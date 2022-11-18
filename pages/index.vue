<template>
  <div>
    <section class="hero">
      <img src="~/assets/logo.svg" alt="logo">
      <p>Plongez vous dans le nouvel escape game. Combattez une intelligence artificielle malefique et resolvez ses enigmes les plus complexes pour liberer l’ecole des entraves de cette IA.</p>
      <TheButton text="commencer" 
                link="/game" 
      />
    </section>
    <section class="findMore">
      <div class="findMore-header">
        <h3>Découvrez les pôles de l’IIM</h3>
        <p>Chaque axe s’est fait attaquee par l’intellegience artificielle malefique. Apprenez a les decouvrir avant d’aider les etudiants de chaque pole.</p>
      </div>
      <div class="findMore-cards">
        <TheCard />
        <TheCard />
        <TheCard />
        <TheCard />
        <TheCard />
      </div>
    </section>
    <section class="discover">
      <div class="discover-content">
        <h3>Découvrez l’IASCAPE avant de commencer</h3>
        <p>Apprenez a connaitre Medusa, l’intelligence artificielle malefique pour dejouer ses tours et vous preparer a l’escape game.</p>
        <TheButton text="découvrir" link="/game/introduction" />
      </div>
      <div></div>
    </section>
    <section class="enigmes">
      <div class="enigmes-header">
        <h3>Parcourez les enigmes</h3>
        <p>Decouvrez les enigmes d’IIMSCAPE a travers chaque axes et decouvrez quelques astuces</p>
      </div>
      <div class="enigmes-cards">
        <TheCard />
        <TheCard />
        <TheCard />
        <TheCard />
      </div>
    </section>
    <section class="medusa">
      <div class="medusa-content">
        <h3>Medusa, l’intelligence artificielle malefique</h3>
        <p>Apprenez a connaitre Medusa, l’intelligence artificielle malefique pour dejouer ses tours et vous preparer a l’escape game.</p>
        <TheButton text="commencer" link="/game/introduction" />
      </div>
    </section>
    <section class="video">
      <div class="video-border">
        <div class="video-content"></div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
    name: "IndexPage",
    layout: "default",
}
</script>
