# project-1

Name:  Jordan Woodard

Overview:  This project is for a webpage that I made.  It is for a fictional company set in the year 2185, which is conducting space tours for people who live on Earth, taking them to different planets across the galaxy.

How to use:  The webpage is divided into three segments:  Summary, Tour, and Registration.  It is possible to explore these parts of the page by clicking on the links in the navbar.  The end of each segment features a link that reads "Go Back to Navbar" in italics, which takes the user back to the navbar.  There are also images placed within carousels, which show what these planets and their surfaces look like.  A validation form has been added as well, and whether the use fills it out correctly or not, a feedback message appears below each label whenever the user clicks the Submit button.

Technology used:  .html, .css

Ideas for future improvement:  set up navigation paths by using buttons, find an image large enough to cover the background instead of tiling a small image, try out more font variety

<head>
    <title>Space Tour</title>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="./project1.css">

</head>

<body>

  <!--navbar-->

    <nav class="navbar navbar-expand-lg bg-light" >
        <div class="container-fluid" id="backtothetop">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <a class="navbar-brand" href="#">Navbar</a>
          <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#summary">Summary</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#tour">Tour</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#registration">Registration</a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
          </div>
        </div>
    </nav>

    <!--Summary-->

    <div class="container my-4 text-center" id="summary">
           <img src="./astro_ex_logo.png" alt="astro ex logo">
          <h1>Greetings from Astro Ex!</h1>
    </div>
    

    <div class="container my-4">
      <div class="row">
        
        <section class="col-12">
              <h4>Introduction</h4>
              <p>Have you ever wondered what space travel feels like?  Do you look up at the stars and think about what (or who) lies beyond the solar system?  Are you tired of being stuck on the same rock every 
                day?  Then allow Astro Ex to help you satisfy your curiosity.  Whether you want to find a new world to colonize, plan on joining the military, are interested in meeting some alien races, or have a 
                taste for adventure, Astro Ex is here to fulfill your needs and desires.  So if you're ready to embark on a journey into the final frontier, then sign up for an Astro Ex Space Tour today!</p>
        </section>

        <section class="col-12">
             <h4>Purpose</h4>
             <p>Funded by an multinational space organization called the Human Advancement Coalition (or "HAC" for short), the Astro Ex corporation is in charge of its interstellar expansion efforts.  Basically, our job is 
              to map out other star systems and survey extrasolar worlds.  As humanity continues to expand across the galaxy, the Coalition needs to know which worlds are suitable for colonization, since each world 
              comes with its own surprises, and must prepare for whatever threats may lie ahead.  Based on Earth, our homeworld, Astro Ex has been supporting the Coalition since 2147.  Now we have been authorized by our
              employer to conduct space tours for Earth citizens who are willing to leave home, be it temporarily or permanently.</p>
        </section>
      
        <section class="col-12">
            <h4>Mission Statement</h4>
            <p>The Astro Ex corporation is honored to provide Earth civilians with an opportunity to explore the cosmos.  We at Astro Ex understand that space travel is a dangerous venture.  There's always the threat
              of astromonical events like asteroids and supernovas, as well as hostile encounters with space pirates and criminal organizations, not to mention the possibility of going to war with other spacefaring.  
              races.  Nevertheless, we are proud to show you that space is also a marvelous venture.  Life is full of risks.  Besides, if humanity was too afraid to take risks, then we wouldn't have been trying to leave 
              Earth in the first place.</p>
        </section>
        <div class="nav-item my-4">
            <a class="nav-link" aria-current="page" href="#backtothetop"><em>Go Back to Navbar</em></a>
        </div>
    </div>
  </div>

    <!--Tour-->

    <div class="container my-4 text-center" id="tour">
        <h1>A taste of what's to come</h1>
    </div>

    <div class="container my-4">
        <h4>List of Planets</h4>
        <p>As Astro Ex continues to discover new worlds, the stops along each tour are constantly changing.  Here is the list of the eight planets that have been scheduled for the next upcoming tour.</p>
    </div>

    <div class="container my-4">
      <div class="row">

        <section class="col-12">
          <div class="text-center">
          <h2>ANUBIS</h2>
          </div>
              <div id="anubis" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#anubis" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#anubis" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#anubis" data-bs-slide-to="2" aria-label="Slide 3"></button>
        <button type="button" data-bs-target="#anubis" data-bs-slide-to="3" aria-label="Slide 4"></button>
        <button type="button" data-bs-target="#anubis" data-bs-slide-to="4" aria-label="Slide 5"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="./anubis_landscape.jpg" class="d-block" height=300 alt="anubis 1">
        </div>
        <div class="carousel-item">
          <img src="./anubis_landscape.jpg" class="d-block" height=300 alt="anubis 2">
      </div>
      <div class="carousel-item">
        <img src="./anubis_landscape2.jpg" class="d-block" height=300 alt="anubis 3">
      </div>
      <div class="carousel-item">
        <img src="./anubis_landscape3.jpg" class="d-block" height=300 alt="anubis 4">
      </div>    
      <div class="carousel-item">
        <img src="./anubis_landscape4.jpg" class="d-block" height=300 alt="anubis 5">
      </div>  
    </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#anubis" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#anubis" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
      <p>The planet Anubis is littered with barren wastelands.  Rocky canyons, mesas, and plateaus can be found all over the surface.  The presence of water beds and giant fossils provides a hint that prehistoric life once 
           thrived here.  Unfortunately, a climate shift caused by its sun killed off every living creature on the planet, rendering Anubis completely devoid of life.  It only makes sense to name this world after the Egyptian 
            god of death.  By now, the Coalition has developed an industrial hub on this lifeless rock, mainly for producing weapons, armor, robots, and starships for the military.</p>
      </section>

      <section class="col-12">
        <div class="text-center">
          <h2>BASTION</h2>
        </div>
      <div id="bastion" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#bastion" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#bastion" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#bastion" data-bs-slide-to="2" aria-label="Slide 3"></button>
      <button type="button" data-bs-target="#bastion" data-bs-slide-to="3" aria-label="Slide 4"></button>
      <button type="button" data-bs-target="#bastion" data-bs-slide-to="4" aria-label="Slide 5"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./bastion_orbit.jpg" class="d-block" height=300 alt="bastion 1">
      </div>
      <div class="carousel-item">
        <img src="./bastion_landscape.jpg" class="d-block" height=300 alt="bastion 2">
        </div>
        <div class="carousel-item ">
          <img src="./bastion_landscape2.jpg" class="d-block" height=300 alt="bastion 3">
        </div>     
        <div class="carousel-item ">
          <img src="./bastion_landscape3.jpg" class="d-block" height=300 alt="bastion 4">
        </div>
        <div class="carousel-item ">
          <img src="./bastion_landscape4.jpg" class="d-block" height=300 alt="bastion 5">
        </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#bastion" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#bastion" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
      <p>A planet located near the western border of Human Space, Bastion is covered in vast mountain ranges.  Lakes and rivers divide up the rocky mountains, and fog often blankets parts of the surface.  Predatory birds, 
        which nest high above the surface, dominate the food chain on Bastion, feasting on the animals below.  Realizing the strategic value that the mountains provide and its close proximity to alien territory, the 
        Coalition established a military base on Bastion, in case relations with one of the alien races from the west turns sour.</p>
      </section>

      <section class="col-12">
        <div class="text-center">
          <h2>EDEN</h2>
        </div>
        <div id="eden" class="carousel slide">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#eden" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#eden" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#eden" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#eden" data-bs-slide-to="3" aria-label="Slide 4"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./eden_orbit2.jpg" class="d-block" height=300 alt="eden 1">
            </div>
            <div class="carousel-item">
              <img src="./eden_orbit.jpg" class="d-block" height=300 alt="eden 2">  
            </div>
            <div class="carousel-item">
              <img src="./eden_landscape.jpg" class="d-block" height=300 alt="eden 3">
            </div>
            <div class="carousel-item">
              <img src="./eden_landscape2.jpg" class="d-block" height=300 alt="eden 4">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#eden" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#eden" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <p>The picturesque world of Eden features grassy plains, as well as highlands and lakes.  It is a windy planet with a warm climate.  The plants and animals that can be found on Eden are relatively benign.  With its 
          calm weather and plentiful food sources, this planet has become known among the human race as a paradise world (just like its Christian namesake).  Not too long ago, the HAC transformed it into an agriculture center, 
          distributing food and water to nearby worlds in which such things are hard to come by.  The only real danger for Eden comes in the form of pirate attacks, as it is not very far from a lawless region of space to the 
          east.</p>
      </section>

      <section class="col-12">
        <div class="text-center">
          <h2>PACIFICO</h2>
        </div>
        <div id="pacifico" class="carousel slide">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#pacifico" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#pacifico" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#pacifico" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#pacifico" data-bs-slide-to="3" aria-label="Slide 4"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./pacifico_orbit.jpg" class="d-block" height=300 alt="pacifico 1">
            </div>
            <div class="carousel-item">
              <img src="./pacifico_landscape.jpg" class="d-block" height=300 alt="pacifico 2">
            </div>
            <div class="carousel-item">
              <img src="./pacifico_landscape2.jpg" class="d-block" height=300 alt="pacifico 3">
            </div>
            <div class="carousel-item">
              <img src="./pacifico_landscape3.jpg" class="d-block" height=300 alt="pacifico 4">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#pacifico" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#pacifico" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <p>Deriving its name from the Pacific Ocean back on Earth, Pacifico is a world covered in water.  98% of its surface is submerged under the ocean, while the other 2% is made up of island chains.  As expected, Pacifico 
          is home to a wide variety of marine creatures.  In addition, its tropical climate provides the ingredients for storms to develop on a regular basis.  When the Coalition found Pacifico, it decided to use it as a 
          communication hub, since it is placed alongside a trade route that runs through the southern side of Human Space.</p>
      </section>

      
      <section class="col-12">
        <div class="text-center">
          <h2>SURTUR</h2>
        </div>
          <div id="surtur" class="carousel slide">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#surtur" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#surtur" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#surtur" data-bs-slide-to="2" aria-label="Slide 3"></button>
              <button type="button" data-bs-target="#surtur" data-bs-slide-to="3" aria-label="Slide 4"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="./surtur_orbit2.jpg" class="d-block" height=300 alt="surtur 1">
              </div>
              <div class="carousel-item">
                <img src="./surtur_landscape.jpg" class="d-block" height=300 alt="surtur 2">
              </div>
              <div class="carousel-item">
                <img src="./surtur_landscape2.jpg" class="d-block" height=300 alt="surtur 3">
              </div>
              <div class="carousel-item">
                <img src="./surtur_landscape3.jpg" class="d-block" height=300 alt="surtur 4">
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#surtur" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#surtur" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
        </div>
        <p>A world that is known as a "pressure cooker" world, Surtur has lava and volcanic fields spread all over its surface.  Not only is it blazing hot, its atmosphere is also contaminated by ash particles, making the air 
          hazardous to breathe without respiratory equipment.  This planet gets its name from the Norse god of fire, due to its fiery landscape.  Meanwhile, the Coalition set up a mining operation on Surtur, on account of the 
          volcanic activity that provides an abundance of minerals.</p>
      </section>

      
      <section class="col-12">
        <div class="text-center">
          <h2>TARTARUS</h2>
        </div>
        <div id="tartarus" class="carousel slide">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#tartarus" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#tartarus" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#tartarus" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#tartarus" data-bs-slide-to="3" aria-label="Slide 4"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./tartarus_orbit.jpg" class="d-block" height=300 alt="tartarus 1">
            </div>
            <div class="carousel-item">
              <img src="./tartarus_landscape.jpg" class="d-block" height=300 alt="tartarus 2">
            </div>
            <div class="carousel-item">
              <img src="./tartarus_landscape2.jpg" class="d-block" height=300 alt="tartarus 3">
            </div>
            <div class="carousel-item">
              <img src="./tartarus_landscape4.jpg" class="d-block" height=300 alt="tartarus 4">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#tartarus" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#tartarus" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <p>Named after the Greek version of Hell, Tartarus is one of two planets located in the Hades system (the other being Elysium).  Its surface consists of deserts and rock formations.  Life is tough on Tartarus, due to
          its hot climate, the scarcity of food and water, its spiky vegetation, and the presence of deadly sandstorms.  These unforgiving conditions led to the wildlife becoming violent and aggressive in order to survive.  
          For such a hellish world, it's only fitting that the Coalition constructed a maximum security prison within one of Tartarus's deserts, where criminals are forced to live the rest of their days in agony.</p>
      </section>

      
      <section class="col-12">
        <div class="text-center">
          <h2>VERDINE</h2>
        </div>
        <div id="verdine" class="carousel slide">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#verdine" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#verdine" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#verdine" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#verdine" data-bs-slide-to="3" aria-label="Slide 4"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./verdine_orbit.jpg" class="d-block" height=300 alt="verdine 1">
            </div>
            <div class="carousel-item">
              <img src="./verdine_orbit2.jpg" class="d-block" height=300 alt="verdine 2">
            </div>
            <div class="carousel-item">
              <img src="./verdine_landscape.jpg" class="d-block" height=300 alt="verdine 3">
            </div>
            <div class="carousel-item">
              <img src="./verdine_landscape2.jpg" class="d-block" height=300 alt="verdine 4">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#verdine" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#verdine" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <p>Placed in a solar system that sits just north of our own, Verdine is a moon consisting of jungles and swamps.  Countless exotic plant and animal species inhabit this lush world.  Caution must be taken, though, as 
          many of them are poisonous.  Aside from that, it is possible to see the gas giant that Verdine orbits from the surface, along with some of the other moons.  Because of Verdine's rich biodiversity, the HAC established 
          a research center within one of the jungles.  The experiments being performed are for creating medicine.</p>
      </section>

      <section class="col-12">
        <div class="text-center">
          <h2>WONDER</h2>
        </div>
        <div id="wonder" class="carousel slide">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#wonder" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#wonder" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#wonder" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#wonder" data-bs-slide-to="3" aria-label="Slide 4"></button>
            <button type="button" data-bs-target="#wonder" data-bs-slide-to="4" aria-label="Slide 5"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="./wonder_orbit.jpg" class="d-block" height=300 alt="wonder 1">
            </div>
            <div class="carousel-item">
              <img src="./wonder_landscape.jpg" class="d-block" height=300 alt="wonder 2">
            </div>
            <div class="carousel-item">
              <img src="./wonder_landscape2.jpg" class="d-block" height=300 alt="wonder 3">
            </div>
            <div class="carousel-item">
              <img src="./wonder_landscape3.jpg" class="d-block" height=300 alt="wonder 4">
            </div>
            <div class="carousel-item">
              <img src="./wonder_landscape4.jpg" class="d-block" height=300 alt="wonder 5">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#wonder" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#wonder" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
          </div>
          <p>Thousands of years ago, a long-lost alien race inhabited the snowy tundras of Wonder.  When the HAC discovered some ancient ruins, it grew fascinated with who these enigmatic aliens were, so multiple archaeological 
            expeditions were commissioned.  So far, hundreds of artifacts have been found.  As for Wonder itself, it occupies a remote star system.  It is a difficult planet to reach because of its remoteness and the lack of any
            nearby hyperspace beacons, so extra caution must be taken while flying here.  Despite its freezing conditions, life can be found on the surface, especially in icy caves, where geothermal vents can be found.</p>
      </section>

      <div class="nav-item my-4">
        <a class="nav-link" aria-current="page" href="#backtothetop"><em>Go Back to Navbar</em></a>
    </div>

    </div>
  </div>

    <!--Registration-->

    <div class="container my-4 text-center" id="registration">
      <h1>Ready for a tour?</h1>
    </div>

    <div class="container my-4">
      <h4>Prices</h4>
      <p>Adults = 100 credits each</p>
      <p>Kids = 50 credits each</p>
    <div class="row">
      <div class="col-2 offset-3">
        <button type="button" class="btn btn-info">Sign Up</button>
      </div>
      <div class="col-2">
        <button type="button" class="btn btn-info">Tour Dates</button>
      </div>
      <div class="col-2">
        <button type="button" class="btn btn-info">Refund Policy</button>

      </div>
    </div>
    </div>


    <form class="container contact-form my-4 needs-validation" 
          action="#"
          method="POST"
          novalidate>
          <div class="form-group row">
            <div class="col-3 offset-3" >

                <label class="container-fluid p-0">
                    First Name
                    <input type="text" class="form-control" id="validationServerUsername" 
                        placeholder="Enter your first name"
                        required>
                    <span class="invalid-feedback">
                        Please enter a name.
                    </span>
                    <span class="valid-feedback">
                        Well done.
                    </span>
                </label>
                
            </div>
            <div class="col-3">

              <label class="container-fluid p-0">
                  Last Name
                  <input type="text" class="form-control" id="validationServerUsername2" 
                        placeholder="Enter your last name"
                        required>
                        <!--<span class="input-group-text" id="inputGroupPrepend3">@</span>-->
                    <span class="invalid-feedback">
                        Please enter a name.
                    </span>
                    <span class="valid-feedback">
                        Well done.
                      </span>
              </label>
              <!--<small id="emailHelp" 
                  class="form-text text-muted col-12">
                  * This field is mandatory.
              </small>-->

          </div>
        </div>
        <div class="form-group row">
            <div class="col col-md-6 offset-md-3">
                <label class="container-fluid p-0">
                    Email
                </label>
                <input type="email" 
                    class="form-control" 
                    id="password" 
                    placeholder="Enter your email" 
                    required>
                    <span class="invalid-feedback">
                      Please use a valid email address.
                    </span>
                  <span class="valid-feedback">
                      Well done.
                  </span>
            </div>
        </div>
        <div class="form-group row">
            <div class="col col-md-6 offset-md-3">
                <label for="textarea">
                    Message
                </label>
                <textarea class="form-control" 
                        id="textarea" 
                        rows="3"></textarea>
            </div>
        </div>
        <div class="form-group row">
            <div class="col col-md-6 offset-md-3">
                <button type="submit" 
                        class="btn btn-primary">
                    Submit
                </button>            
            </div>
        </div>
      
      <div class="nav-item my-4">
        <a class="nav-link" aria-current="page" href="#backtothetop"><em>Go Back to Navbar</em></a>
    </div>
  
  </form>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    
    <script src="https://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>

    <script src="./validate.js"></script>

</body>



