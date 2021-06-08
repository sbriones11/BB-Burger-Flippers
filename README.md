# BB-Burger-Flippers
Demonstration

<!DOCTYPE html>
<html>

<head>
    <!--Import Google Icon Font-->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

    <!--Import materialize.css-->
    <!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

    <!-- FONT AWESOME CDN -->
    <script src="https://kit.fontawesome.com/eb50945a84.js" crossorigin="anonymous"></script>

    <!--GOOGLE FONT-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap" rel="stylesheet">

    <!--Let browser know website is optimized for mobile-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>BB Burger Flippers</title>

    <link rel='stylesheet' href='./style.css'>
    <style>
* {
    font-size: large;
    font-family: 'Oswald', sans-serif;
}

.brand-logo {
    margin: 0 2rem;
    text-align: center;   
}
.slider {
    background-size: cover;
    font-size: large;
    font-family: 'Oswald', sans-serif;   
}

.fa-bars {
    margin: 0 1rem;
    color: white;
}

.fa-search {
    margin: 0 1rem;
    color: white;
}

.fa-truck {
    margin: 0 1rem;
    color: white;
}

.fa-cart {
    margin: 0 1rem;
    color: white;
}


.fa-hamburger {
    margin: 0 1rem;
    color: white;
}

.fa-cheese {
    margin: 0 1rem;
    color: white;
}

.fa-leaf {
    margin: 0 1rem;
    color: white;
}

.fa-stroopwafel {
    margin: 0 1rem;
    color: white;
}

.center-align {
    margin: 5rem 0;
}

.yellow-text {
    font-size: xx-large;
    font-family: 'Oswald', sans-serif;
    text-align: center;
    text-shadow: black;
}

.parallax img {
    width: 100vw;
}


@media only screen and (max-width: 800px) {

    .parallax-container {
        height: 200px;
    }
}



    </style>
</head>
<body>

<!-- NAVBAR -->
    <div class="navbar">
        <nav class="black">
            <div class="nav-wrapper">
                <a href="#" class="brand-logo">
                <span class="yellow-text darken-2">BB </span>Burger Flippers</a>
            </div></nav></div>

<!-- SLIDER ADDS -->
    <section class="slider">
        <ul class="slides">
            <li><img src="./img/slider1.jpg" alt="Burgers">
            <div class="caption center-align">
                <h3>
                    Looking for tasty and affordable meal?
                </h3></div></li>
            <li><img src="./img/slider2.jpg" alt="Burgers">
                <div class="caption center-align">
                <h3>
                    Check our menu and grab yours now!
                </h3></div></li>
            <li><img src="./img/slider3.jpg" alt="Burgers">
            <div class="caption center-align">
                <h3>
                    Enjoy eating with us!
                </h3></div></li>
            <li><img src="./img/slider4.png" alt="Burgers">
                <div class="caption center-align"></div>
            </li>
        </ul>

        <!--Nav bar-->
        <nav class="nav-wrapper black">
            <div class="sidenav-trigger" ></div> 
                <a href="" class="sidenav-trigger" data-target="mobile-menu">
                <i class="fas fa-bars"></i></a></div>
            <ul class="right hide-on-med-and-down">
                <li><a href="#search"><i class="fas fa-search"></i></a></li>
                <li><a href="#cart"><i class="fas fa-shopping-cart"></i></a></li>
                <li><a href="#delivery"><i class="fas fa-truck"></i></a></li>
            </ul>

            <ul class="sidenav grey lighten-2" id=mobile-menu>
                <li><a href="#">Search</a></li>
                <li><a href="#">Cart</a></li>
                <li><a href="#">Delivery</a></li>
            </ul>
        </nav>
        <!-- SIDENAV -->
        <ul id="nav-active" class="sidenav">
            <li><a href="#menu">Menu</a></li>
            <li><a href="#Order Now">Order Now</a></li>
            <li><a href="#Delivery">Delivery</a></li></ul>
    </section>

<!-- CARD MENU -->
    <section class="section">
        <h2 class="yellow-text darken-2">- Menu -</h2>
        <br>
    <div class="row">

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card1.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">BF Burger<i
                    class="fas fa-plus white-text right"></i></span>
            </div>            
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 69.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam iusto facilis doloribus repellendus totam aspernatur maxime libero commodi sequi deleniti. Eum eos optio illum possimus!.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card2.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Aloha BF Burger<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 89.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae esse quasi quo, minus perferendis dolores, facere voluptatem dolorem iusto sed maxime, architecto ipsum voluptates ex.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card3.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Texas BF Burger<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 89.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card4.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">BF + Sides<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 110<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card5.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Aloha + Sides<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 130.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>
        
        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card6.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Texas + Sides<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 130.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>
                
        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card7.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">BF Chicken Burger<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 99.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>
        
        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card8.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Burger Blowout<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 199.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card9.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Box of Fries<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 49.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>
        
        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card10.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Box of Onion Rings<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 69.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card11.jpg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Crispy Nuggets<i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 89.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>

        <div class="col s6 m3">
        <div class="card black">
            <div class="card-image waves-effect waves-block waves-light">
            <img class="activator" src="./img/img-card12.jpeg"></div>
            <div class="card-content">
                <span class="card-title activator yellow-text darken-2">Tuna Pesto Pasta <i
                class="fas fa-plus white-text right"></i></span></div>
            <div class="card-reveal black">
                <span class="card-title yellow-text darken-2">p 99.00<i
                class="material-icons right">close</i></span>
                <p class="grey-text lighten-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Porro odio doloribus facere error ullam cumque quae, eos qui omnis enim quos neque dicta saepe ratione.</p></div>
        </div>
        </div>
    </div>
</section>

<!--COLLAPSIBLE BURGER PARTS-->
<section class="section">
    <h2 class="yellow-text darken-2">- What's Inside? -</h2>
<br>
    <div class="row">
    <div class="col s12 m6">
        <img class="materialboxed responsive-img" src="./img/collapsible1.png"></div>
    
    <div class="col s12 m6">
        <ul class="collapsible popout">
            <li class="active">
                <div class="collapsible-header black white-text"><i class="fas fa-hamburger"></i>Bun</div>
                <div class="collapsible-body"><span>Pillowy brioche homemade buns with sesame seeds on top.</span></div></li>
            <li>
                <div class="collapsible-header  black white-text"><i class="fas fa-cheese"></i>Cheese</div>
                <div class="collapsible-body"><span>Special cheese matched with homemade sauce back to back.</span></div></li>
            <li>
                <div class="collapsible-header black white-text"><i class="fas fa-stroopwafel"></i>Patty</div>
                <div class="collapsible-body"><span>Delicious and tasty homemade patties with no extenders.</span></div></li>
            <li>
                <div class="collapsible-header black white-text"><i class="fas fa-hamburger"></i>Cucumber</div>
                <div class="collapsible-body"><span>Served clean and fresh cucmber from the market.</span></div></li>
            <li>
                <div class="collapsible-header black white-text"><i class="fas fa-hamburger"></i>Tomatoes and Onions</div>
                <div class="collapsible-body"><span>Served clean and fresh tomatoes and onions from the market.</span></div></li>
            <li>
                <div class="collapsible-header black white-text"><i class="fas fa-leaf"></i>Lettuce</div>
                <div class="collapsible-body"><span>Served clean and fresh lettuce from the market.</span></div></li>
        </ul>
    </div>
    </div>       
</section>

<!--PARALLAX 1-THE BUSINESS-->
<section class="">
    <h2 class="yellow-text darken-2 lighten-2">THE BUSINESS</h2>
    <br>
</section>

<!--DELIVERIES-->
    <section class="section">
        <div class="parallax-container">
        <div class="parallax">
            <img src="./img/parallax1.jpg" alt=""></div></div>
        <div class="container">
            <h2 class="yellow-text darken-2">- Deliveries -</h2>
            <p class="center-align black-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit, sapiente doloremque necessitatibus ad explicabo, iure quam magni voluptate eum nemo, nisi fugiat inventore odit id ipsum amet eos? Eveniet facilis corporis consequatur in aliquid veritatis iure alias voluptas ex officia culpa possimus accusamus ad, dolorum rem! Aliquam tempore iure id!</p></div>
    </section>

<!--OUR PACKAGING-->
    <section class="section">
        <div class="parallax-container">
        <div class="parallax">
            <img src="./img/packaging.png" alt=""></div></div>
        <div class="container">
            <h2 class="yellow-text darken-2">- Our Packaging -</h2>
            <p class="center-align black-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti reiciendis nihil vero, quasi facilis ducimus repudiandae architecto, voluptatum nam quis doloribus. Nobis itaque ipsa aperiam vero sequi, tempora impedit illum? Voluptate dignissimos facilis excepturi soluta cupiditate ipsa, fugiat temporibus quaerat. Odio aliquid minima, dolorum id laudantium aspernatur enim consequatur possimus.</p></div>
    </section>

<!--FOOTER-->

        <div class="footer-copyright center-align">
        <div class="container">
        © 2014 Copyright BB Burger Flippers PH
        </div>
        </div>
    </footer>


    <!-- <footer class="white center-align">
        <span class="grey-text text-darken-1">&copy 2020, BB Burger Flippers</span>
    </footer> -->

    <!--JavaScript at end of body for optimized loading-->
    
    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    <script>

        document.addEventListener('DOMContentLoaded', () => {
            // SIDENAV
            const sideNav = document.querySelector('.sidenav');
            M.Sidenav.init(sideNav);

            // SLIDER
            const slider = document.querySelector('.slider')
            M.Slider.init(slider)

            // COLLECTIBLES
            const collapsible = document.querySelectorAll('.collapsible')
            M.Collapsible.init(collapsible)

            // PARALLAX
            const parallax = document.querySelectorAll('.parallax')
            M.Parallax.init(parallax)

            // MATERIALBOXED
            const materialBoxes = document.querySelectorAll('.materialboxed')
            M.Materialbox.init(materialBoxes)

            // CAROUSEL 
            const carousels = document.querySelectorAll('.carousel')
            M.Carousel.init(carousels)

        })
        //         / Or with jQuery

        //   $(document).ready(function(){
        //     $('.slider').slider();


        // OPTIONS 
        // SIDENAV
        // edge: left
        // draggable: true 
        // inDuration: 250
        // outDuration: 200
        // onOpenStart: function()
        // preventScrolling: true

        // SLIDER
        // indicators: true
        // height: 400
        // duration: 500
        // interval: 6000

        // // COLLAPSIBLES
        // accordion: true
        // inDuration: 300
        // outDuration: 300

        // PARALLAX
        // responsiveThreshold: 0

        // MATERIALBOX
        // inDuration: 275
        // outDuration: 200




    </script>
</body>

</html>
