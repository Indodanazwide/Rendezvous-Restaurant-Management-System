<template>
    <div class="about">
        <!-- Banner -->
        <header>
            <h1>About</h1>
        </header>

        <main class="content">
            <section class="introduction">
                <p>
                    Welcome to <strong>Rendezvous Restaurant</strong>, where culinary excellence meets innovation. Nestled within the vibrant Steve Biko Campus at Durban University of Technology (DUT), Rendezvous was born from a shared passion for great food, sustainability, and student empowerment. Our story is as much about serving delicious meals as it is about fostering a space for creativity, education, and community engagement.
                </p>
            </section>

            <section class="body">
                <article class="text">
                    <h2>Our Journey</h2>

                    <p>Established as a student-run restaurant by the Department of Food and Nutrition Consumer Sciences, Rendezvous began as a practical training ground for aspiring chefs and food experts. Over the years, it has evolved into a cornerstone of the campus dining experience, offering a wide range of meals carefully crafted by students and overseen by experienced faculty.</p>
                    
                    <p>
                        In 2024, we embraced a new chapter through a rebranding effort that reflects our commitment to sustainability and modern dining experiences. We introduced eco-friendly packaging and expanded our offerings to include Home Meal Replacements (HMR), perfectly suited for today’s fast-paced lifestyle. This rebranding is not just about new menus and packaging but about aligning with DUT's ENVISION 2030 strategy, which aims to foster financial sustainability and innovation.
                    </p>
                </article>


                <article class="vision">
                    <div class="media"></div>
                    <div class="text">
                        <h3>Our Vision</h3>

                        <p>
                            At Rendezvous, we believe in delivering more than just food. Our mission is to provide wholesome, high-quality meals that nourish both body and soul. We are deeply committed to environmental responsibility and continuously strive to reduce our ecological footprint by incorporating sustainable practices into everything we do—from sourcing ingredients to minimizing food waste.
                        </p>
                    </div>
                </article>

                <article class="what-we-offer">
                    <h2>What We Offer</h2>

                    <p>
                        Rendezvous Restaurant is proud to serve the university community and beyond with diverse menu options that cater to a wide range of dietary preferences. Whether you're in the mood for hearty meals, vegan delights, or convenient takeaways, we’ve got something for everyone. Our <strong>Meals on the Go</strong> concept ensures that you can enjoy nutritious, ready-to-eat meals wherever you are, whether on or off campus.
                    </p>

                    <p>
                        Our menu is carefully designed to rotate on a four-week cycle, offering a variety of seasonal dishes that highlight fresh, local ingredients. With meals prepared by students, each dish reflects the creativity, skill, and care of future culinary professionals.
                    </p>
                </article>

                <article class="gallery">
                    <h2>Gallery</h2>

                    <div>
                        <div class="image img1"></div>
                        <div class="image img2"></div>
                        <div class="image img3"></div>
                    </div>
                </article>

                <article class="empowerment">
                    <h2>A Commitment to Student Empowerment</h2>

                    <p>
                        Rendezvous is more than just a restaurant—it's a training ground for the next generation of food industry leaders. We provide real-world experience for students, equipping them with the skills they need to succeed in the fast-paced world of food and nutrition. By dining with us, you’re not only enjoying great food; you’re supporting the education and future careers of DUT’s talented students.
                    </p>

                    <p>
                        The Meals on the Go initiative, managed by our alumna Lihle Nhlebela through the YES Programme, is an extension of our commitment to growth, sustainability, and innovation. This project not only generates third-stream income for the department but also serves as a platform for students to showcase their talents beyond the classroom.
                    </p>
                </article>

                <article class="join">
                    <h2>Join Us for a Memorable Dining Experience</h2>

                    <p>
                        Operating from 11 AM to 2 PM on Wednesdays and Thursdays in the first semester, and expanding to Fridays in the second semester, Rendezvous offers an inviting atmosphere where students, faculty, and visitors can relax, enjoy freshly prepared meals, and support student learning. Whether you’re here for a quick takeaway or a sit-down meal, we aim to make every visit a memorable one.
                    </p>

                    <p>
                        At Rendezvous, we are constantly evolving, but one thing remains the same: our dedication to serving delicious, sustainable food and empowering the next generation of food professionals.
                    </p>
                </article>
            </section>

            <section class="conclusion">
                <p style="text-align: center;"><mark>Thank you for being part of our story. We look forward to welcoming you!</mark></p>
            </section>
        </main>
    </div>
</template>

<style>
.about {
    padding: 12vh 0;
}

header {
  height: 20vh;
  width: 100%;
  background-color: #0F152C;
  color: #b2a43b;
  text-align: center;
  padding-block: 1.5rem;
}

.content {
    padding: 0 2rem;
}

.vision {
    display: flex;
    justify-content: center;
    align-items: center;
}

.vision div {
    width: 30%;
    margin: 2rem 4rem;
}

.content h2 {
    margin-top: 3rem;
}

.media {
    background-image: url('@/assets/images/jpg/door.jpg');
}

.gallery {
    margin-block: 5rem;
}

.gallery div {
    display: flex;
    justify-content: center;
    align-items: center;
}

.image {
    display: inline-block;
    overflow: hidden;
    width: 300px;
    height: 200px;
    background-size: cover;
    background-repeat: no-repeat;
    transition: transform 0.3s ease;
}

.img1 {
    background-image: url('@/assets/images/jpg/desert.webp');
    transition: .5s;
}

.img2 {
    background-image: url('@/assets/images/jpg/scones.webp');
    transition: .5s;
}

.img3 {
    background-image: url('@/assets/images/jpg/tradition.jpg');
    transition: .5s;
}

.image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.6s ease, filter 0.6s ease;
}

.image:hover {
    transform: scale(1.1);
    filter: brightness(80%);
    margin-inline: .2rem;
    box-shadow: 1rem 1rem 1rem .5rem rgba(0, 0, 0, 0.2); 
}

.img1:hover {
    background-image: url('@/assets/images/jpg/baked.webp');
}

.img2:hover {
    background-image: url('@/assets/images/jpg/prepared.webp');
}

.img3:hover {
    background-image: url('@/assets/images/jpg/roti.webp');
}
</style>