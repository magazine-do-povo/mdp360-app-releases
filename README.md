# MDP360 — Releases do app

Repositório PÚBLICO de distribuição do app PovoVendas (MDP360):

- **APK**: anexado em cada release (`v<versão>`)
- **`mdp360-app-version.json`**: manifesto lido pelo auto-update do app
  (`{ version, buildNumber, apkUrl, forceUpdate, releaseNotes }`)

O código-fonte vive no repositório privado `magazine-do-povo/MDP360`.
As releases são publicadas automaticamente pelo workflow `deploy-app.yml` de lá
quando a versão em `app/package.json` muda.
