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
      <iframe style="min-width: 60%;" width="auto" height="315"
        src="https://www.youtube.com/embed/OpaYoftORnE?si=GuGGR1yAAJ93tZjc" title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen></iframe>
    </div>

    <AHeader text="Motivation & What is Arcanepad?" />

    <p>
      <b> Arcanepad </b> is a tool for Unity, Godot and Web that makes life easier when creating
      multi-device apps like the ones for this gamejam, also is a platform that allows to run those games without
      having to install a new desktop and android app for every new game. You can create and
      distribute games that use Arcanepad without an account. You don't need to ask us
      for permission to get a devkit, is our commitment to remain open and dev friendly. Nevertheless, in the future we
      plan to support a way to distribute and sell your apps within Arcanepad.
    </p>

    <AHeader text="How?" />
    <p>
      I created many examples and mini games, as showcased on the video, so you can get started asap on
      creating awesome games. There is a baseball game, a flying car game, a retro space ship game, and a starter
      template that shows how to use the pointer of our phones, to... paint? shoot? interact? Is your desicion.
    </p>

    <p>
      There is a unique tutorial section for Unity, Godot and Web, you can find it on the
      <a href="https://imvenx.github.io/arcanedocs" target="_blank">ArcaneDocs</a>
    </p>


    <p>
      Also I'll be keen to help you if needed, go to our discord channel, there I will be answering questions on
      the channels: "help", "arcane-dev", "godot", "unity" and "web".
    </p>

    <a href="https://discord.com/invite/6Pr9JBCGXy" target="_blank"
      style="display: grid; width: fit-content; margin: auto;">
      <img src="images/join-discord.png" />
    </a>

    <AHeader text="Rules" />

    <ul>
      <li style="list-style: none;">
        <p>&#9670; The game uses at least two different screens to work (Example: A controller and a viewer)</p>
        <p>&#9670; You are allowed to adapt an existing game for this gamejam if you prefer, the work will be on
          the controller part and the change in mechanics and user experience</p>
        <p>&#9670; You are not required to use Arcanepad, if you prefeer you can create the whole networking system in
          your own, altho realistically that may be very challenging for the time of this gamejam, in any case, we
          encourage you to use Arcanepad but feel free to do all on your own if you prefeer</p>
      </li>
    </ul>

    <AHeader text="Grand Finale & Live Gaming" />

    <p>
      The submissions will be featured on the main menu of Arcanepad for a period of time, and will be played
      live at Barcelona CheckPoint Gaming Bar after the ArcaneJam ends. You don't need to assist to this event to
      participate, but you can join us if you are near to have a fun time trying out some of the games.
    </p>

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
