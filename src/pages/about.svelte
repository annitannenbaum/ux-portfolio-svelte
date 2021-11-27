<script>
</script>

<main>
        <div class="about-container">
                <div class="heading-container">
                        <h2>Hamburg</h2>
                        <h2>UI/UX</h2>
                        <h2>Dogs</h2>
                        <h2>Illustrate</h2>
                        <h2>Music</h2>
                        <h2>Art</h2>
                        <h2>Fashion Brands</h2>
                </div>
                <div class="paragraph-container">
                        <p>Currently based in Hamburg and working at <a href="www.thinfabrics.com">thinfabrics GmbH</a>.</p>
                        <p>
                                Since 2015 I'm a trained communication designer, but I put my hands into the digital world and
                                became a UI/UX designer.
                        </p>
                        <p>
                                Hamburg is my home, but I still want to see the world. I like to explore new spots in my hometown
                                with my dog Paul, he is a lab-husky-mix (a.ka. crazy dog).
                        </p>
                        <p>
                                My other passion is to collect sneakers and unfortunately spend way too much money on them.
                        </p>
                        <img src="assets/svg/peace.svg" alt="peace sign">
                </div>
        </div>
</main>

<style>
        a {
                padding: 0;
                color: white;
                text-decoration: underline;
        }
        p {
                color: white;
        }
        h2 {
                margin: 0;
                padding: 0;
        }

        .about-container {
                padding: 0 5rem;
                display: flex;
                flex-direction: row;
                align-items: center;
        }

        .paragraph-container {
                width: 50%;
                margin-left: 10rem;
                margin-bottom: 12rem;
        }

        @media screen and (max-width: 1024px) {
                .about-container {
                        flex-direction: column;
                }

                .paragraph-container {
                        width: 100%;
                        margin: 0;
                }
  }
</style>