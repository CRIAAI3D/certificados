# Cert Generator — Online

Sistema online para emissão de certificados da Extremo Brazilian Jiu-Jitsu.

Esta versão é preparada para GitHub Pages ou Firebase Hosting.

## Pastas principais

- `index.html`: aplicação
- `assets/`: logos, imagens e scripts
- `assets/js/firebase-config.js`: configurações do Firebase
- `firestore.rules`: regras de segurança do Firestore
- `firebase.json`: configuração para Firebase Hosting
- `.nojekyll`: evita problemas de publicação no GitHub Pages

## Antes de publicar

Edite `assets/js/firebase-config.js` e cole as configurações do seu Firebase Web App.

Depois, no Firebase:
1. Ative Authentication com E-mail/senha e Google.
2. Crie o Firestore em modo produção.
3. Publique as regras do arquivo `firestore.rules`.
4. Crie o documento `usersByEmail/SEU_EMAIL`.
