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

<li class="glide__slide" style="text-align: left;"> <img src="/assets/images/bc_slider1.png" alt="first draft">

<small>Artwork given to us from our client. The artwork was created for the mobile home screen.</small>

</li>

<li class="glide__slide" style="text-align: left;"> <img src="/assets/images/bc_slider2.png" alt="second draft">

<small>Old design of the in-game desktop screen.</small>

</li>

<li class="glide__slide" style="text-align: left;"> <img src="/assets/images/bc_slider3.png" alt="third draft">

<small>Old magic scroll design.</small>

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

{% include caption.html sideBySide=true url="/assets/images/bc_phone1.png" title="Mobile Home Screen" description="Mobile main menu. We decided to explore the usage of the ribbon from our wireframes, building assets to match the style and sharpness of the angles." %}

{% include caption.html sideBySide=true url="/assets/images/bc_friendslist.png" title="Friends List" description="Mobile friends list. Friends that are online appear darker, while those that are offline will appear faded." %}

{% include caption.html sideBySide=true url="/assets/images/bc_options.png" title="Play Options" description="Mobile options. The options screen utilizes the same banner design as the previous screens." %}

{% include caption.html sideBySide=true url="/assets/images/bc_phone3.png" title="Queue Match" description="Mobile queue match. After pressing the Start Battle button, the interface takes the player to this screen. The player has the option to challenge other online players, train their strategic skills, or walk through a tutorial." %}

{% include caption.html sideBySide=true url="/assets/images/bc_phone4.png" title="Mobile In-Game" description="Mobile in-game. The buttons and other hud assets utilize diamond shapes, the profile icons action button and count down timer as well." %}

{% include caption.html sideBySide=true url="/assets/images/bc_phone6.png" title="In-Game Drop-Down" description="Mobile in-game drop-down. The ribbon drops down and inverts the direction of the arrow." %}

We used transparency and light to make the interface look more open and indicate information. To make sure that text would still be readable even on a light background we used subtle drop shadows and a slight blur effect along with a generous text-shadow.

## Cards

While not in the initial brief, the design team felt that the current card design did not match the new UI assets and was not very legible when shrunk down to fit a mobile phone screen.

<figure> <img src="/assets/images/bcCards.png" alt="card redesign"> </figure>

<small>**↑ Card redesign.**</small>

<small>_We simplified the card design by shortening the card description, removing the flavor text and artist credit. The important information was relocated at the top left corner._</small>

Some of the biggest changes were cleaning up the card shape and remove the textured background. To make the text more legible, we also bumped up the font size and removed unnecessary elements such as flavor text and artist description. Instead, those elements moved to the deck builder page. The team also moved the damage amount to the upper left to increase visibility.

![](/assets/images/bc_cardinfo.png)

<small>**↑ Card details**</small>

<small>We removed the flavor text and artist credit from the card and displayed it in the deck builder.</small>

<figure class="flexImages">

<div> <img src="/assets/images/bc_deckbuilder1.png" alt="deck builder 1"> <small>↑ Deck builder draft 1</small>

</div>

<div> <img src="/assets/images/bc_deckbuilder2.png" alt="deck builder 2"> <small>↑ Deck builder draft 2</small>

</div>

</figure>

## Symbols

The last component of the card we changed was the element symbols. The original symbols were more artistry rendered but did not scale well when smaller than 32px. Therefore a team member came up with a simpler flatter, more scalable symbol.

![](/assets/images/bc_iconsize.png)![](/assets/images/bc_symbols-1.png)

## Development

After the contract with our client ended, they took the design assets we created and implemented them into their game. While Group 6 liked what we created, they adjusted the assets to their own liking.

<figure class="flexImages">

<div> <img src="/assets/images/bc_store.png" alt="desktop store"> <small>↑ Desktop store view</small>

</div>

<div> <img src="/assets/images/bc_deckbuilder.png" alt="desktop deck builder"> <small>↑ Desktop deck builder</small>

</div>

</figure>

<figure class="flexImages">

<div> <img src="/assets/images/bc_desktopingame.png" alt="onboarding screens"> <small>↑ In-game desktop view</small>

</div>

<div> <img src="/assets/images/bc_devphone.png" alt="onboarding screens"> <small>↑ In-game mobile view</small>

</div>

</figure>