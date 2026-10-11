# Modo Avião · CVC

Página para o culto da Comunidade de Vida Cristã Bruxelas: as pessoas escaneiam um QR code e abrem uma página com fundo animado lembrando que a única conexão que elas precisam é com Deus, e que é hora de ligar o modo avião.

- `index.html`: a página que as pessoas abrem no celular.
- `qr.html`: gera o QR code que aponta para a página (pronto para imprimir ou projetar).
- `assets/`: logo da CVC e o mascote do Jesus (recortado e otimizado em WebP).
- `vendor/qrcode.js`: biblioteca de QR code (MIT, Kazuhiko Arase), incluída localmente para funcionar sem CDN.

## Publicar no GitHub Pages

1. No GitHub, abra **Settings → Pages**.
2. Em **Source**, escolha *Deploy from a branch*, selecione a branch e a pasta `/ (root)` e salve.
3. A página fica em `https://<usuario>.github.io/cvc/` e o QR code em `https://<usuario>.github.io/cvc/qr.html`.

O `qr.html` aponta automaticamente para a página principal do mesmo site. Para gerar um QR para outro endereço (por exemplo, um domínio próprio), use `qr.html?url=https://seu-endereco`.
