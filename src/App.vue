<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>




<body class="font-sans antialiased text-gray-900 leading-normal tracking-wider bg-cover" style="background-image:url('https://source.unsplash.com/1L71sPT5XKc');">



  <div class="max-w-4xl flex items-center h-auto lg:h-screen flex-wrap mx-auto  lg:my-0 ">
    <!--Main Col-->
    <div id="profile" class="w-full lg:w-3/5 rounded-lg lg:rounded-l-lg lg:rounded-r-none shadow-2xl bg-white opacity-100 mx-6 lg:mx-0">

        <div class="p-4 md:p-12 text-center lg:text-left">
            <!-- Image for mobile view-->
            <div><img src="../assets/DD.jpg" class="block lg:hidden rounded-full shadow-xl mx-auto -mt-16 h-48 w-48 bg-cover "></div>

            <h1 class="text-3xl font-bold pt-8 lg:pt-0">Barzun Zakwan</h1>
            <div class="mx-auto lg:mx-0 w-4/5 pt-3 border-b-2 border-emerald-500 opacity-25"></div>
            <p class="pt-3 text-base font-bold flex items-center justify-center lg:justify-start">Student ID: </p>
            <p class="pt-2 text-base font-bold lg:text-sm flex items-center justify-center lg:justify-start">Group Code: DWDT07</p>
            <p class="pt-8 text-sm">I am a student from Politeknik Brunei taking Web Development course. 
            I am currently i my 4th semester of learning and have started doing our final year project. 
            The project is called Market, it is an application that lets users buy, sell or browse certain items.
            </p>
        </div>

    </div>

    <!--Img Col-->
    <div class="w-full lg:w-2/5">
        <img src="../assets/DD.jpg" class="rounded-none lg:rounded-lg shadow-2xl hidden lg:block transform scale-105">
    </div>

</div>


	
	
</body>


  
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
