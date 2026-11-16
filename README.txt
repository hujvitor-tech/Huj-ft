# HUJ Studio AI — versão 3.0

Atualização offline-first para o iPhone XR, sem bibliotecas externas e sem custo de hospedagem no GitHub Pages.

## Novidades 3.0
- Melhorar automaticamente: estima luminosidade e contraste da imagem e aplica ajustes locais editáveis.
- Histograma de luminosidade para visualizar a distribuição tonal da foto.
- Presets personalizados: salve, aplique e exclua suas próprias combinações de ajustes neste aparelho.
- Mantém os recursos da 2.1: câmera com grade/temporizador e controles condicionais, editor com temperatura, matiz, nitidez, vinheta, rotação, espelhamento, comparação antes/depois, presets prontos, exportação JPEG e biblioteca local.
- Cache do Service Worker atualizado para v3.0.

## Privacidade e limitações
- Processamento de imagem e presets personalizados acontecem localmente no navegador. Fotos não são enviadas a um servidor por este aplicativo.
- A melhoria automática é um algoritmo simples baseado em luminosidade e contraste; não é IA generativa nem reconhecimento de objetos.
- O histograma representa a luminosidade da imagem original aberta no editor.
- Controles avançados da câmera dependem do suporte exposto pelo Chrome/Safari no iPhone. ISO manual, obturador manual, RAW/DNG e foco manual não são garantidos.
- A primeira visita deve ocorrer online em HTTPS para instalar o cache. Limpar dados do site pode apagar fotos da biblioteca e presets guardados localmente; exporte/guarde fotos importantes.

## Atualizar pelo GitHub no iPhone
Substitua os cinco arquivos da raiz do repositório pelos arquivos deste pacote e confirme o commit. Não apague o README.md existente do GitHub, se quiser mantê-lo.
