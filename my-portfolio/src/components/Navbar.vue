<template>
    <div class="nav-bar w-full bg-slate-400">
        This is the navbar
        <ul class="flex gap-8 justify-center px-8">
            <li class="logo">
                Logo
            </li>
            <li>
                <RouterLink to='/about'> About</RouterLink>
            </li>
            <li>
                <RouterLink to='/other'> Other</RouterLink>
            </li>
            
        </ul>
    </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {

  }
}
</script>