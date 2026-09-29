# Manual de Boas Práticas — Comissões Macrorregionais de Acompanhamento (CMA)

Site do manual das CMA — SES/MG · Subsecretaria de Regionalização · CMIR.

## Como publicar no GitHub Pages

1. Crie o repositório (ex.: `cmir-ses-mg/manual-cma`).
2. Envie o conteúdo desta pasta na raiz do repositório:
   - `index.html`
   - `docs/` (os PDFs)
3. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`.
4. O site fica em `https://cmir-ses-mg.github.io/manual-cma/`.

## Atualizar um documento

Substitua o arquivo dentro de `docs/` mantendo o mesmo nome. Os links do site
continuam funcionando sem nenhuma alteração no `index.html`.

| Link no site | Arquivo |
|---|---|
| Manual completo | `docs/manual-boas-praticas-cma.pdf` |
| Regimento Interno das CMA | `docs/resolucao-10512-2025-regimento-cma.pdf` |
| Errata da 10.512 | `docs/errata-resolucao-10512-2025.pdf` |
| Resolução 11.044/2026 | `docs/resolucao-11044-2026.pdf` |
| Resolução 10.382/2025 | `docs/resolucao-10382-2025.pdf` |
| Decreto 49.080/2025 | `docs/decreto-49080-2025.pdf` |
| SESResolve | link externo (https://sesresolve.saude.mg.gov.br/) |

O `index.html` é autocontido: fontes embutidas, sem dependência externa.
Se os PDFs não estiverem presentes, a seção de downloads se oculta sozinha.
