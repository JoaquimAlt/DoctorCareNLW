# DoctorCareNLW
<div style="display: inline_block">
<h2> Projeto Web de: </h2>
<img align="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img align="center" alt="css" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img align="center" alt="css" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</div><br/>

# Preview
### Com 3 adaptações de display temos:
## Smartphone/Tablet `320px-1023px` 
<img height="320rem" src="https://user-images.githubusercontent.com/63430363/167310509-0ef6f0c7-7aa4-4c40-a251-743648038248.gif"> <br>
## Desktop  `1024px ...` 
<img height="320rem" src="https://user-images.githubusercontent.com/63430363/167311473-b39940f6-9402-451d-91f1-9a8d0121a0e8.gif">

# Introdução a `HTML` e `CSS`
Iniciaremos com assuntos básicos de estrutura, nomenclatura e anatomia de HTML e CSS.
- [Editores de texto e organização de pastas](#editores-de-texto);
- [HTML: anatomia e introdução de tags](#html);
- [CSS: anatomia e introdução de propriedades](#css);
- [Classes, id](#classes-e-id);
- [Github Desktop](#github-desktop).

#### Editores de texto
Para se modificar um arquivo .html e .css, precisamos de editor de texto. Apesar de que um simples bloco de notas pode ser a ferramenta para criação desses arquivos, vários softwares foram lançados no mercado para gostos dos programado res, oferecendo facilidades e plugins para facilitar o desenvolvimento. Alguns famosos e notáveis são:
- [Sublime Text](https://www.sublimetext.com/);
- [Notepad++](https://notepad-plus-plus.org/);
- [Atom](https://atom.io/);
- Usado no Projeto: [Visual Studio Code](https://code.visualstudio.com/);

<p align="center">
	<a href="https://scrollrevealjs.org" title="Visit ScrollReveal home page">
		<img src="https://scrollrevealjs.org/img/logomark.svg" alt="ScrollReveal" width="120">
	</a>
</p>
<br>
<p align="center">
	<a href="https://scrollrevealjs.org" title="Visit ScrollReveal home page">
		<img width="200" src="https://scrollrevealjs.org/img/scrollreveal-logotype-dark.svg" alt="ScrollReveal">
	</a>
</p>
<p align="center">Animate elements as they scroll into view.</p>

<p align="center">
	<a href="https://travis-ci.org/jlmakes/scrollreveal">
		<img src="https://img.shields.io/travis/jlmakes/scrollreveal.svg" alt="Build status">
	</a>
	<a href="https://www.npmjs.com/package/scrollreveal">
		<img src="https://img.shields.io/npm/dm/scrollreveal.svg" alt="Monthly downloads">
	</a>
	<a href="https://www.npmjs.com/package/scrollreveal">
		<img src="https://img.shields.io/npm/v/scrollreveal.svg" alt="Version">
	</a>
	<img src="https://img.shields.io/badge/min+gzip-5.7_kB-blue.svg" alt="5.7 kB min+gzip">
	<a href="https://opensource.org/licenses/GPL-3.0">
		<img src="https://img.shields.io/badge/license-GPLv3-blue.svg" alt="GPLv3 License">
	</a>
</p>

<br>

# Introduction

ScrollReveal is a JavaScript library for easily animating elements as they enter/leave the viewport. It was designed to be robust and flexible, but hopefully you’ll be surprised below at how easy it is to pick up.

<br>

# Installation

## Browser

A simple and fast way to get started is to include this script on your page:

```html
<script src="https://unpkg.com/scrollreveal"></script>
```

This will create the global variable `ScrollReveal`

> Be careful using this method in production. Without specifying a fixed version number, Unpkg may delay your page load while it resolves the latest version. Learn more at [unpkg.com](https://unpkg.com)

## Module

```bash
npm install scrollreveal
```

#### CommonJS

```js
const ScrollReveal = require('scrollreveal')
```

#### ES2015

```js
import ScrollReveal from 'scrollreveal'
```

<br>

# Usage

Installation provides us with the constructor function [`ScrollReveal()`](https://scrollrevealjs.org/api/constructor.html). Calling this function returns the ScrollReveal instance, the “brain” behind the magic.

> ScrollReveal employs the singleton pattern; no matter how many times the constructor is called, it will always return the same instance. This means we can call it anywhere, worry-free.

There’s a lot we can do with this instance, but most of the time we’ll be using the [`reveal()`](https://scrollrevealjs.org/api/reveal.html) method to create animation. Fundamentally, this is how to use ScrollReveal:

```html
<h1 class="headline">
	Widget Inc.
</h1>
```

```js
ScrollReveal().reveal('.headline')
```

**🔎 See this demo live on [JSBin](http://jsbin.com/jufohaxonu/edit?html,output)**

<br>
