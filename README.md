# CENTRALUX CONTAGEM

App web de contagem de estoque por SKU. Funciona direto no navegador (desktop e celular), sem instalação e sem servidor.

**Acesse:** https://pedroliang.github.io/centralux-contagem/

## Recursos

- Registro rápido de SKU + quantidade (Enter avança entre os campos)
- Detecção de SKU duplicado com opção de somar ou substituir
- Totais de SKUs e unidades em tempo real
- Nome do responsável e data da contagem
- Prévia do texto da contagem, cópia e download em `.txt`
- Grupos de destino salvos (WhatsApp ou link) para envio rápido
- Dados mantidos no navegador (localStorage) entre sessões

## Uso local

Baixe o repositório e abra `index.html` no navegador. Todos os arquivos precisam ficar na mesma pasta.

## Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | Página do app (marcação + lógica) |
| `support.js` | Runtime que renderiza a página |
| `styles.css` | Tokens de tema e estilos |
| `_ds/` | Design system de origem (referência) |
| `.nojekyll` | Impede o GitHub Pages de ignorar a pasta `_ds` |
