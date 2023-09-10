<template>
    <nav>
        <div>
            <h2>Web Developer</h2>
        </div>
        <!-- MEGA MENU -->
        <MegaMenu />
        <!-- MEGA MENU END -->
        <!-- MOBILE MENU -->
        <MobileMenu />
        <!-- MOBILE MENU END -->
    </nav>
</template>

<script>
import MegaMenu from './NavigationMenu/MegaMenu.vue';
import MobileMenu from './NavigationMenu/MobileMenu.vue';

export default {
    name: "NavComponent",
    components: {
        MegaMenu,
        MobileMenu
    }
}
</script>