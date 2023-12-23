<template>
  <div id="cont" style="color:white; width: 100vw; margin: auto; padding: 20px; overflow: hidden;">

    <p>
      Welcome to the ArcaneJam! This is your opportunity to push the boundaries of gaming!
    </p>
    <AHeader text="About" />
    <p>
      Here is the basic idea, you have a phone that will be the controller and a PC that is the viewer.
      The phone could be anything, a lantern, a key, a gun, a baseball bat, a driving wheel, an airplane control, a
      classic gamepad, basically is a link between the player and the videogame.
    </p>

    <div style="text-align: center;">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/OpaYoftORnE?si=GuGGR1yAAJ93tZjc"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen></iframe>
    </div>

    <AHeader text="Motivation & What is Arcanepad?" />

    <p>
      Arcanepad is a Software Development Kit for Unity, Godot and Web that makes life easier when creating
      multi-device apps like the ones for this gamejam, also is a platform that allows to run those games without
      having to install a new desktop and android app for every new game. The motivation for this gamejam is to
      showcase the platform and the SDK libraries. I'v been working for a year on this and I'll keep adding
      features like the hability to sell your games. The great thing is that you can distribute the games in your
      own (example: itch.io) and Arcanepad is open for anyone to add those games manaully and play them without
      the need for an account, opposite to most platforms and consoles where you need to ask permission and fill
      forms even before start developing.
    </p>
    <p>
      I created many examples and mini games, as showcased on the video, so you can get started asap on
      creating awesome games. There is a baseball game, a flying car game, a retro space ship game, and a starter
      template that shows how to use the pointer of our phones, to... paint? shoot? interact? Is your desicion.
    </p>
    <p>
      Also I'll be keen to help you if needed, go to our discord channel, there I will be answering questions on
      the channels: "help", "arcane-dev", "godot", "unity" and "web".
    </p>

    <a href="https://discord.com/invite/6Pr9JBCGXy" target="_blank"
      style="display: grid; width: fit-content; margin: auto;">
      <img src="images/join-discord.png" />
    </a>

    <p>
      The submissions will be featured on the main menu of Arcanepad for a period of time, and will be played
      live at Barcelona CheckPoint Gaming Bar after the ArcaneJam ends. You don't need to assist to this event to
      participate, but you can join us if you are near to have a fun time trying out some of the games.
    </p>

    <p>you can use godot unity or web, there is docs in the [arcanedocs link] there are tutorials for each game
      engine
      you could make a game like sports that use your phone as a baseball bat or a tennis racket, or the phone
      could
      be a gun for a trail shooter game, or the lantern for a exploration game, you could use multiple phones that
      behave as different tools, and they could shift shape to become another tools, or you could just make a
      traditional gamepad layout like the classic nes controller or a modern controller with [the word for the
      joysticks that have omnidirection]&nbsp;</p>
    <p>The games will be played on a presencial event in Barcelona gaming bar the theme is free, you can do whatever
      you
      want, there are no prizes except for having fun and learning something new, and having a cool project for
      your
      portfolio the games will be voted by most creative, mechanics, style, innovative and replayability</p>
    <p>If you won't continue the project after the gamejam,&nbsp;we encourage you to make it open source so in the
      future&nbsp;anyone can take from where you left, but this is totally up to you of course!</p>
    <p>The best games will be featured in the Arcanepad Home.</p>


  </div>
  <svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
    <rect width="100%" height="100%" fill="black" />
    <!-- Random stars -->
    <circle cx="20" cy="30" r="2" fill="white" />
    <circle cx="50" cy="70" r="1" fill="white" />
    <circle cx="100" cy="50" r="1.5" fill="white" />
    <circle cx="150" cy="100" r="2" fill="white" />
    <circle cx="170" cy="150" r="1" fill="white" />
    <!-- Add more circles for more stars -->
  </svg>
</template>

<script setup lang="ts">
import AHeader from 'src/components/AHeader.vue';


</script>

<style scoped>
#cont {
  margin: 5%;
}

img {
  transition: .5s all;
  width: 80%;
  max-width: 600px;
  margin: 20px auto;
}

img:hover {
  scale: 1.1;
}
</style>
