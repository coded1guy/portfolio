<script setup lang="ts">
import { ref } from "vue";
import MobileNavIcon from "./svgs/MobileNavIcon.vue";

const showDropDown = ref(false);

const toggleDropDown = () => {
  showDropDown.value = !showDropDown.value;
};
</script>

<template>
  <nav>
    <span class="logo">
      <a href="/"> &lt;emmo&gt; </a>
    </span>
    <div class="nav-cnt">
      <button id="menu" @click="toggleDropDown">
        <MobileNavIcon :is-open="showDropDown" />
      </button>
      <ul class="nav-links" :class="[showDropDown ? 'show-links' : '']">
        <li>
          <a href="#about" class="active">About</a>
        </li>
        <li>
          <a href="#experience">Experience</a>
        </li>
        <li>
          <a href="#projects">Projects</a>
        </li>
        <li>
          <a href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
@import "../assets/css/navbar.css";
</style>
