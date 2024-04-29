# Simple React Project using a font

This project is just that: a project example to learn how to use a font in React.

## Getting Started

The final result looks like this:

![Screenshot](/screenshots/screenshot-01.png)

## Prerequisites

You need a working environment with:
* [Git](https://git-scm.com) - You can install it from https://git-scm.com/downloads.
* [Node.js](https://nodejs.org) - Install node.js from https://nodejs.org/es/download/. It's advisable to install the LTS version.

## General Installation instructions

Clone this project:

```
git clone https://github.com/tcrurav/react-fonts.git
```

Now install all dependencies.

```
cd react-fonts
npm install
```

And finally run the project.

```
cd react-fonts
npm run dev
```

Enjoy!!!

## Include a font in your React Project

Follow the instructions in the site of your chosen font. In my case the instructions are here: https://www.onlinewebfonts.com/download/f323892ea5283141dbbbec176c9e3ee7

1. Step 1: copy the link line in your index.html in your react project:
```
<link href="https://db.onlinewebfonts.com/c/f323892ea5283141dbbbec176c9e3ee7?family=Antique+Olive+Nord+Italic" rel="stylesheet">
```

2. Step 2: I have used the font in Home.css like this:
```
p {
  font-family: "Antique Olive Nord Italic";
}
```

## Built With

* [Visual Studio Code](https://code.visualstudio.com/) - The Editor used in this project
* [Node.js](https://nodejs.org/) - Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.
* [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling. Get ready for a development environment that can finally catch up with you.

## Acknowledgments

* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2. A very complete template for README.md files.
* https://www.onlinewebfonts.com/download/f323892ea5283141dbbbec176c9e3ee7. The font used in this project.
* https://www.onlinewebfonts.com/fonts. Online web fonts for your projects.
