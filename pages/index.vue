<template>
  <div class="container">
    <nav class="navbar w-full">
      <div class="container px-12 py-8">
        <div class="flex justify-between items-center">
          <div class="logo">
            <h6 class="text-white">RK DEV</h6>
          </div>

          <div class="nav-items text-white h-full">
            <ul class="list-none flex items-center justify-around">
              <li>Home</li>
              <li class="ml-12">Projects</li>
              <li class="ml-12">About</li>
              <li class="ml-12">Resume</li>
            </ul>
          </div>
        </div>
      </div>
    </nav>

    <div class="grid grid-cols-auto place-items-center items-center h-96">
      <div>
        <h1 class="text-white text-6xl font-bold ">I'm, 
          <span class="text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600 leading-10">Rafi Khoirulloh</span> as 
          <br /> <span class="text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600 leading-10">Full Stack Developer</span>
        </h1>

        
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'IndexPage',
}
</script>
