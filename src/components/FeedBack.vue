<template>
    <div class="md:py-[96px] sm:py-[64px] md:px-[64px] sm:px-[16px] text-center">
        <h2 class="md:text-[30px] sm:text-[30px] font-[500] text-[#101828] sm:px-[16px] md:leading-[38px] sm:leading-[30px]">
            We’ve been using Untitled to kick start every new project and can’t imagine working without it.
        </h2>
        <div class="flex flex-col items-center mt-[32px]">
            <img :src=maggi alt="avatar" class="w-[64px] h-[64px] rounded-full" />
            <h2 class="text-[18px] font-[500] text-[#101828] sm:px-[16px] leading-[24px] md:mt-[16px] text-center">Kelly Williams</h2>
            <h2 class="text-[16px] font-[400] text-[#667085] sm:px-[16px] leading-[24px] md:mt-[4px] text-center">Head of Design, Layers</h2>
        </div>
        <div class="flex justify-center gap-x-[16px] mt-[39.5px]">
            <div class="w-[10px] aspect-square rounded-full bg-[#6941C6]"></div>
            <div class="w-[10px] aspect-square rounded-full bg-[#F2F4F7]"></div>
            <div class="w-[10px] aspect-square rounded-full bg-[#F2F4F7]"></div>
        </div>
    </div>
</template>

<script>
import maggi from "../assets/maggi.jpg"

export default {
  name: 'Feedback',
  data() {
    return {
        maggi: maggi
    }
  }
}

</script>

