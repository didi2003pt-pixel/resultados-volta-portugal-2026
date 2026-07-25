# Resultados — Volta a Portugal à Vela 2026

Este repositório contém o site público de resultados.

## Estrutura

- `index.html` — página inicial
- `resultados/anc.html` — resultados ANC
- `resultados/orc.html` — resultados ORC
- `.nojekyll` — impede processamento Jekyll

## Antes de publicar

Nos ficheiros `resultados/anc.html` e `resultados/orc.html`, substituir:

```javascript
const APPS_SCRIPT_URL = 'COLE_AQUI_A_URL_DA_APLICACAO_WEB';
```

pela URL `/exec` gerada no Google Apps Script.

## GitHub Pages

1. Criar um repositório público.
2. Carregar todos estes ficheiros e pastas.
3. Abrir `Settings > Pages`.
4. Escolher `Deploy from a branch`.
5. Branch: `main`.
6. Pasta: `/root`.
7. Guardar.

O endereço será semelhante a:

`https://UTILIZADOR.github.io/resultados-volta-portugal-2026/`
