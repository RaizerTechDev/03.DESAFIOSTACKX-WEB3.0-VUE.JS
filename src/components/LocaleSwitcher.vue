<template>
    <nav class="mx-auto flex">
        <button 
          @click="$i18n.locale = locales[0]"
          class="transition-all hover:brightness-90 mr-4 box-border w-32 h-12 bg-[#27272A] flex items-center justify-center rounded-2xl text-white-900 border-2  border-solid border-brown"
        >
            <img class="mr-1" src="@/assets/icons/brazil.svg" alt=""/>
            Português
        </button>

        <button 
          @click="$i18n.locale = locales[1]"
          class="transition-all hover:brightness-90 mr-4 box-border w-32 h-12 bg-[#27272A] flex items-center justify-center rounded-2xl text-white-900 border-2  border-solid border-brown "
        >
            <img class="mr-1" src="@/assets/icons/english.svg" alt=""/>
            Inglês
        </button>

        <button 
          @click="$i18n.locale = locales[2]"
          class="transition-all hover:brightness-90 mr-4 box-border w-32 h-12 bg-[#27272A] flex items-center justify-center rounded-2xl text-white-900 border-2  border-solid border-brown"
        >
            <img class="mr-1" src="@/assets/icons/spanish.svg" alt=""/>
            Espanhol
        </button>
    </nav>
</template>

<script>
    export default {
        name: 'LocaleSwitcher',
        data() {
            return {
                locales: ["pt", "en", "es"],
            }
        }
    }
</script>