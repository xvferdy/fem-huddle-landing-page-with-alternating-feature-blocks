# Huddle landing page with alternating feature blocks

> 🔖 This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100).

## 🌈 ✨ 🎉 Have Fun Building! 🚀 🎊 🎈
> 🖥️ **Welcome** <br>
> Thanks for checking out this front-end coding challenge.
[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.
***To do this challenges, you need a basic understanding of HTML and CSS.*** Press <kbd>Enter</kbd> 🚀 to start the game!!

## 🌍 Table of Contents
- [Brief](#brief)
- [The challenge](#the-challenge)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned-)
- [Difficult Things](#difficult-things-)
- [Author](#author)

## Brief
This challenge is perfect if you're wanting to practice your layout skills. If you're starting to get a bit more confident laying out a web page, give this project a go.

Your challenge is to build out this **landing page** and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go 👍.

**Preview** 👓

![Design preview for the Loopstudios landing page coding challenge](./design/desktop-preview.jpg)

## The challenge 
Users should be able to:
  
| Challenge | Newbie | Junior | Intermediate | Advanced |
| --- | :---: | :---: | :---: | :---: |
| View the optimal layout for the site depending on their device's screen size | ⭕ |  |  |  |
| See hover states for all interactive elements on the page | ⭕ |  |  |  |

[![🐬 Newbie Difficulty List](https://img.shields.io/badge/Difficulty-Newbie-3F54A3?style=for-the-badge&logo=frontendmentor "Newbie Difficulty")](https://www.frontendmentor.io/challenges?difficulties=1)

## Links
- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/huddle-landing-page-with-alternating-feature-blocks-html-sass-SkwcTBjUq)
- Live Site URL: [Gituhb Pages](https://xvferdy.github.io/fem-huddle-landing-page-with-alternating-feature-blocks/)

## My process
> ⌛ I challenge my self to finish this for ***~3 days*** <br>
> ▐ <br>
> 🧑‍💻 ***Day 1:*** Studying the design <br>
> ▐ <sub>Import style guide <kbd>0.5 hour</kbd></sub> <br>
> ▐ <br>
> 🧑‍💻 ***Day 2:*** Code basic layout with [**HTML**](https://developer.mozilla.org/en-US/docs/Web/HTML) & [**Sass**](https://sass-lang.com/) <br>
> ▐ <sub>HTML content <kbd>~1 hour</kbd></sub> <br>
> ▐ <sub>Layout for header <kbd>~2.5 hours</kbd></sub> <br>
> ▐ <br>
> 🧑‍💻 ***Day 3:*** Continuing The layout<br>
> ▐ <sub>Update card layout <kbd>~2.5 hours</kbd></sub> <br>
> ▐ <sub>Desktop layout <kbd>~1 hour</kbd></sub> <br>
> ▐ <sub>Tablet layout <kbd>~1 hour</kbd></sub> <br>
> ▐ <br>
> 🗓️ ***Day 4 onwards:*** Continue some unfinished task & submit the solution to [**Frontend Mentor**](https://www.frontendmentor.io/solutions/huddle-landing-page-with-alternating-feature-blocks-html-sass-SkwcTBjUq "Solution") 🚩 <br>
> ▐ <sub>Mobile layout <kbd>~1 hour</kbd></sub> <br>
> ▐ <br>
> 🗓️ 

## Built with
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML "developer.mozilla")
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html "W3C")

## What I learned 🥳

<details>
    <summary>☑️ <b>flex order</b></summary> <br>
  
`order: 2` will make the property goes second
###### stylesheets/scss/\_huddle.scss
```scss
&__text {
  order: 2;
  text-align: center;
  h2 {
    font-size: 2.5rem;
  }
  p {
    font-size: 1.5rem;
  }
}
&__img {
  order: 1;
}
```
</details>

<details>
    <summary>☑️ <b>Margin with minus value</b></summary> <br>
  
`margin-bottom: -80px;` negative value will places it closer
###### stylesheets/scss/\_huddle.scss
```scss
margin-bottom: -80px;
```
</details>

## Difficult Things 😓
Things were difficult for me and I finally gave up 😓😓
- [ ] **HTML5** Semantic
- [ ] Footer not good
- [ ] No layout for tablet
- [ ] Some _DRY_ **CSS** code

## Author
| [<img src="https://avatars.githubusercontent.com/u/47988956?v=4" alt="xvferdy" width="100px"/><br><sub><samp>Berlianto</samp></sub>](https://github.com/xvferdy)  |
|:---:|

<h3 align="right">
      <a href="#readme">To Top ⤴️</a>
</h3>
