<template>
    <div class="flex flex-col justify-between h-screen bg-[#F9FAFB] w-[50%]">
        <NavBar />
        <FeedBack />
        <footer class="ml-[32px] mb-[32px]">
            <p class="font-inter font-[400] text-[14px] text-[#667085]">
                © Untitled UI 2077
            </p>
        </footer>
    </div>
</template>

<script>
import NavBar from './NavBar.vue';
import FeedBack from './FeedBack.vue';

export default {
    name: "Accolades",
    components: { NavBar, FeedBack }
}
</script>