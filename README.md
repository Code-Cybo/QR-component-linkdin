# linkdin - QR code component

When you scan the code you will be redirected to Linkdin profile

## Table of contents

- [Overview)
  - [Links]
- [My process]
  - [Built with]
  - [What I learned]
  - [Continued development]
  - [Useful resources]
- [Author]
- [Acknowledgments]

## Overview
In this project we have created a QR code component. when we scan it we are redirected to my linkdin profile
### Screenshot
 

![](Design/website_preview.jpg)

### Links
- Live Site URL: 

## My process
- At first we have created two divs.
- Specified css file in HTML code.
- By using CSS we have specified font-size and font-family.
- Align the created divs.
- defined CSS code for each div.
- Added image and text and configured them.
- At last added other arts into the site.

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned
- While building this site i came across many issues while aligning the components, so i learned how we can use VH and VW
foe defining sizes.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>QR Code</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="shortcut icon" href="images/favicon.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit&display=swap" rel="stylesheet">
  </head>
  <body>
    <div class="main">
      <img src="images\circle.png" class="circle" alt="circle">
      <img src="images\dots.png" class="dot" alt="dots">
      <img src="images\l.png" class="l" alt="l">
      <img src="images\wave.png" class="wave" alt="wave">
      <div class="qr">
        <img src="images\image-qr-code.png" class="img" alt="QR">
        <h3 class="tzt">Improve your front-end skill by building projects</h3>
        <p class="txt">Scan above qr code to visit my Linkdin profile and follow to see content related to Robotics</p>
      </div>
    </div>
  </body>
</html>

```

```css

body{
  font-family: 'Outfit', sans-serif;
  /* background-color: #7b879d ; */
  background-color: #f2f6fd;
  margin: 0;
  text-align: center;
}
.main{
  width: 70vw;
  background-color:  #d6e2f0;
  /* margin: auto auto; */
  /* margin-top: 90px; */
  margin: 15vh 15vw;
  height: 70vh;
  border-radius: 10px;
  box-shadow: 0 10px 20px lightgrey;
}
.qr{
  background-color: white;
  width: 20vw;
  height: 60vh;
  border-radius: 10px;
  position: absolute;
  top: 20vh;
  left: 40vw;
  box-shadow: 0 15px 20px lightblue;
}
.img{
  width: 17vw;
  height: 33vh;
  margin: 0;
  margin-top: 15px;
  border-radius: 15px;
}
.txt{
  margin: 10px 0 20px 2.7vw;
  font-size: 15px;
  width: 15vw;
}
.tzt{
  margin: 10px 0 5px 1.8vw;
  font-size: 1.5vw;
  width: 17vw
}
.dot{
  position: absolute;
  top: 45vh;
  left: -5vw;
}
.wave{
  position: absolute;
  top: 30vh;
  right: -2vw;
}
.l{
  height: 80px;
  position: absolute;
  top: -2vh;
  left: 60vw;
}
.circle{
  height: 400px;
  width: 400px;
  position: absolute;
  bottom: -30vh;
  left: 40vw;
}

```

### Continued development

eed to work on CSS sizing to overcme the problems i fced this time.

### Useful resources

- Resouce 1 (https://icons8.com/icons/)- this really helped me to find designs and arts for the site.

- Resouce 2 (http://www-db.deis.unibo.it/courses/TW/DOCS/w3schools/colors/colors_picker.asp-colorhex=D3D3D3.html#gsc.tab=0)- This helped me selecting colours

## Author

- Website - Om Sonar 
- Frontend Mentor - [@Code-Cybo](https://www.frontendmentor.io/profile/Code-Cybo)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Always take help from internet whenever you are stuck at some point for long time.
