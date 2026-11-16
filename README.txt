# HUJ Studio AI — versão 2.0

Atualização da primeira versão, mantendo o projeto PWA sem bibliotecas externas.

## Recursos
- Câmera com troca frontal/traseira, temporizador e grade 3x3.
- Controles de zoom, compensação de exposição e flash somente quando a câmera/navegador expõem suporte.
- Editor com exposição, brilho, contraste, realces, sombras, saturação, temperatura, vinheta e preto e branco.
- Presets Natural, Cinematográfico, Dark urbano, Preto e branco, Quente e Frio.
- Exportação JPEG e cópia editada na biblioteca local.
- Assistente local com análise de luminosidade, sombras, realces e tendência de cor.
- Biblioteca IndexedDB e cache offline via Service Worker.

## Limitações
- O Chrome/Safari no iPhone não expõe todos os controles de uma câmera nativa. ISO manual, velocidade do obturador, RAW/DNG e foco manual podem não estar disponíveis.
- Flash/zoom/exposição só aparecem como utilizáveis quando o dispositivo informa suporte.
- O assistente é análise computacional local por regras; não é IA generativa nem reconhecimento semântico.
- A primeira visita deve ser feita online em HTTPS para instalar o cache. A permissão de câmera pode ser solicitada novamente.
- Fotos são guardadas no armazenamento do navegador deste aparelho. Limpar dados do site pode apagá-las; faça exportação/backup das fotos importantes.

## Atualizar o GitHub Pages
Substitua os arquivos antigos pelos arquivos desta pasta no repositório e confirme o commit. O Service Worker usa o cache `huj-studio-v2` para atualizar a versão anterior.
