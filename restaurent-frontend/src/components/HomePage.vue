<template>
    <div class="homepage">
        <!-- Hero -->
        <section class="hero" id="hero">
            <article>
                <h1>Rendezvous</h1>

                <hr class="hero-line" />

                <p>Savor the Moment, Anytime, Anywhere!</p>
            </article>
        </section>

        <!-- Featured menu -->
        <section class="menu" id="">
            <article class="menu-intro">
                <h2>Indulge in Our Signature Creations</h2>
                <p>From classic favorites to innovative twists, our menu has something for everyone.</p>
            </article>

            <hr class="menu-line">

            <article class="menu-category">
                <ul class="opt-menu">
                    <li class="category1">
                        <div class="item">
                            <img src="@/assets/images/jpg/cake.jpg" alt="Tasty Cake">
                        </div>
                        <div class="description">
                            <p><strong>Tasty Treats</strong></p>
                            <p>Delightful desserts perfect for satisfying your sweet tooth.</p>
                        </div>
                    </li>
                    <li class="category2">
                        <div class="item">
                            <img src="@/assets/images/jpg/sandwich.jpg" alt="Sandwich">
                        </div>
                        <div class="description">
                            <p><strong>Sandwiches</strong></p>
                            <p>Freshly made sandwiches with options for chips on the side.</p>
                        </div>
                    </li>
                    <li class="category3">
                        <div class="item">
                            <img src="@/assets/images/jpg/salad.jpg" alt="Salad">
                        </div>
                        <div class="description">
                            <p><strong>Light Meals</strong></p>
                            <p>Quick, flavorful bites ideal for a lighter meal.</p>
                        </div>
                    </li>
                    <li class="category4">
                        <div class="item">
                            <img src="@/assets/images/jpg/golden.jpg" alt="Golden">
                        </div>
                        <div class="description">
                            <p><strong>Main Meals</strong></p>
                            <p>Hearty, gourmet dishes featuring satisfying flavors and ingredients.</p>
                        </div>
                    </li>
                    <li class="category5">
                        <div class="item">
                            <img src="@/assets/images/jpg/drinks.jpg" alt="Drinks">
                        </div>
                        <div class="description">
                            <p><strong>Cold Bevarages</strong></p>
                            <p>Refreshing cold drinks, juices, and smoothies to cool you down.</p>
                        </div>
                    </li>
                    <li class="category6">
                        <div class="item">
                            <img src="@/assets/images/jpg/coffe.jpg" alt="Coffee">
                        </div>
                        <div class="description">
                            <p><strong>Hot Bevarages</strong></p>
                            <p>Warm, comforting beverages to enjoy with your meal or on their own.</p>
                        </div>
                    </li>
                </ul>
            </article>

            <hr class="menu-line">

            <article class="menu-cta">
                <p>Explore our delicious menu and treat yourself to mouth-watering meals and refreshing drinks! Order now or reserve your table for an unforgettable dining experience!</p>
                
                <br>

                <RouterLink class="homepage-cta" to="/menu">Explore  Our Menu & Order Now!</RouterLink>
            </article>
        </section>

        <!-- Featured about us -->
        <section class="about">
            <h2>Rendezvous Restaurent</h2>
        
            <div class="container">
                <div class="text">
                    <p>
                    Welcome to <strong>Rendezvous Restaurant</strong>, where culinary excellence meets
                    innovation. Nestled within the vibrant Steve Biko Campus at
                    <a href="http://dut.ac.za">Durban University of Technology</a>, Rendezvous was born from a
                    shared passion for great food, sustainability, and student empowerment. Our story is as
                    much about serving delicious meals as it is about fostering a space for creativity,
                    education, and community engagement.
                    </p>

                    <br><br>

                    <RouterLink class="homepage-cta" to="/about">Explore more about us</RouterLink>
                </div>

                <div class="media"></div>
            </div>
        </section>

        <section class="allergy-statement">
            <p>At Rendezvous Restaurant, we strive to offer a variety of delicious meals and beverages that cater to diverse tastes and preferences. <mark>Please note</mark> that some items on our menu may contain or come into contact with <mark>common allergens</mark>, including WHEAT, EGGS, PEANUTS, TREE NUTS, MILK, FISH, SHELLFISH, and SOY. We take food safety seriously and encourage customers with allergies or specific dietary concerns to <mark>inform our staff when placing orders</mark> so we can do our best to accommodate your needs.</p>
        </section>

    </div>
</template>

<style>
.hero {
    height: 100vh;
    background-image: url('@/assets/images/png/first-layer.png');
    background-size: contain;
    background-repeat: no-repeat;
    text-align: center;
}

.hero article {
    width: 100%;
    height: 100%;
    padding-left: 27rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.hero-line {
    height: 1rem;
    width: 60%;
    border: transparent;
    background: linear-gradient(to right, #63b37600 0%, #63b37649 50%, #63B375 100%);
}

.menu {
    padding: 5rem 2rem;
}

.menu-intro {
    text-align: center;
}

.menu-line {
    height: 1rem;
    width: 60%;
    margin: 2rem auto 4rem 30%;
    border: transparent;
    background: linear-gradient(to right, #63b37600 0%, #63b37649 50%, #63B375 100%);
}

.menu-category ul {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
    justify-items: center;
    width: 100%;
}

.menu-category ul li {
    width: 60%;
}

.item img {
    width: 100%;
    box-shadow: 0.125rem 0.125rem 0.5rem 0.0625rem rgba(0, 0, 0, 0.1);
}

.menu-cta {
    padding: 0 7rem;
    text-align: center;
}

.homepage-cta {
    background-color: #63B375;
    border-radius: 5rem;
    color: #0f152c;
    padding: .7rem 4rem;
    transition: .5s
}

.homepage-cta:hover {
    background-color: #63b3767c;
}

.about h2{
    text-align: center;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
}

.container div {
    width: 40%;
    margin: 2rem 4rem;
}

.media {
    background-image: url('@/assets/images/jpg/restaurant.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    height: 25rem;
    width: 10rem;
    box-shadow: .5rem .5rem .5rem .5rem rgba(0, 0, 0, 0.1);
}

.allergy-statement {
    padding: 4rem 8rem;
    text-align: center;
}
</style>