
# SGC – GitHub Pages (Static)

Este pacote contém um site **estático** do SGC pronto para publicar no **GitHub Pages** e usar como Tab do Microsoft Teams.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `sgc-app`).
2. Envie os arquivos deste pacote para a branch `main` (raiz).
3. No GitHub: Settings → Pages → Build and deployment: selecione **Deploy from a branch**, branch **main**, folder **/**.
4. Aguarde a URL aparecer (algo como `https://SEU-USUARIO.github.io/sgc-app/`).

## Apontar o Manifest do Teams
- Edite o `manifest.json` do pacote do Teams (manifest zip) e troque:
  - `contentUrl` e `websiteUrl` → pela URL do GitHub Pages + `/index.html`.
  - inclua `SEU-USUARIO.github.io` em `validDomains` se necessário.

Pronto! O app abrirá as pastas do SharePoint **dentro do SGC**.
