<template>
  <div class="absolute top-0 left-0 w-screen flex flex-col">
    <!-- landing screen -->
    <div class="relative w-full h-screen flex flex-col justify-center items-center">
      <!-- ABSOLUTE top nav -->
      <div
        class="absolute w-full top-0 left-0 flex justify-between items-center px-10 py-6"
      >
        <div>logo</div>
        <div class="flex text-lg font-bold">
          <div class="nav-button">experience</div>
          <div class="nav-button">experience</div>
          <div class="nav-button">experience</div>
          <div class="nav-button">experience</div>
        </div>
      </div>

      <!-- center text -->
      <div class="text-3xl">hi how are you</div>

      <!-- ABSOLUTE click to see more -->
      <div class="absolute bottom-0 flex flex-col justify-start items-center">
        <div>EXPLORE</div>
        <div>BLABLABLA</div>
        <div class="w-8">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 150 176"
            width="100%"
            preserveAspectRatio="xMidYMid meet"
            style="
              width: 100%;
              height: 100%;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <defs>
              <clipPath id="__lottie_element_3">
                <rect width="150" height="176" x="0" y="0"></rect>
              </clipPath>
            </defs>
            <g clip-path="url(#__lottie_element_3)">
              <g
                transform="matrix(1,0,0,1,974.0009765625,541.193603515625)"
                opacity="1"
                style="display: block"
              >
                <g opacity="1" transform="matrix(1,0,0,1,0,0)">
                  <path
                    fill="rgb(51,51,51)"
                    fill-opacity="1"
                    d=" M-944.4180297851562,-492 C-944.4180297851562,-492 -853.5859985351562,-492 -853.5859985351562,-492 C-849.2109985351562,-492 -847.7540283203125,-489.0820007324219 -850.0430297851562,-485.5429992675781 C-850.0430297851562,-485.5429992675781 -895.4569702148438,-419.0820007324219 -895.4569702148438,-419.0820007324219 C-896.1640014648438,-417.8479919433594 -897.4769897460938,-417.08599853515625 -898.89501953125,-417.08599853515625 C-900.3170166015625,-417.08599853515625 -901.6290283203125,-417.8479919433594 -902.3319702148438,-419.0820007324219 C-902.3319702148438,-419.0820007324219 -947.9569702148438,-485.5429992675781 -947.9569702148438,-485.5429992675781 C-950.25,-489.0820007324219 -948.7930297851562,-492 -944.4180297851562,-492 C-944.4180297851562,-492 -944.4180297851562,-492 -944.4180297851562,-492z"
                  ></path>
                </g>
              </g>
            </g>
          </svg>
        </div>
      </div>
    </div>

    <!-- next thing -->
    <div class="h-24">helloblablabla</div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import "./assets/css/tailwind.css";

export default {
  name: "app",
};
</script>

<style lang="postcss">
#app {
  font-family: "-apple-system", "BlinkMacSystemFont", "Segoe UI", "Helvetica";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.nav-button {
  @apply m-3 cursor-pointer;
}
</style>
