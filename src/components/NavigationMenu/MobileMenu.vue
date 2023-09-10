<template>
    <!-- MOBILE MENU -->
    <div class="mobile-menu-wrapper">
        <label for="toggle">&#9776;</label>
        <input type="checkbox" name="toggle" id="toggle">
        <ul class="mobile-menu">
            <li><a href="#">Home</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#work">Experience</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
    <!-- MOBILE MENU END -->
</template>

<script>
export default {
    name: "MobileMenu"
}
</script>