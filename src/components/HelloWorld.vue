<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <section id="main">
      <header id="title">
        <h1>Alberto Arturo Zepeda Echavarria</h1>
        <span class="subtitle">Ingeniero en sistemas computacionales</span>
      </header>
      <section class="main-block">
        <h2>
          <i class="fa fa-suitcase"></i> Experiencia
        </h2>
        <section class="blocks">
          <div class="date">
            <span>2015</span><span>present</span>
          </div>
          <div class="decorator">
          </div>
          <div class="details">
            <header>
              <h3>Some Position</h3>
              <span class="place">Some Workplace</span>
              <span class="location">(remote)</span>
            </header>
            <div>
              <ul>
                <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit</li>
                <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin nec mi ante. Etiam odio eros, placerat eu metus id, gravida eleifend odio. Vestibulum dapibus pharetra odio, egestas ullamcorper ipsum congue ac. Maecenas viverra tortor eget convallis vestibulum. Donec pulvinar venenatis est, non sollicitudin metus laoreet sed. Fusce tincidunt felis nec neque aliquet porttitor</li>
              </ul>
              </div>
          </div>
        </section>
        
      </section>
      <section class="main-block concise">
        <h2>
          <i class="fa fa-graduation-cap"></i> Educacion
        </h2>
        <section class="blocks">
          <div class="date">
            <span>2009</span><span>2014</span>
          </div>
          <div class="decorator">
          </div>
          <div class="details">
            <header>
              <h3>Ph.D. in Forty-Two Discovery</h3>
              <span class="place">Inexistent University</span>
              <span class="location">Some City, Some Country</span>
            </header>
            <div>Relationship of the number with the answer to life, the universe and everything</div>
          </div>
        </section>
        
      </section>
    </section>
    <aside id="sidebar">
      <div class="side-block" id="contact">
        <h1>
          Contact Info
        </h1>
        <ul>
          <li><i class="fa fa-globe"></i> <a href="https://arturozepeda.xyz" > arturozepeda.xyz</a></li>
          <li><i class="fa fa-linkedin"></i><a href="https://www.linkedin.com/in/alberto-zepeda-636724149"> linkedin</a></li>
          <li><i class="fa fa-envelope"></i><a href="mailto:aaze92@gmail.com"> aaze92@gmail.com</a></li>
          <li><i class="fa fa-phone"></i>+52 (722)2450955</li>
        </ul>
      </div>
      <div class="side-block" id="skills">
        <h1>
          Skills
        </h1>
        <ul>
          <li>Omnipresence</li>
          <li>Anonymity</li>
        </ul>
        <ul>
          <li>Ordinarity</li>
          <li>No name rights</li>
        </ul>
      </div>
      <div class="side-block" id="disclaimer">
        This r&eacute;sum&eacute; was wholly typeset with HTML/CSS &mdash; see <code>git.io/vVSYL</code>
      </div>
    </aside>
</template>

<style scoped>

</style>
