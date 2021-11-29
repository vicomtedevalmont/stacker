<template>
  <div>
    <b-container fluid class="text-center p-0 m-0">
      <Navbar />
      <b-jumbotron
        header="Stacks"
        header-tag="h2"
        fluid
        class="m-0 p-0 p-3"
        header-level="4"
      >
      </b-jumbotron>
    </b-container>
    <b-container>
      <div class="mt-3">
        <b-card-group deck>
          <b-card header="Default" class="text-center">
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </b-card-text>
          </b-card>
          <b-card header="Default" class="text-center">
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </b-card-text>
          </b-card>
          <b-card header="Default" class="text-center">
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </b-card-text>
          </b-card>
        </b-card-group>
      </div>
    </b-container>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "@/utils/vue-imports";
import Navbar from "@/components/Navbar.vue";

@Component({
  name: "Home",
  components: {
    Navbar,
  },
})
export default class Home extends Vue {
  images = [
    ["/img/pwa.png", "/img/pwa.png", "/img/pwa.png"],
    ["/img/pwa.png", "/img/pwa.png"],
  ];
}
</script>
