<template>
    <div class="contact">
        <!-- Banner -->
        <header>
            <h1>Contact</h1>
        </header>

        <main>
            <section class="contact-info">
                <address>
                    <h2>Contact Information</h2>
                    <ul>
                        <li><strong>Location:</strong> Steve Biko Campus, Durban University of Technology</li>
                        <li><strong>Operating Hours:</strong>
                            <ul>
                                <li>First Semester: Wednesday & Thursday: 11:00 AM - 2:00 PM</li>
                                <li>Second Semester: Wednesday, Thursday & Friday: 11:00 AM - 2:00 PM</li>
                            </ul>
                        </li>
                        <li><strong>Phone:</strong> <a href="tel:+27313732500">+27 (0)31 373 2500</a></li>
                        <li><strong>Email:</strong> <a href="mailto:info@rendezvousrestaurant.co.za">info@rendezvousrestaurant.co.za</a></li>
                    </ul>
                </address>

                <address>
                    <h2>Contact Persons</h2>
                    <ul>
                        <li><strong>Jane Visagie (Head of Department):</strong> <a href="tel:+27313732501">+27 (0)31 373 2501</a> | <a href="mailto:jane.visagie@dut.ac.za">jane.visagie@dut.ac.za</a></li>
                        <li><strong>Jabu Chiya (Reservations Coordinator):</strong> <a href="tel:+27313732502">+27 (0)31 373 2502</a> | <a href="mailto:jabu.chiya@dut.ac.za">jabu.chiya@dut.ac.za</a></li>
                        <li><strong>Noxolo Blose (Customer Relations Manager):</strong> <a href="tel:+27313732503">+27 (0)31 373 2503</a> | <a href="mailto:noxolo.blose@dut.ac.za">noxolo.blose@dut.ac.za</a></li>
                    </ul>
                </address>
            </section>

            <section class="map">
                <h2 style="text-align: center;">Find Us</h2>
                <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d348.94679767178804!2d31.0038597!3d-29.8537739!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1ef7a9e8ac84fe5f%3A0x7944dd47ee8de972!2sRendezvous%20Restaurant!5e0!3m2!1sen!2sza!4v1693912322495!5m2!1sen!2sza" 
        loading="lazy"></iframe>
            </section>
        </main>
    </div>
</template>

<style>
.contact {
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

.contact-info {
    display: flex;
    justify-content: center;
    padding: 4rem 2rem;
}

.contact-info ul {
    margin: 1rem 4rem;
}

.contact-info ul li {
    line-height: 2rem;
}

.map iframe {
  width: 100%;
  height: 400px;
  border: 0;
}
</style>