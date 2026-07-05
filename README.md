# Outro Sem Dono · Cartão de Visita Virtual

Cartão de visita virtual da loja, em uma única página (`index.html`), com:

- 🪝 **Logo** (ícone de cabide — pode ser trocado pela sua imagem)
- 📸 **Instagram** (@outrosemdono)
- 📍 **Como chegar na loja** (botão que abre o Google Maps)
- 📦 **Opção de retirada na loja**
- 🕘 **Horário de funcionamento**

## Como personalizar

Abra o arquivo `index.html` e procure pelos comentários `EDITE AQUI`:

1. **Endereço**: troque `Rua Exemplo, 123 - Centro` no link do Google Maps e no texto do botão pelo endereço real da loja.
2. **Horários**: ajuste a tabela de horário de funcionamento.
3. **Logo**: se tiver uma imagem de logo, salve como `logo.png` na raiz do projeto e substitua o `<svg>` dentro da `<div class="logo">` por `<img src="logo.png" alt="Logo">`.
4. **Instagram**: se o @ da loja for diferente de `@outrosemdono`, atualize o link e os textos.

## Como publicar (GitHub Pages)

1. No GitHub, vá em **Settings → Pages**.
2. Em **Source**, escolha a branch principal e a pasta `/ (root)`.
3. Salve — em alguns minutos o cartão estará no ar em `https://<seu-usuario>.github.io/outrosemdono/`.

Esse link pode ser colocado na bio do Instagram. 😉
