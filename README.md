# Gerador de Contratos — Chácara Recanto Alvorada

Site estático (sem back-end) que preenche o contrato de locação a partir de `modelo.docx`.

- **Individual:** preencha o formulário e baixe o `.docx`.
- **Em massa:** baixe a planilha modelo (CSV), preencha uma linha por contrato, envie e baixe um `.zip`.

## Publicar no GitHub Pages
1. Crie um repositório e envie estes arquivos.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.

## Alterar o texto do contrato
Edite `modelo.docx` no Word. Os campos são marcadores entre chaves, ex.: `{loc_nome}`, `{valor_total}`.
