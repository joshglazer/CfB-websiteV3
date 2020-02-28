<template>
    <div id="featured">
        <h3 class="text-center display-4 py-2" style="font-size: 2.5rem;">Featured Projects</h3>
        <carousel :navigationEnabled="true">
            <slide>
                <img src="images/cfb_project_caro4.jpg" class="d-block w-100 img-fluid" alt="...">
                <div class="content text-center">
                <h3 class="display-4">Know Your Rights Baltimore</h3>
                <p class="d-none d-sm-block">2019 National Day of Civic Hacking - A project launched in the summer of 2019 dedicated to helping the people of Baltimore get eduucated on their civil rights through consumer technology</p>
                <a role="button" class="btn btn-outline-light my-2" target="_blank" href="https://github.com/CodeForBaltimore/KnowYourRightsBaltimore">Learn more</a>
                </div>
            </slide>
            <slide>
                <img src="images/cfb_project_caro5.jpg" class="d-block w-100 img-fluid" alt="...">
                <div class="content text-center">
                    <h3 class="display-4">Jury Instructions</h3>
                    <p class="d-none d-sm-block">A proof of concept app to assist judges/practitioners fill out criminal pattern jury instructions.</p>
                    <a role="button" class="btn btn-outline-light my-2" target="_blank" href="https://github.com/CodeForBaltimore/JuryInstructions">Learn more</a>
                </div>
            </slide>
            <slide>
                <img src="images/cfb_project_caro6.jpg" class="d-block w-100 img-fluid" alt="...">
                <div class="content text-center">
                    <h3 class="display-4">Sync the City</h3>
                    <p class="d-none d-sm-block">Synchronizing efforts for change throughout the city. Mapping tool developed in R using the Leaflet library. See projects tab for status of mapping development.</p>
                    <a role="button" class="btn btn-outline-light my-2" target="_blank" href="https://github.com/syncthecity">Learn more</a>
                </div>
            </slide>
        </carousel>
    </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel'

export default {
    components: {
        Carousel,
        Slide
    }
}
</script>

<style>
.VueCarousel-slide {
  position: relative;
  font-family: Arial;
  font-size: 24px;
  text-align: center;
  min-height: 100px;
}

.label {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>