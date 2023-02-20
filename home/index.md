---
title: Dishes That Would Kill Me
coverimage: ../uploads/dishes-that-would-kill-me-book-cover-.png
permalink: /
layout: recipeshome
published: true
date: 2023-01-31T15:39:44.021Z
---
**Welcome to my recipe site, where every dish is lovingly crafted to be the ultimate "Thomas Kryptonite".** 

Yes, you heard that right - this site’s owner, Thomas, is highly allergic to a wide range of ingredients, from sesame seeds to nuts to shellfish, and I’ve made it my mission to create recipes that would put me in a hospital bed faster than you can say "epinephrine injection".

Don’t get it? Ok, never mind.

But don't worry, I’m not a heartless sadist - I’ve also made sure that our recipes are delicious, creative, and easy to follow, so you (at least) can enjoy them without the fear of anaphylaxis. Whether you're in the mood for a juicy burger that uses cauliflower instead of bread, a decadent chocolate cake that's nut-free and dairy-free, or a spicy curry that swaps out tofu for shrimp, I’ve got you covered.

So come on in, take a look around, and don't forget to send some love to the site’s poor, allergy-ridden owner, who can never enjoy these dishes - but will hopefully inspire you to at least give them a try.



<style>

/\* Style for the lightbox overlay \*/

.lightbox {

position: absolute;

top: 0;

left: 0;

width: 100%;

height: 100%;

background-color: #ffcc00;

z-index: 9999;

display: flex;

justify-content: center;

align-items: center;

margin: auto;

width: 100%;

}



/\* Style for the exploding text \*/

.exploding-text {

display: inline-block;

font-family: 'Intro Rust G Base', sans-serif;

font-size: 96px;

font-weight: bold;

color: #880808;

animation: explode 2s forwards;

margin: auto;

width: 85%;



padding: 10px;

}



/\* Keyframe animation for the exploding text \*/

@keyframes explode {

from {

transform: scale(0);

opacity: 0;

}

to {

transform: scale(1);

opacity: 1;

}

}



/\* Style for the fade-out animation \*/

.fade-out {

animation: fade-out 1s forwards;

}



/\* Keyframe animation for the fade-out effect \*/

@keyframes fade-out {

from {

opacity: 1;

}

to {

opacity: 0;

}

}

</style>

</head>

<body>

<div class="lightbox">

<center> <div class="exploding-text">WELCOME TO... <br> DISHES THAT WOULD KILL ME</div></center>

</div>



<script>

setTimeout(function() {

var lightbox = document.querySelector('.lightbox');

lightbox.classList.add('fade-out');

setTimeout(function() {

lightbox.parentNode.removeChild(lightbox);

}, 2000);

}, 5000);

</script>