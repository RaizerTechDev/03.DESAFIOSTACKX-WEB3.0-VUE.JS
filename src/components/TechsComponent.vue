<template>
  <section class="w-full h-40 bg-[#27272A] rounded-2xl border-2  border-solid border-brown">
   <ul class="list-disc text-white-400 h-full flex flex-col justify-center items-center flex-wrap">
       <li 
         class="mb-1 w-[10rem]"
         v-for="tech in techs" :key="tech"
       >
         {{tech}}
       </li>
     </ul>
   </section>
</template>

<script>
export default {
 name: 'TechsComponent',
 data() {
   return {
     techs: [
         'HTML',
         'React',
         'Angular',
         'VueJs',
         'Tailwind CSS', 
         'Styled Components', 
         'SASS',
         'Node',
         'TypeScript',
         'Java',  
         'SpringBoot',         
         'JavaScript', 
         'Firebird',
         'MYSql',
         'PostgreSQL',
         'MongoDB',    
         'Python',
         'Django',
         'Sqlite',
         'Tableau',   
       ]
   }
 }
}
</script>

<style>
#app {
  text-transform: capitalize;  
  text-shadow: 15px 5px 5px rgba(190, 72, 8, 0.933); 
  filter: brightness(1.3);
  cursor: pointer; 
} 
</style>

