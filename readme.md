# Portfolio page

Our site about Joga

## Installation

We created repo on git.

```bash
git create repository
```

## Project structure

Containing folders...

```
portfolio
│   README.md
│   index.html    
│
└───css
│   │   style.css
│   
└───images
    │   img1.jpg
    │   img2.jpg
```

## Header 

Starting of our page

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Joga</title>
  <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
```

## Sections

```html
<div class="container">
    <div class="part" id="about">
      <h1>About us</h1>
      <img class="img-text" src="images/img4.jpg" alt="history"/>
      <p>
       Welcome Beginners!
       We are here to support you in your new path which is Yoga.
       When you’re brand new to yoga, it can feel intimidating and be difficult to know exactly where and how to get started. Our Yoga for Beginners guide was created specifically for you—to give you all the tips, guidelines, and recommendations you will need to start a successful yoga practice.
     </p>
```

Tak zbudowane są poszczególne części

## Contact Form

```html
    <div class="part" id="contact">
      <h1 class="center">Contact</h1>
      <div class="contact">
        <div class="center">
          <img class="img-mail" src="images/img2.jpg" alt="mail"/>
        </div>
        <div>
          <form class="contact-form">
            <div>
              <label>Name</label>
            </div>
            <div>
              <input type="Text" name="name"/>
            </div>
            <div>
              <label>Email</label>
            </div>
            <div>
              <input type="Email" name="email">
            </div>
            <div>
              <label>Message</label>
            </div>
            <div>
              <textarea name="msg"></textarea> 
            </div>
            <div>
              <button>Send</button>
            </div>
          </form>
        </div>
      </div>
    </div>
```

## Footer

```html
<footer>
  <span class="autor">
    Dawid Kapiszka @ 2022
  </span>
  <a href="https://www.twitter.com" target="_blank">
    <img src="images/twitter.png" class="link-img">
  </a>
  <a href="https://www.facebook.com" target="_blank">
    <img src="images/facebook.png" class="link-img">
  </a>
  <a href="https://www.instagram.com" target="_blank">
    <img src="images/instagram.png" class="link-img">
  </a>
</footer>
```

Stopka strony

## Project css

style.css main styles 

```css
html {
    scroll-behavior: smooth;
    background: url('../images/background.jpg') no-repeat;
    background-size: cover;
    background-position: center;
}

nav, footer {
    background-color: black;
    text-align: center;
    padding: 1%;
    position: fixed;
    font-family: monospace;
    z-index: 1;
}

nav {
    top: 0;
    left: 0;
    width: 100%;
}

footer {
    bottom: 0;
    left:  0;
    width: 100%;
    color: white;
    font-size: 25px;
}
```

## Contact form styling

```css
.contact {
    display: flex;
    align-items: center;
    justify-content: center;
}

@media only screen and (max-width:858px)  {
    .contact {
        flex-direction: column;
    }
}

.contact > div {
    min-width: 220px;
}

.center {
    text-align: center;
}

.contact-form {
    padding: 7%;
    min-width: 220px;
}

.contact-form > div {
    margin: 5%;
    text-align: center;
}
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Images

![alt text](images/home.PNG)