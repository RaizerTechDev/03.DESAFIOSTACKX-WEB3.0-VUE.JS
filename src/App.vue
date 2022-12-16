<template>
  <HeaderComponent/>

  <main class="h-screen w-[50rem] mx-auto pt-28 pb-4 flex flex-col justify-between items-center">
    <article>
      <HelloI18n/>
      <TechsComponent/>
    </article>

    <LocaleSwitcher/>
  </main>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import HelloI18n from './components/HelloI18n.vue'
import TechsComponent from './components/TechsComponent.vue'
import LocaleSwitcher from './components/LocaleSwitcher.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    HelloI18n,
    TechsComponent,
    LocaleSwitcher
  }
}
</script>


