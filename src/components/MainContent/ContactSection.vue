<template>
    <article class="contact row" id="contact">
        <header class="row-title">
            <h2>Contact</h2>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat pariatur dicta eius laborum optio quod.
            </p>
        </header>
        <section class="content">
            <div class="left">
                <h3>Contact Info</h3>
                <ul class="contact-data">
                    <li>
                        <i class="fi-xnluxl-envelope"></i>
                        <a href="mailto:yourmail@gmail.com">yourmail@gmail.com</a>
                    </li>
                    <li>
                        <i class="fa-brands fa-linkedin-in"></i>
                        <a href="https://linkedin.com/in/gustavobpf" target="_blank">linkedin.com/in/gustavobpf</a>
                    </li>
                    <li>
                        <i class="fa-brands fa-github"></i>
                        <a href="https://github.com/ac-gbpfreitas" target="_blank">github.com/ac-gbpfreitas</a>
                    </li>
                    <li>
                        <i class="fi-xnsuxl-map-marker-solid"></i>
                        <address>Vancouver, BC</address>
                    </li>
                </ul>
            </div>
            <div class="right">
                <form>
                    <input type="text" name="name" v-model="name" id="name" placeholder="Name">
                    <input type="email" name="email" v-model="email" id="email" placeholder="Email">
                    <input type="text" name="subject" v-model="subject" id="subject" placeholder="Subject">
                    <textarea placeholder="Message" v-model="message" name="message" id="message"></textarea>
                    <input type="submit" value="Send Message" name="btn-submit">
                </form>
            </div>
        </section>
    </article>
</template>

<script>
    export default {
        name: "ContactSection",
        data() {
            return {
                name: "",
                email: "",
                subject: "",
                message: ""
            }
        }
    }
</script>