---
layout: blog
title: Battle Caster
description: UI Design / Branding
card_size: medium
cover_image: "/assets/images/bc_thumbnail.png"
post_image: "/assets/images/bc_hero.png"
context_work: Client Work
context_date: Jan 2020 – Jun 2020
contribution:
- item: Interface Design
- item: User Experience
- item: Asset Creation
collaborators: Derek Liu, Lily Liu
project_link: ''
collaborator: []

---
### Group 6

While working for Flux Studio  at Oregon State University, a client approached my team got about redesigning the app interface of a new mobile card game. Battle Casters is a PVP digital trading card game in which players control a single character’s stats, movement, and attacks through the various cards they control.

<style>

.glide ul {

max-width: initial;

}

.glide img {

pointer-events: none;

}

.glide__slides {

padding-left: 0;

}

.glide .glide__slide {

opacity: 1; transform: scale(1);

}

</style>

<div class="glide mt4">

<div class="glide__track" data-glide-el="track">

<ul class="glide__slides">

<li class="glide__slide" style="text-align: left;"> <img src="/assets/images/bc_slider2.png" alt="second draft">

<small>The featured image showcases the in-game screen. This project focuses on redesigning the hud assets of the game.</small>

</li>

<li class="glide__slide" style="text-align: left;"> <img src="/assets/images/bc_slider1.png" alt="first draft">

<small>This artwork was created for the mobile home screen and was given to us by the client. </small>

</li>

</ul>

</div>

<small style="text-align: center; color: var(--ink-6); font-weight: 600; display: block;">drag, swipe or use arrow keys</small>

</div>

### Wireframes

At the start of the project, they showed our team the current prototype game. However they made it clear that all of the current assets besides the logo were placeholders and gave us free rein to create a new look and systems.

![](/assets/images/bc_wireframes.png)

### Interface

For the new look, we kept the texture paper background. To make the most of the screen and maximize the amount of battlefield a player can see at any given time, we made elements transparent and pushed them off-screen when not active. We positioned these interactive elements at the bottom of the screen to make it easier to hit with one’s fingers.

{% include caption.html sideBySide=true url="/assets/images/bc_phone1.png" title="Mobile Home Screen" description="We decided to explore the usage of the ribbon from our wireframes, building assets to match the style and sharpness of the angles." %}

{% include caption.html sideBySide=true url="/assets/images/bc_friendslist.png" title="Friends List" description="Friends that are online appear darker, while those that are offline will appear faded." %}

{% include caption.html sideBySide=true url="/assets/images/bc_options.png" title="Play Options" description="The options screen utilizes the same banner design as the previous screens." %}

{% include caption.html sideBySide=true url="/assets/images/bc_phone3.png" title="Queue Match" description="After pressing the Start Battle button, the interface takes the player to this screen. The player has the option to challenge other online players, train their strategic skills, or walk through a tutorial." %}

{% include caption.html sideBySide=true url="/assets/images/bc_phone4.png" title="Mobile In-Game" description="The buttons and other hud assets utilize diamond shapes, the profile icons action button and count down timer as well." %}

{% include caption.html sideBySide=true url="/assets/images/bc_phone6.png" title="In-Game Drop-Down" description="The ribbon drops down and inverts the direction of the arrow." %}

We used transparency and light to make the interface look more open and indicate information. To make sure that text would still be readable even on a light background we used subtle drop shadows and a slight blur effect along with a generous text-shadow.

## Card Redesign

While not in the initial brief, the design team felt that the current card design did not match the new UI assets and was not very legible when shrunk down to fit a mobile phone screen.

<figure> <img src="/assets/images/bcCards.png" alt="card redesign"> </figure>

Some of the biggest changes were cleaning up the card shape and remove the textured background. To make the text more legible, we increased the font size and removed unnecessary elements such as flavor text and artist description. Instead, those elements were moved to the deck builder page. The team also moved the damage amount to the upper left to increase visibility.

{% include caption.html sideBySide=false url="/assets/images/bc_cardInfo.png" title="Card Details" description="We removed the flavor text and artist credit from the card and displayed it in the deck builder." %}

{% include caption.html sideBySide=true url="/assets/images/bcDeckBuilder1.png" title="Mobile Deck Builder Draft 1" description="" %}

{% include caption.html sideBySide=true url="/assets/images/bcDeckBuilder2.png" title="Mobile Deck Builder Draft 2" description="" %}

## Symbols

The last component of the card we changed was the element symbols. The original symbols were more artistry rendered but did not scale well when smaller than 32px. Therefore a team member came up with a simpler flatter, more scalable symbol.

{:.nameofclass}

![](/assets/images/bc_iconsize.png)![](/assets/images/bc_symbols-1.png)

## Development

After the contract with our client ended, they took the design assets we created and implemented them into their game. While the client liked what we created, they modified our designs into their game. **The following screens were not created by the design team, and is currently in development by Group 6.**

{% include caption.html sideBySide=true url="/assets/images/bcStore.png" title="Desktop Store" description="" %}

{% include caption.html sideBySide=true url="/assets/images/bcDesktopDeckBuilder.png" title="Desktop Deck Builder" description="" %}

{% include caption.html sideBySide=true url="/assets/images/bcDesktopInGame.png" title="Desktop In-Game" description="The cards in the player's hand are displayed in a different style, the interface buttons are simplified, and different health bars are being used." %}

{% include caption.html sideBySide=true url="/assets/images/bcMobileInGame.png" title="Mobile In-Game" description="On mobile screens, our card designs make it easier for the player to quickly read the card description, and see the damage counter in the top left corner of each card." %}