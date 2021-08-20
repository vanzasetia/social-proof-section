# Chat App CSS Illustration

<p align="left">
  <img src="https://img.shields.io/badge/Difficulty-Intermediate-yellow?style=for-the-badge&logo=frontendmentor" alt="Difficulty">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/vanzasetia/chat-app-css-illustration?style=for-the-badge&logo=github">
  <a href="https://twitter.com/vanzasetia" target="_blank"><img src="https://img.shields.io/twitter/follow/vanzasetia?logo=twitter&style=for-the-badge" alt="Twitter followers." /></a>
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vanzasetia/chat-app-css-illustration?style=for-the-badge&logo=git">
  <img alt="Netlify" src="https://img.shields.io/netlify/9c613af3-0754-41ce-b44d-b5396b4738a8?style=for-the-badge&logo=netlify">
</p>
<p>
  <a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>

## Feedback and Live Review
* [🌍 Live Review](https://vanzachatapp.netlify.app/)
* [👉 Give feedback on Frontend Mentor platform](https://www.frontendmentor.io/solutions/chat-app-css-illustration-html-css-sass-85OdKVY48)
* [🐦 Give Feedback on Twitter](https://twitter.com/vanzasetia/status/1427479692987174915?s=19)

## Screenshot
![Desktop preview](./screenshots/desktop.jpg)

## Table of contents
- [Story](#the-story-when-doing-this-challenge)
  - [When Building the body background](#body-background)
  - [When Building the Person Part](#person)
  - [When Building the Chat Part](#chat)
  - [Animation Part](#animation)
- [What I Learned](#what-i-learned)
- [Technology that I used](#built-with)
- [Continued Development](#continued-development)

## The Story When Doing This Challenge
I used my [color picker](https://play.google.com/store/apps/details?id=gmikhail.colorpicker) and got this color `rgb(250, 250, 250)` for the body background color.

### Body Background
This was so hard. So, I used CSS pseudo elements for the top and bottom background. I used absolute positioning and it worked!

But for the bottom one I couldn't make it *full width*, like the gradient (the top one), so I just created with the half width. The reason for it because, even after I applied `overflow-x: hidden` on the `body`, It's still causing a horizontal scroll bar appeared.

When it came to a moment where I need to make it responsive, it's scary. After several times trying to us`clamp()` and `calc()`, which are [CSS Math Functions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions). I didn't make it using those functions 😞.

Ultimately, I ended up with the *normal* way of doing that by setting up media queries to change the size of the background for "every screen size" 😅.

### Person
The `person` part I used flexbox to control the layout. I used `svg` for the chevron left and three dots icons.

### Chat
I noticed that the first chat was different. On the mobile it said, *That sounds great. I’d be happy to discuss more.*, while on the desktop it said, *That sounds great. I’d be happy with that.* I decided to follow the desktop version.

For the chat layout, I used flexbox for everything started from chat bubble to input message.

### Animation
For the animations, I will do it on my second try.

## What I Learned
* I learned to create illustration using HTML and CSS.
* I learned a little bit about `clamp()` and `calc()`.

## Built With
This project created using **HTML5**, **CSS3**, and **Sass**. I used flexbox to handle every layout.

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="" width="auto" height="70px">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="" width="auto" height="70px">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="" width="auto" height="70px">
</p>

## Continued development
I will take people feedback and improve this solution. Also, I will try to add animations and try to use `calc()` or `clamp()` for my second try, in the future.