<script setup>
const links = [
    {
        name: 'Home',
        url: '#home'
    },
    {
        name: 'About',
        url: '#about'
    },
    {
        name: 'Portfolio',
        url: '#portfolio'
    },
    {
        name: 'Contact Me',
        url: '#contact'
    }
]

</script>

<template>
    <nav class="flex justify-between items-center md:mx-10 mx-2 px-5 py-4">
            <div class="logo">
                <ul>
                    <li class="web-name font-extrabold font-Poppins text-3xl text-palette-300 animate hid-left tracking-widest"> n<span>iko</span>j<span>an</span>. </li>
                </ul>
            </div>
    
            <!--MOBILE MENU-->
            <div class="mobile-btn md:hidden" id="mobile-btn">
                <div class="bar">
                </div>
            </div>

            <div class="nav-links hidden md:block">
                <ul class="flex gap-x-8">
                    <li v-for="link in links" class="font-semibold my-2 animate hid-left">
                        <a :href="link.url">{{link.name}}</a>
                    </li>
                </ul>
            </div>
        </nav>
</template>