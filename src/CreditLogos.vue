<template>
  <div id="logo-credits">
    <div id="icons-container">
      <a href="https://www.cosmicds.cfa.harvard.edu/" target="_blank" rel="noopener noreferrer"
        ><img alt="CosmicDS Logo" src="https://cosmicds.github.io/cds-website/logos/cosmicds_logo_for_dark_backgrounds.png"
      /></a>
      <a href="https://worldwidetelescope.org/home/" target="_blank" rel="noopener noreferrer"
        ><img alt="WWT Logo" src="https://cosmicds.github.io/cds-website/logos/logo_wwt.png"
      /></a>
      <a href="https://science.nasa.gov/learners" target="_blank" rel="noopener noreferrer" class="pl-1"
        ><img alt="SciAct Logo" src="https://cosmicds.github.io/cds-website/logos/logo_sciact.png"
      /></a>
    </div>
  </div>
</template>


<script lang="ts">
import { defineComponent, } from "vue";

export default defineComponent({


  props: {
    visible: {
      type: Boolean,
      default: true
    },
  },

  data() {
    return {    };
  },

  created() {
    return;
  },

  methods: {
    
  },

  computed: { 

    isMobile() {
      return (/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent));
    },
  },

  watch: {
  }
});
</script>
