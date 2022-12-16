<template>
    <header class="w-screen h-[4.5rem] bg-[#27272A] backdrop-blur-sm shadow-sm fixed flex justify-center items-center border-2 border-solid border-brown">
        <div class="px-5 py-2 box-border bg-[#6b7280] rounded-xl hover:brightness-90 cursor-pointer transition-all border-2 border-solid border-brown">
             <img
                class="w-36 h-7"
                src="@/assets/icons/stackx.svg"
                alt="">
        </div>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent'
    }
</script>