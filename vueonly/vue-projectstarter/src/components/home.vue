<template>
    <div class="home">
        <header>
            <h1>Welcome to Freelancer Website</h1>
            <p>Your one-stop solution for freelance services</p>
        </header>
        <section class="services">
            <h2>Our Services</h2>
            <ul>
                <li>Web Development</li>
                <li>Graphic Design</li>
                <li>Content Writing</li>
                <li>SEO Optimization</li>
            </ul>
        </section>
        <section class="about">
            <h2>About Us</h2>
            <p>We connect freelancers with clients to provide top-notch services.</p>
        </section>
        <section class="contact">
            <h2>Contact Us</h2>
            <p>Email: contact@freelancerwebsite.com</p>
            <p>Phone: +123 456 7890</p>
        </section>
    </div>
</template>

<script>
export default {
    name: 'Home'
}
</script>

<style scoped>
.home {
    text-align: center;
    padding: 20px;
}

header {
    background-color: #f8f9fa;
    padding: 20px;
    border-bottom: 1px solid #dee2e6;
}

.services, .about, .contact {
    margin: 20px 0;
}

h1, h2 {
    color: #343a40;
}

p {
    color: #6c757d;
}
</style>