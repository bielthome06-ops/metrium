# METRIUM — Segurança Industrial

Site em um único arquivo (`index.html`), sem build e sem dependências.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub e envie `index.html` e este `README.md`.
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Aguarde alguns minutos: o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Editar
No início do `<script>` do `index.html`:
- `CONFIG`: WhatsApp, e-mail, endereço, Instagram, frete, formas de pagamento e políticas.
- `PRODUCTS`: produtos, preços, categorias e especificações.
- `IMG`: imagens embutidas em base64.

## Importante
- Pedidos, devoluções e orçamentos ficam apenas no navegador (localStorage). Para vender de verdade, é preciso um servidor e um gateway de pagamento (`PAYMENT.createCheckout`).
- Preços, códigos e especificações são exemplos.
