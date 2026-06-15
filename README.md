# Form Captura (ViDi)

Formulário interativo de diagnóstico estratégico da ViDi com integrações ativas (Google Sheets, DataCrazy CRM e Meta Pixel).

## 🚀 Fluxo de Deploy (IMPORTANTE)

Este repositório utiliza o **GitHub Pages** hospedado a partir da branch **`gh-pages`**. 

Sempre que fizer alterações no código (na branch `master`), siga as etapas abaixo para publicar as alterações no ar:

1. **Finalizar e comitar as alterações na branch `master`**:
   ```bash
   git checkout master
   # ... fazer alterações ...
   git add .
   git commit -m "sua mensagem"
   git push origin master
   ```

2. **Atualizar a branch de deploy (`gh-pages`)**:
   ```bash
   git checkout gh-pages
   git merge master
   git push origin gh-pages
   git checkout master
   ```
