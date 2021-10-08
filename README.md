## 💻 Project summary

This repo does not have a user-friendly graphical interface, its proposal is just the functionality to generate the QR with the content that the user wanted, Next.js was used to generate new QR codes without the need to "load" the page taking advantage of server side rendering.

## 🛠 Technologies

Project was built using **Node.js** and **Next.js** and the following dependencies:

- **[QRcode SVG](https://www.npmjs.com/package/qrcode-svg)** - This library has been written to generate a SVG image of QR Code in Node.js

## 📕 How to use:

To use it, just run it locally and in the body of the link, pass the site or text you want to generate, as shown below:

```bash
http://localhost:3000/api?url= TEXT OR LINK OF YOUR CHOICE
```

Remembering that you can put space and/or accents and special characters and press the `enter` key which will be corrected (without removing) automatically. Now if you want to generate a QR Code link, just do as follows:

```bash
http://localhost:3000/api?url=https://teste.com.br
```

## 🔨 Local Installation

You need [Node.js](https://nodejs.org) version 10 or higher, but if you want to use [Yarn](https://yarnpkg.com/) you can also just have it on your computer to continue.

```bash
git clone https://github.com/JhonyWalker-pixel/qrcode-dynamic.git

$ cd qrcode-dynamic
$ npm install or yarn install
```

And now, to run locally, just run the following command:

```bash
$ cd qrcode-dynamic
$ npm start or yarn start
```

## 📖 License

This project is under license from MIT. See the [LICENSE](LICENSE.md) file for more details.
