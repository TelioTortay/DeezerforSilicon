# DeezerforSilicon
Deezer client for M1 Mac. Electron based.

## Installer DeezerforSilicon 🚀
1. Téléchargez le .zip dans les [releases](https://github.com/TelioTortay/DeezerforSilicon/releases/tag/main-release).
2. Copiez le .app dans votre dossier "Applications".
3. Si vous avez une erreur de type "Développeur non reconnu", entrez dans le terminal et entrez ceci : ``sudo spctl --master-disable``
4. Le tour est joué !

## Dépendences
DeezerforSilicon dépend de :
- NodeJS // npm
- Electron
- [nativefier](https://github.com/nativefier/nativefier)

## How to
DeezerforSilicon is based on Electron, and packaged with [nativefier](https://github.com/nativefier/nativefier).
```nativefier "https://deezer.com" --name 'Deezer' --title-bar-style 'hiddenInset' --icon 'Deezer.icns' --copyright '© Deezer 20xx - Created by Télio Tortay' --app-version 'x.x.x' --background-color '#131316' --inject 'injectdeezer.css'```
