<template>
  <svg id="parentSvg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
       viewBox="0 0 103 117" shape-rendering="geometricPrecision" text-rendering="geometricPrecision">
    <defs>
      <clipPath id="e2wxnmzqyooc2">
        <circle id="e2wxnmzqyooc3" r="44" transform="matrix(1 0 0 1 52.59000000000000 46.97000000000000)" fill="none"
                stroke="none" stroke-width="1"/>
      </clipPath>
    </defs>
    <g id="e2wxnmzqyooc21" clip-path="url(#e2wxnmzqyooc2)">
      <g id="animatedElement" transform="translate(0,0)">
        <path id="e2wxnmzqyooc22"
              d="M48.280000,91L56.610000,91C75.870000,89.560000,82,79.720000,82,79.720000L82,25L22,25L22,79C29.159702,85.843839,38.419066,90.071859,48.280000,91Z"
              transform="translate(0,0)" fill="rgb(255,211,129)" stroke="none" stroke-width="1"/>
      </g>
    </g>
    <path id="e2wxnmzqyooc23"
          d="M52,93.130000C26.594902,93.130000,6,72.535098,6,47.130000C6,21.724902,26.594902,1.130000,52,1.130000C77.405098,1.130000,98,21.724902,98,47.130000C97.966945,72.521394,77.391394,93.096945,52,93.130000ZM52,5.130000C28.804041,5.130000,10,23.934041,10,47.130000C10,70.325959,28.804041,89.130000,52,89.130000C75.195959,89.130000,94,70.325959,94,47.130000C94,23.934041,75.195959,5.130000,52,5.130000Z"
          fill="rgb(0,0,0)" stroke="none" stroke-width="1"/>
  </svg>
</template>

<script>
export default {
  name: "HelloWorld"
}
</script>

<style scoped>
#parentSvg {
  pointer-events: all;
  width: 100px;
}

#parentSvg:hover #animatedElement {
  animation: e2 3000ms linear 1 normal forwards;
}

@keyframes e2 {
  0% {
    transform: translate(0px, 68px)
  }
  33% {
    transform: translate(0px, 0px)
  }
  100% {
    transform: translate(0px, 0px)
  }
}

</style>