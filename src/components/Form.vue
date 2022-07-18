<template>
    <form action="" class="w-[50%] px-[180px] flex flex-col justify-center">
        <h1 class="md:text-[30px] font-[700] text-[#101828] md:leading-[36px] mb-[12px]">
            Welcome Back
        </h1>
        <p class="md:text-[16px] font-[400] text-[#667085] md:leading-[36px] mb-[32px]">
            Welcome back! Please enter your details.
        </p>
        <label for="email" class="md:text-[14px] font-[500] text-[#344054] md:leading-[20px] mb-[6px]">Email</label>
        <input id="email" type="email" placeholder="Enter your email" required :class="inputBox">
        <label for="password" class="md:text-[14px] font-[500] text-[#344054] md:leading-[20px] mb-[6px] mt-[20px]">Password</label>
        <input id="password" type="password" placeholder="" required :class="inputBox">
        <div class="flex items-center justify-between py-[24px]">
            <div class="flex gap-x-[8px]">
                <input type="checkbox" id="remember" class="cursor-pointer">
                <label for="remember" class="md:text-[14px] font-[500] text-[#344054] md:leading-[20px]">Remember for 30 days</label>
            </div>
            <p class="md:text-[14px] font-[500] text-[#6941C6] md:leading-[20px] cursor-pointer">Forgot password</p>
        </div>
        <div class="flex flex-col-reverse">
            <button class="text-[#344054] font-500 text-[16px] bg-none rounded-[8px] py-[10px] border-[1px] border-[#D0D5DD] shadow-[0_1px_2px_rgba(16,24,40,0.05)] flex justify-center gap-x-[13px]">
                <img :src=google alt="google" class="h-[24px] aspect-auto">
                Sign in with Google
            </button>
            <button class="text-white font-500 text-[16px] bg-[#7F56D9] rounded-[8px]  py-[10px] sm:mb-[12px] md:mb-[16px]">
                Sign in
            </button>
        </div>
        <div class="flex items-center justify-center pt-[32px] gap-x-[4px]">
            <p class="md:text-[14px] font-[400] text-[#344054] md:leading-[20px]">Don't have an account?</p>
            <p class="md:text-[14px] font-[500] text-[#6941C6] md:leading-[20px] cursor-pointer">SIgn up</p>
        </div>
    </form>
</template>

<script>
import google from "../assets/google.png"

export default {
    name: "Form",
    data() {
        return {
            inputBox : "md:text-[16px] font-[400] text-[#667085] md:leading-[24px] pl-[14px] py-[10px] rounded-[8px] border-[#D0D5DD] border-[1px] shadow-[0_1px_2px_rgba(16,24,40,0.05)]",
            google : google
        }
    }
}
</script>