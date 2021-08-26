## 💻 Resumo do projeto

Este repo não possui uma interface gráfica amigavél, a proposta do mesmo é a apenas a funcionalidade de gerar o QR com o conteúdo que o usuário desejasse, foi utilizado o Next.js para geração de novos QR codes sem a necessidade de "carregar" a página usufruindo do server side rendering.

## 🛠 Tecnologias

Projeto foi construído utilizando **Node.js** e o **Next.js** e as seguintes dependências:

- **[QRcode SVG](https://www.npmjs.com/package/qrcode-svg)** é uma lib para gerar uma imagem SVG de QR Code em Node.js com qualquer conteúdo que você deseja.

## 📕Como usar

Para utilizar basta executar localmente e no corpo do link passar o site ou texto que deseja gerar, conforme exemplo abaixo:

```bash
http://localhost:3000/api?url=TEXTO
```

Lembrando que pode colocar espaço e/ou acentos e caracteres especiais e pressionar a tecla `enter` que será corrigido (sem remover) automaticamente. Agora caso deseje gerar um QR Code de link basta fazer da seguinte forma:

```bash
http://localhost:3000/api?url=https://teste.com.br
```

## 🔨 Instalação Local

Você precisará do [Node.js](https://nodejs.org) versão 10 ou superior, instalado no seu computador para continuar.

```bash
git clone https://github.com/JhonyWalker-pixel/qrcode-dynamic.git

$ cd qrcode-dynamic
$ npm install
```

E agora para rodar nosso projeto localmente basta executar o seguinte comando:

```bash
$ cd qrcode-dynamic
$ npm start
```

## 📖 License

Este projeto está sob a licença do MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
