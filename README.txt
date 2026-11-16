# HUJ Studio AI — versão 1.0

Primeira versão experimental, feita para abrir em Safari no iPhone.

## Incluído
- Pré-visualização e captura pela câmera do navegador
- Alternância entre câmera frontal e traseira
- Importação de fotos
- Ajustes de brilho, contraste, saturação, sépia e preto e branco
- Presets básicos
- Análise local simples de luminosidade
- Biblioteca local com IndexedDB
- Cache offline por Service Worker

## Limitações importantes
- Precisa ser publicado em um endereço HTTPS para acessar a câmera.
- Abra primeiro no Safari, permita a câmera e carregue o app online ao menos uma vez.
- A câmera pode solicitar permissão novamente em cada abertura do app instalado na Tela de Início.
- Controles avançados como ISO, velocidade, RAW/DNG e flash não são expostos de forma consistente pelo Safari no iPhone.
- O assistente desta versão usa análise local simples, não um modelo generativo de IA.
- A exportação salva uma cópia JPEG; a foto original permanece intacta.

## Publicar gratuitamente
Envie estes arquivos para um serviço de hospedagem estática HTTPS com plano gratuito. Depois abra o endereço no Safari e use Compartilhar > Adicionar à Tela de Início.
