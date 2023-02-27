# Componentes e Design Systems Impactados

(#componentes_e_design_systems_impactados)

<p align="center">
  <a href="https://www.blueprojects.com.br/" rel="noopener">
 <img  height=160px src="./images/blueprojects-logotipo-azul-02.png" alt="Bot logo"></a>
</p>

<h3 align="center">HSBC - Portal WEB - Components Issues.</h3>
<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/AmoreiraT/HSBC_Components_Issues/issues)

</div>

---

<p align="center"> 🤖 Componets e Design Systems, adequações e diferenças entre propostas praticaveis em tempo hábil em fronte à propostas de customização de Design System. Aqui serão notados apenas os components de maior custo para criação e impactos à usabilidade para a entrega em tempo hábil.
    <br> 
</p>

## 📝 Índice

- [Sobre](#sobre)
- [Figma](#figma)
- [Date Pickers](#datePicker)
- [Custom Progress Tracker](#progressTracker)
- [Table Data](#tableData)
- [Native Components](#nativeComponents)
- [Versionamentos](#versionamentos)
- [Links](#links)
- [Autores](#autor)

## 🧐 Sobre <a name = "sobre"></a>[🔝](#componentes_e_design_systems_impactados)

Write sobre 1-2 paragraphs describing the purpose of your bot.

## 🎨 Figma <a name = "figma"></a>[🔝](#componentes_e_design_systems_impactados)

```
Protótipo do Portal Web em tempo real.
```

<div align="center">
<a id="iframeLink" href="https://www.figma.com/proto/JHPXOOzrbejTLOK0593s7u/HSBC-Web?page-id=0%3A10&node-id=1359%3A9949&viewport=321%2C-255%2C0.14&scaling=contain&starting-point-node-id=1359%3A9949"><div id="iframeDiv"><img src="./images/embeedPrototype.png" ></div></a></p>
</div>
 <br/>

---

 <br/>

```
Design UI em tempo real.
```

<div align="center">
<a id="iframeLink" href="https://www.figma.com/file/JHPXOOzrbejTLOK0593s7u/HSBC-Web?node-id=0%3A10&t=ishXP9WoRTXOQx8X-1"><div id="iframeDiv"><img src="./images/openDesignUI.png" ></div></a></p>
</div>
 <br/>

  <br/>

---

 <br/>

## 📅 Date Pickers <a name = "datePicker"></a>

> Wholesale Web Toolkit Version: 4.0.0 December 2021. Páginas: 3, 4, 70, 71, 72

The bot first extracts the word from the comment and then fetches word definitions, part of speech, example and source from the Oxford Dictionary API.

If the word does not exist in the Oxford Dictionary, the Oxford API then returns a 404 response upon which the bot then tries to fetch results form the Urban Dictionary API.

The bot uses the Pushshift API to fetch comments, PRAW module to reply to comments and Heroku as a server.

The entire bot is written in Python 3.6
<br/>

---

 <br/>
## ➡️ ProgressTracker <a name = "progressTracker"></a>

To use the bot, type:

```
!dict word
```

The first part, i.e. "!dict" **is not** case sensitive.

The bot will then give you the Oxford Dictionary (or Urban Dictionary; if the word does not exist in the Oxford Dictionary) definition of the word as a comment reply.

### Example:

**Definition:**

Baby, dont hurt me~
Dont hurt me~ no more.

**Example:**

Dude1: Bruh, what is love?
Dude2: Baby, dont hurt me, dont hurt me- no more!
Dude1: dafuq?

---

<sup>Want to make a similar reddit bot? Check out: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup>

## 📑 Table Data <a name = "tableData"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [nativeComponents](#nativeComponents) for notes on how to deploy the project on a live system.

### Prerequisites

 <br/>

---

 <br/>

## 📟 Native Components <a name = "nativeComponents"></a>

To see an example project on how to deploy your bot, please see my own configuration:

- **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

 <br/>

---

 <br/>

## 📍 Versionamentos <a name = "versionamentos"></a>

- [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
- [Heroku](https://www.heroku.com/) - SaaS hosting platform

 <br/>

---

 <br/>

## 🕸️ Acessos <a name = "links"></a>

> Protótipo do Portal Web em tempo real. <br/> > **Link:** https://www.figma.com/proto/JHPXOOzrbejTLOK0593s7u/HSBC-Web?page-id=0%3A10&node-id=1359%3A9949&viewport=321%2C-255%2C0.14&scaling=contain&starting-point-node-id=1359%3A9949

> Design UI em tempo real. <br/> > **Link:** https://www.figma.com/file/JHPXOOzrbejTLOK0593s7u/HSBC-Web?node-id=0%3A10&t=ishXP9WoRTXOQx8X-1

 <br/>

---

 <br/>

## 🎉 Autores <a name = "autor"></a>

- Thiago Moreira
- Lincoln Silva
- Estevão
