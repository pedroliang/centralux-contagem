# CENTRALUX CONTAGEM

App web de contagem de estoque por SKU. Funciona direto no navegador (desktop e celular), sem instalação e sem servidor.

**Acesse:** https://pedroliang.github.io/centralux-contagem/

## Recursos

- Registro rápido de SKU + quantidade (Enter avança entre os campos)
- Detecção de SKU duplicado com opção de somar ou substituir
- Totais de SKUs e unidades em tempo real
- Nome do responsável e data da contagem
- Prévia do relatório e download em `.txt`
- Botão **Enviar no WhatsApp** com três níveis de fallback:
  1. compartilha o `.txt` já anexado pela folha de compartilhamento do celular;
  2. se o aparelho não compartilhar arquivos, compartilha o relatório como texto;
  3. se nem isso, copia o relatório e abre o app do WhatsApp para colar.
- Dados mantidos no navegador (localStorage) entre sessões
- Página única, sem dependências externas — funciona offline depois de carregada

## Uso local

Baixe `index.html` e abra no navegador. É um arquivo único e autossuficiente.

## Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | O app inteiro: HTML, CSS e JavaScript em um arquivo só |
| `Centralux Contagem.dc.html` | Versão original do editor visual (referência) |
| `support.js`, `styles.css`, `_ds/` | Arquivos da versão original — não são usados pelo `index.html` |
| `.nojekyll` | Impede o GitHub Pages de ignorar a pasta `_ds` |
