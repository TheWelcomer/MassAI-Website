<script lang="ts">
</script>

<section class="bg-gradient-section text-white py-16 sm:px-8 relative overflow-hidden">
  <div class="absolute inset-0 z-0 bg-gradient-to-r from-red-400 via-pink-700 to-red-900 animate-gradient move-gradient"></div>

  <div class="container mx-auto text-center relative z-10">
    <h1 class="font-fraunces font-extrabold text-5xl mb-4">About Us</h1>
    <p class="text-lg max-w-2xl mx-auto">
      We are UMass Amherst's premier student organization for students passionate about machine learning and artificial intelligence. Whether you're interested in learning the fundamentals or eager to work on hands-on projects, this is the place for you! 
    </p>
  </div>

</section>


<style>
  .animate-gradient {
    background-size: 300% 300%;
    animation: gradientAnimation 8s ease infinite;
  }

  @keyframes gradientAnimation {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }
  .move-gradient {
    pointer-events: none;
    transition: transform 0.1s;
  }

  .bg-gradient-section:hover .move-gradient {
    transform: scale(1.1);
  }

  .bg-gradient-section {
    position: relative;
    overflow: hidden;
  }

  /*   .btn { */
  /*   display: inline-block; */
  /*   padding: 10px 20px; */
  /*   font-size: 1rem; */
  /*   color: white; */
  /*   background-color:rgb(142, 2, 2); */
  /*   border: none; */
  /*   border-radius: 5px; */
  /*   text-decoration: none; */
  /*   cursor: pointer; */
  /* } */
  /* .btn:hover { */
  /*   background-color:rgb(79, 9, 2); */
  /* } */
</style>
