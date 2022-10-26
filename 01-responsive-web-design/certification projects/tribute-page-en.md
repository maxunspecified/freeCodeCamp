---
id: bd7158d8c242eddfaeb5bd13
title: Build a Survey Form
isRequired: true
challengeType: 2
isHidden: false
---

## HTML
```

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1"> 
    <script src="https://kit.fontawesome.com/f6cfa43d23.js" crossorigin="anonymous"></script>
    <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <main id="main">
    <header>
      <nav>
        <ul>
         <li class="nav-pill"><a href="#life-section">EARLY LIFE</a></li>
         <li class="nav-pill"><a href="#edu-section">EDUCATION</a></li>
          <li class="nav-pill"><a href="#early-bus">PAYPAL & ZIP2</a></li>
         <li class="nav-pill"><a href="#falcon1-section">SPACEX</a></li>
        </ul>
      </nav>
      <section class="header-image">
        <div class="header-image-text">
            <h1 id="title">Elon Musk</h1>
            <h2>"Land on Mars, a round-trip ticket, half a million dollars. It can be done."</h2>
          </div>
      </section>
    </header>
    <main>
      <section class="information-section" id="life-section">
        <h2>Early Life</h2>
      <hr class="responsive-hr">
      <div class="text-wrapper">
        <div class="project-card" id="img-div"> <!-- Test 3 -->
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/86/PBHS-facade.jpg" alt="Pretoria Boys High School" id="image"/> <!-- Test 4 -->
      <div class="project-desc" id="img-caption"> <!-- Test 5 -->
        <p>Pretoria Boys High School</p>
        <a href="https://en.wikipedia.org/wiki/Elon_Musk"target="_blank"class="view-project-button"> Wikipedia Page </a>
      </div>
    </div>
      <div class="image-text">
          <h3>June 28th, 1971</h3>
          <p id="tribute-info">Elon Reeve Musk was born on June 28, 1971, in Pretoria, one of the capital cities of South Africa. Musk has British and Pennsylvania Dutch ancestry. His mother is Maye Musk, a model and dietitian born in Saskatchewan, Canada and raised in South Africa. His father is Errol Musk, a South African electromechanical engineer, pilot, sailor, consultant, and property developer who was a half-owner of a Zambian emerald mine near Lake Tanganyika. Musk has a younger brother, Kimbal, born in 1972 and a younger sister, Tosca, born in 1974. Musk's family was wealthy during his youth. His father was elected to the Pretoria City Council as a representative of the anti-apartheid Progressive Party, with his children reportedly sharing their father's dislike of apartheid. His maternal grandfather, Joshua Haldeman, was an adventurous American-born Canadian who took his family on record-breaking journeys in a single-engine Bellanca airplane to Africa and Australia. After his parents divorced in 1980, Musk mostly lived with his father. Musk later regretted his decision because he has become estranged from his father. He has a paternal half-sister and a half-brother. In his biography, Ashlee Vance described Musk as an awkward and introverted child. When Musk was age ten, he developed an interest in computing and video games, teaching himself how to program from his Commodore VIC-20 user manual. At age twelve, he sold his BASIC-based game Blastar to PC and Office Technology magazine for approximately $500.</p> <!-- test 6  -->
          </div>
    </div>
      </section>
      <section class="information-section" id="edu-section">
        <h2>Education</h2>
      <hr class="responsive-hr">
      <div class="text-wrapper row-reverse">
        <div class="project-card">
      <img src="https://www.incimages.com/uploaded_files/image/1920x1080/feature-114-Elon-Musk-EoY-opener-pan_7026.jpg" alt="Elon Musk in his collage dorm"/>
      <div class="project-desc">
        <p>Elon Musk in his collage dorm</p>
        <a href="https://www.youtube.com/watch?v=CQbKctnnA-Y"target="_blank"class="view-project-button"> Elon Musk Interview on Collage </a>
      </div>
    </div>
      <div class="image-text">
          <h3>1989</h3>
          <p>Msuk attended Waterkloof House Preparatory School, Bryanston High School and graduated from Pretoria Boys High School. In 1989, Elon would immigrate from South Africa to Canada and later to the United States. In 1990, after a year of working at a lumber mill, Elon attended Queen's University in Kingston, Ontario. He later transferred to the University of Pennsylvania, where he graduated in 1997. Elon double majored in economics and physics, which provided a solid foundation for the tech industry. During collage in 1994, Elon pursued two Silicon Valley internships at the Pinnacle Research Institute for battery technology and the video game developer Rocket Science Games. His dream was to always have a tech start-up, resulting in him dropping his PhD program at Stanford University for materials science in 1995 after only two days. Musk decided to join the Internet boom instead and applied for a job at Netscape, to which he reportedly never received a response.</p>
          </div>
    </div>
      </section>
      <section class="quote-section" id="quantum-quote">
        <h2>Wow, I super loved astronomy (but took it at Queens, not Penn)! Definitely one of my favorite classes. Senior year quantum mechanics at Penn was the hardest class I ever took. That stuff will mess with your mind.</h2>
        <p class="quote-person"><i>- Elon Musk, <time datatime="8-30-2020">Aug 30, 2020</time></i><a class="twitter-logo" target="_blank"href="https://twitter.com/elonmusk/status/1300106137413582849?s=20" id="tribute-link"><i class="fab fa-twitter"></i></a></p> <!-- test 7  -->
      </section>
       <section class="information-section" id="early-bus">
        <h2>Early Business Ventures</h2>
      <hr class="responsive-hr">
      <div class="text-wrapper">
        <div class="project-card">
      <img src="https://loopinput.com/wp-content/uploads/2020/03/image4-1.png" alt="Elon Musk in his collage dorm"/>
      <div class="project-desc">
        <p>Elon Musk in his collage dorm</p>
        <a href="https://en.wikipedia.org/wiki/Zip2"target="_blank"class="view-project-button"> Wikipedia Article</a>
      </div>
    </div>
      <div class="image-text">
          <h3>1995 | Zip2</h3>
          <p>In 1995, Elon Musk and his brother Kimbal along with Greg Kouri founded Zip2. In Ashlee Vance's biography of Elon Musk, it is claimed that the Musks' father, Errol Musk, provided them with US$28,000 during this time, but Elon Musk later denied this, claiming that his father invested in a later round of funding. The software company set out to design an internet-based city guide with maps, directions and yellow pages of a chosen city. The company sold software packages to newspaper publishers in order to add various locations to the database. These newspaper companies could also publish online via the network. Before the company took off, Elon was too broke to afford more than an office and a couch to sleep on. He showered at the YMCA and ate fast food 4 days a week to scrape by. The company was initially invested in by the venture capital firm Mohr Davidow Ventures for $3 million, resulting in a move to Palo Alto. The New York Times and various other publishers later invested $50 million into the company. CitySearch offered a deal of over $300 million to merge with Zip2, but the deal was called off after backlash from Elon. Elon lost his chairman position in the company and later Zip2 was sold for $307 million to Compaq in 1999. Elon walked away from the deal with $22 million for his 7% share. His first major business venture during the internet boom made Elon a millionaire before the age of 30</p>
          </div>
    </div>
         <div class="text-wrapper row-reverse">
        <div class="project-card">
      <img src="https://vni.s3.amazonaws.com/180203190648543.png" alt="X.com Original Website"/>
      <div class="project-desc">
        <p>X.com Original Website</p>
        <a href="https://en.wikipedia.org/wiki/X.com"target="_blank"class="view-project-button"> Wikipedia Article  </a>
      </div>
    </div>
      <div class="image-text">
          <h3>1999 | X.com and PayPal</h3>
          <p>Later in 1999, Musk co-founded X.com, an online financial services and e-mail payment company. X.com was one of the first federally insured online banks and over 200,000 customers joined after its initial months of operation. Even though Musk founded the company, investors regarded him as inexperienced and replaced with Intuit CEO Bill Harris by the end of the year. In 2000, X.com merged with online bank Confinity to avoid competition as Confinity's money-transfer service PayPal was more popular than X.com's service. Musk then returned as CEO of the merged company. His preference for Microsoft over Unix-based software caused a rift among the company's employees and Peter Thiel, Confinity's founder, to resign. In addition to compounding technological issues and a lack of a cohesive business model, the board ousted Musk and replaced him with Thiel in September 2000. Under Thiel, the company focused on the money transfer service and renamed as PayPal in 2001. The next year, PayPal was acquired by eBay for $1.5 billion in stock, of which Musk—the largest shareholder with 11.72% of shares—received $175.8 million. More than one and a half decades later, Musk purchased the domain X.com from PayPal in 2017 because of his personal sentimental value.</p>
          </div>
    </div>
      </section>
           <section class="quote-section" id="bus-quote">
        <h2>My share of profits from the PayPal acquisition were $180 million. I put $100 million in SpaceX, $70m in Tesla, and $10m in Solar City & I had to borrow money for rent.</h2>
        <p class="quote-person"><i>- Elon Musk, <time datatime="6-11-2016">June 11 2016</time></i>
        </p>
      </section>
      <section class="information-section" id="falcon1-section">
        <h2>SpaceX</h2>
      <hr class="responsive-hr">
      <div class="text-wrapper">
        <div class="project-card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Elon_Musk_at_MSC_2006.jpg/1280px-Elon_Musk_at_MSC_2006.jpg" alt="Elon Musk at the 9th Annual Mars Society"/>
      <div class="project-desc">
        <p>Elon Musk at the 9th Annual Mars Society</p>
        <a href="https://youtu.be/PK0kTcJFnVk?t=674"target="_blank"class="view-project-button"> 15th Annual Mars Society </a>
      </div>
    </div>
      <div class="image-text">
          <h3>2001</h3>
          <p>In early 2001, Musk became involved with the nonprofit Mars Society and discussed funding plans to place a growth-chamber for plants on Mars. In October the same year, he traveled to Moscow with Jim Cantrell and Adeo Ressi to buy refurbished intercontinental ballistic missiles (ICBMs) that could send the greenhouse payloads into space. He met with companies NPO Lavochkin and Kosmotras; however, Musk was seen as a novice and the group returned to the United States empty-handed. In February 2002, the group returned to Russia with Mike Griffin (president of In-Q-Tel) to look for three ICBMs. They had another meeting with Kosmotras and were offered one rocket for $8 million, which Musk rejected. He instead decided to start a company that could build affordable rockets. With $100 million of his early fortune, Musk founded SpaceX in May 2002 and became the company's CEO and Chief Engineer. From 2001 to 2021, SpaceX would develop many unique launch vehicles, pushing the grounds of what is possible in the aerospace industry.</p>
          </div>
    </div>
        <div class="text-wrapper row-reverse">
        <div class="project-card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Falcon_1_Flight_4_liftoff.jpg" alt="Falcon 1 on its 4th flight"/>
      <div class="project-desc">
        <p>Falcon 1 on its 4th flight</p>
        <a href="https://en.wikipedia.org/wiki/Falcon_1"target="_blank"class="view-project-button">Wikipedia Article</a>
      </div>
    </div>
      <div class="image-text">
          <h3>Falcon 1 | 2002 - 2009</h3>
          <p>Falcon 1 was the first rocket developed by SpaceX. Developed from 2002 to 2005 and flown from 2006 to 2009, Falcon 1 achieved orbit twice successfully. The Falcon 1 was a two-stage rocket that could achieve 1400 LBS to 185 KM LEO or 990 LBS to SSO. The first and second Falcon 1 rockets were powered by a Merlin 1A engine for the first stage. This engine produced 76,000 pounds of thrust, with a total weight of 150 pounds, fed by a 20,000-RPM-turbo pump. The final 3 flights of the Falcon 1 replaced the Merlin 1A with the Merlin 1C, resulting in 110,000 LBS of thrust, fueled by a 22,000-RPM-turbo pump. The second-stage engine was a pressure-fed Krestal vaccum engine with 2.9 tons of thrust, cooled radiatively. Each engine was fueled by RP-1 (refined kerosene) and Liquid Oxygen. The rocket itself stood 69 ft tall with a 5.6 ft diameter. The total weight came out to 62,000 pounds. All launches were conducted on Omelek Island in the Marshal island chain. The first two launches were funded by the United States Department of Defense under DARPA.</p>
          </div>
        </div>
         <h3>Falcon 1 launch history</h3>
        <div class="small-card-container" id="falcon1-gallary">
          <div class="small-card-wrapper">
          <div class="project-card small-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/SpaceX_falcon_in_warehouse.jpg" alt="Falcon 1 Assembled via Friction Welding"/>
      <div class="project-desc">
        <p>Falcon 1 Assembled via Friction Welding</p>
        <a href="https://www.youtube.com/watch?v=0a_00nJ_Y88" target="_blank"class="view-project-button">Flight 1 Video</a>
      </div>
          </div>
            <div class="image-text small-card">
          <h3>24 March 2006</h3>
          <p>First launch of Falcon 1. The payload was the 19.5 kg FalconSAT-2 with an operating altitude of 500 km in LEO. The FalconSAT-2, designed to study the affects of plasma on rocket communications equipment, was developed by the United States Air Force Academy with a student-led team. Its original use was intended for the Space Shuttle Atlantis in 2003 but was canceled after the Columbia accident. A rusted bolt caused a fuel leak in Merlin 1A engine, resulting in engine failure and loss of vehicle at T+33 seconds. The FalconSAT-2 was blown clean from the rocket, and landed a few feet away from the shipping container it arrived in.</p>
          </div>
        </div>
          <div class="small-card-wrapper">
          <div class="project-card small-card">
            <img src="https://i.postimg.cc/fbLgdK0m/Falcon-1-flight-2.png" alt="Falcon 1 thown off course after impacting first stage"/>
      <div class="project-desc">
        <p>Second stage thrown off course after impacting first stage.</p>
        <a href="https://www.youtube.com/watch?v=f9FVOKtRPAE"target="_blank"class="view-project-button">Flight 2 Video</a>
      </div>
          </div>
            <div class="image-text small-card">
          <h3>21 March 2007</h3>
          <p>Second launch of Falcon 1. The payload was an LEO DemoSat made from a boiler plate designed to be a test payload for rockets that had previously experienced a failure. First stage reached orbit, but the second stage impacted the first stage during staging at T+173 seconds. Harmonic oscillation at T+5 minutes and a later engine shut down at T+7 minutes resulted in failure to reach orbit.<p>
          </div>
        </div>
          <div class="small-card-wrapper">
          <div class="project-card small-card">
            <img src="https://i.postimg.cc/9QjDz8Kg/FACLON-1-FLIGHT-3.png" alt="The second stage fairing coming off after failed staging (earth on the left) "/>
      <div class="project-desc">
        <p>The second stage fairing coming off after failed staging (earth on the left) </p>
        <a href="https://www.youtube.com/watch?v=Qz0yJ8N3cA0"target="_blank"class="view-project-button">Flight 3 Video</a>
      </div>
          </div>
            <div class="image-text small-card">
          <h3>3 August 2008</h3>
          <p>Third launch of Falcon 1. The 4 kg LEO payload was composed of four satellites: Trailblazer, PRESat, NanoSail-D, and Explorers. At T+173 seconds, unburnt fuel in the combustion chamber of the Merlin 1A provided extra thrust to first stage during staging. This extra thrust caused the first stage to push itself into the bottom of the second stage after initial staging. The second stage then fired while still being in contact with the first stage, resulting in a spin. The fairing later came off the vehicle and all 4 satellites failed to reach orbit. This problem was fixed by adding a delay between first-stage engine cut-off and staging.</p>
          </div>
        </div>
          <div class="small-card-wrapper">
          <div class="project-card small-card">
            <img src="https://i.postimg.cc/Z5d6MsyJ/falcon-4.jpg" alt="Moments before liftoff of the fourth flight"/>
      <div class="project-desc">
        <p>Moments before liftoff of the fourth flight</p>
        <a href="https://www.youtube.com/watch?v=lgRk6AdHN4Q"target="_blank"class="view-project-button">Flight 4 Video</a>
      </div>
          </div>
            <div class="image-text small-card">
          <h3>28 September 2008</h3>
          <p>Fourth launch of the Falcon 1. The payload was a 165 kg boiler plate in the shape of a hexagonal prism to LEO, designed as a dummy payload for rockets that had previous failures. The payload originally was supposed to be a RazakSAT, but they required a previously successful flight of the rocket. This mission was SpaceX's last attempt at getting into orbit. If this attempt had failed, then SpaceX would be bankrupt. Elon musk was so broke he didn't even own a house and his other companies were on the edge of bankruptcy. The flight itself was first scheduled on the 23rd to 25th, but a depressurization of the rocket during shipping in the C-17 cargo plane resulted in damage to the second stage engine pipline. The flight was a success, putting the payload in a 643 km orbit after a 9-minute and 31 second coast. This launch made SpaceX the first privately-developed rocket company with a fully filled, liquid rocket to reach orbit. The RazakSAT would later fly on the fifth and final Falcon 1 flight.</p>
          </div>
        </div>
        </div>
      </section>
      <section class="quote-section" id="bus-quote">
        <h2>I think it is important that we become a space-faring civilization and be out there among the stars ... We want the things that are in science fiction novels and movies not be science fiction forever. We want them to be real one day.</h2>
        <p class="quote-person">- Elon Musk, <time datatime="8-30-2020">Aug 30, 2020</time><a class="newspaper-logo" target="_blank"href="https://www.cnbc.com/2019/03/06/elon-musk-on-spacex-i-always-thought-we-would-fail.html"><i class="fas fa-newspaper"></i></a>
        </p>
      </section>
      <section class="information-section" id="falcon9">
        <h2>Falcon 9</h2>
      <hr class="responsive-hr">
      <div class="text-wrapper row-reverse">
        <div class="project-card">
      <img src="https://i.postimg.cc/zGTfQydY/falcon-9-liftoff.jpg"  alt="Block 5 Falcon 9 Launching Dragon Capsule to ISS"/>
      <div class="project-desc">
        <p>Block 5 Falcon 9 Launching Dragon Capsule to ISS</p>
        <a href="https://youtu.be/4xJAGFR_N-c?t=1243"target="_blank"class="view-project-button"> CRS-21 Mission </a>
      </div>
    </div>
      <div class="image-text">
          <h3>V1.0 | 2005 - 2010</h3>
          <p>The Falcon 9 is the second launch system developed by SpaceX. Falcon 9 was developed in five stages, with the fifth stage resulting in a medium-lift orbital-class rocket designed for partial reusibility. The first development block, from 2005 to 2010, introduced the original Falcon 9 V1.0. The V1.0 was designed to launch the cargo dragon to the ISS under a commercial resupply contract for NASA. The first stage was powered by six Merlin 1C engines, with each engine delivering 125,000 pounds of thrust. All 6 engines were arranged in a 3x3 grid with a TEA-TEB ignitor. The second stage was powered by a single Merlin 1C engine outfitted with an expansion nozzle for vacuum conditions. The rocket was 157 ft tall and 12 ft in diameter, weighing 735,000 pounds. The vehicle is capable of lifting 20,000 pounds or a dragon capsule, to LEO. Five flights took place from Mid 2010 to early 2013, with 1 failure during the CRS-1 mission (4th flight) due to engine failure. The first stage was outfitted with parachutes for the first two flights in an attempt to recover, however the booster burnt up on reentry before parachutes could deploy.
        </p>
          </div>
    </div>
       <div class="text-wrapper">
        <div class="project-card">
      <img src="https://i.postimg.cc/xdxVpYSS/falcon-heavy-engines.jpg" alt="Falcon Heavy being prepared for STP-2 mission next to recovered Falon 9 booster"/>
      <div class="project-desc">
        <p>Falcon Heavy being prepared for STP-2 mission next to recovered Falon 9 booster</p>
        <a href="https://youtu.be/WxH4CAlhtiQ?t=1482"target="_blank"class="view-project-button"> STP-2 Mission </a>
      </div>
    </div>
      <div class="image-text">
          <h3>V1.1 | 2011 - 2016</h3>
          <p>The Falcon 9 V1.1 is the second block in the Falcon 9 development phase. The rocket was developed from 2011 to 2013 and flew from 2013 to 2016. V1.1 was 224 ft tall with 60% more weight then the V1.0; powered by nine Merlin 1D first-stage engines that provided 60% more thrust in a Octaweb configuration. The second stage was powered by a single Merlin 1D vacuum engine. Payload to LEO increased from 23,000 to 29,000 pounds. The first stage was outfitted with landing legs and grid-fins in an attempt for controlled reentry of the booster. The second stage was outfitted with a 43-feet-by-17-feet-in-diameter fairing that protects satellite payloads. Fifteen flights took  between 2013 and 2016 with only one failure on the 14th flight due to an overpressure event destroying the vehicle upon ascent. The first stage attempted four soft-touch-down ocean landings and three drone ship landings. SpaceX succeeded in three of the four soft ocean landings and none of the drone ship landings. The Falcon 9 was able to demonstrate control during the descent to the drone ship, however, mechanical problems would result in all three landing failures.
        </p>
          </div>
    </div>
        <div class="text-wrapper row-reverse">
        <div class="project-card">
      <img src="https://i.postimg.cc/sX4Dgqk6/303-3037849-falcon-heavy-booster-landing.jpg" alt="Twin Booster Landings at Pad 39A after Falcon Heavy's Maiden Flight on Feburary 6th, 2018"/>
      <div class="project-desc">
        <p>Twin Booster Landings at Pad 39A after Falcon Heavy's Maiden Flight on Feburary 6th, 2018</p>
        <a href="https://youtu.be/wbSwFU6tY1c?t=1304"target="_blank"class="view-project-button"> Test Flight Video </a>
      </div>
    </div>
      <div class="image-text">
          <h3>V1.2 | 2014 - 2021</h3>
          <p>The Falcon 9 V1.2, also known as Full Thrust, was the final phase in the development for the Falcon 9 Program. Developed from 2014 to 2015 and flying from 2015 to 2021, Falcon 9 V1.2 as been the most successful Falcon 9 phase. Later variations to the design would come phases 4 and 5, however, the design as mostly stayed the same. V1.2 was increased in height to 233 ft, with a bigger fairing. The improved Merlin 1D engines offered a 33% increase in performance, allowing for 1.7 million pounds of thrust for the first stage and 210,000 pounds of thrust from the second-stage MVAC. The V1.2 is capable of 34,400 pounds to LEO or 8,860 pounds to Mars. Block 4 and 5 upgrades allowed for performance upgrades and weight reduction. On December 22nd, 2015, V1.2 became the first orbital-class booster to land on solid ground after a launch. Two flights later, on April 8th, 2016, V1.2 booster B1021.1 successfully landed on an automonius drone ship at sea for the first time in history. On March 30th, the following year, it successfully landed again, also making it the first booster to land successfully, after previously being reused. Falcon 9 succeeded in 103 of 103 flights, with 82 out of 88 successful landings. AMOS-6, on September 1st, 2016, was the only Falcon 9 to blow up on launch pad. The problem was due to a COPV failure in the first stage and was quickly fixed.  
        </p>
          </div>
    </div>
        <div class="text-wrapper">
        <div class="project-card">
      <img src="https://i.postimg.cc/ZnrwvFb5/falcon-9-bloopers.jpg" alt="'How Not to Land an Orbital Rocket Booster' video by SpaceX"/>
      <div class="project-desc">
        <p>"How Not to Land an Orbital Rocket Booster" video by SpaceX showing the development proccess of Falcon 9</p>
        <a href="https://www.youtube.com/watch?v=bvim4rsNHkQ"target="_blank"class="view-project-button"> Space Bloopers </a>
      </div>
    </div>
      <div class="image-text">
          <h3>Falcon Heavy | 2003 - 2021</h3>
          <p>The Falcon Heavy is a partially reusable heavy-lift launch vehicle with the highest payload capacity of any operational rocket. The rocket is the 3rd highest capacity rocket to ever reach orbit, behind the Saturn V and Energia. The rocket itself is composed of two side boosters and one core stage, all of which are reusable via self landing capabilities. The idea originated as far back as 2003, during the development of Falcon 1. Strapping together 3 Falcon 1's (or later Falcaon 9's) could provide heavy-lift launch capabilities while allowing for the same reuseability that was intended for the Falcon 9. Falcon Heavy is powered by 27 Merlin 1D engines with a total of 5 million pounds of thrust, followed by an MVAC second stage. Falcon Heavy is capable of 141,000 pounds to LEO, 59,0000 pounds to GTO, 37,000 pounds to Mars or 7,700 pounds to Pluto. Standing 230 feet high and 40 feet wide, it weighs a staggering 3,130,000 pounds. Falcon Heavy has preformed three flights from 2018 to 2021, all of which were successful, with 6 out of 6 booster recovered. 1 out of the 3 core stages have successfully landed.   </p>
          </div>
    </div>
        <div class="text-wrapper row-reverse">
        <div class="project-card large-card">
      <img src="https://i.postimg.cc/Y022G8kp/Falcon-Family-RK2019.png" alt="Height Comparison of Falcon 1 through 9"/>
      <div class="project-desc">
        <p>Height Comparison of Falcon 1 through 9. Grasshopper and 9R were used to test landing capabilities.</p>
        <a href="https://www.youtube.com/watch?v=ANv5UfZsvZQ"target="_blank"class="view-project-button">First Booster Landing Video</a>
      </div>
    </div>
        </div>
      </section>
      <section class="quote-section" id="space-quote">
        <h2>There's a silly notion that failure's not an option at NASA. Failure is an option here. If things are not failing, you are not innovating enough.</h2>
        <p class="quote-person">- Elon Musk, <time datatime="8-30-2020">2005, Falcon 1 Development</time><a class="twitter-logo" target="_blank"href="https://twitter.com/SciGuySpace/status/1151435587771097089?s=20"><i class="fab fa-twitter"></i></a>
        </p>
      </section>
    </main>
    <footer>
      <h4>Tribute Page Project for freeCodeCamp Responsive Web Design Certification</h4>
      <hr class="responsive-hr">
      <p>Built and Designed by Anonymous</p>
      <p>Special Thanks to freecodecamp for this amazing idea!</p>
      <div class="social-media-links-container">
        <a target="_blank" href="https://codepen.io/maxunspecified" class="codepen-logo"><i class="fab fa-codepen"></i></a>
        <a target="_blank" href="https://www.instagram.com/thedevarena" class="insta-logo"><i class="fab fa-instagram"></i></a>
        <a target="_blank" href="https://www.github.com/maxunspecified" class="github-logo"><i class="fab fa-github"></i></a>
      </div>
    </footer>
    </main>
  </body>
</html>

```

## CSS
```

@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500&display=swap');

:root{scroll-behavior: smooth;overflow-y: scroll; -ms-overflow-style: none;scrollbar-width: none;} 
:root::-webkit-scrollbar{display: none;} 

body {
  padding: 0;
  font-family: 'Playfair', monospace;
  margin: 0px;
}
#image{
  max-width: 100%;
}
nav {
  z-index: 9;
  height: auto;
  width: 100%;
  position: fixed;
  display: flex;
  background-color: black;
}
nav > ul {
  width: 100%;
  display: flex;
  flex-direction: row;
  list-style-type: none;
  align-items: stretch;
  margin: 0;
  padding: 0;
  background-color: black;
}

.nav-pill {
  box-shadow: 2px 2px 5px black;
  margin: 0;
  padding: 15px;
  color: black;
  text-align: center;
  border: 1px solid black;
  background-color: black; 
  flex: 3 3 0;
  transition: 0.3s ease-in-out;
}

a {
  text-decoration: none;
  margin: 0 auto;
}
.nav-pill:hover {
  transform: scale(1.1);
  box-shadow: 4px 4px solid black;
  border: 1px solid white;
}
.nav-pill > a {
  color: white;
  transition: 0.3s ease-in-out;
}
.nav-pill >a:hover {
  color: white;
}
.header-image {
  background-color: black;
  width: 100%;
  height: 100vh;
  border: 1px solid black;
  /*background-image: url('https://spacenews.com/wp-content/uploads/2019/06/30934147078_d3fc6602fb_k.jpg');*/
  background-image: url('https://images.unsplash.com/photo-1517976547714-720226b864c1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80');
  background-size: cover;
  background-repeat: no-repeat;
  margin: -1px;
  background-attachment: fixed;
  display: flex;
  justify-content: left;
  align-items: center;
}
.header-image-text{
  padding: 0.5%;
  margin: 10px;
  width: auto;
}
h1,.header-image-text > h2{color: white;text-shadow: 2px 2px 5px black;}
h1{font-size: 10em;margin: 0px;}
h2{text-align: center;margin: 1% auto;}
h3{text-align: center;margin-bottom:2%;}

.header-image-text > h2 {margin: -10px 10px 0px 10px;}

.information-section {
  margin: auto;
  width: 100%;
  height: 100%;
  padding: 20px;
  font-size: 18px;
}
.responsive-hr {
  width: 15%; 
  margin: 10px auto;
  border: 2px solid black;
  box-shadow: 2px 2px 5px black;
}

.quote-section {
  width: 100%;
  height: auto;
  border: 1px solid black;
  box-shadow: 2px 2px 5px black;
  padding: 1%;
}

#early-life {background-color: white;}
#education, #spacex-section, #falcon9 {background-color: rgb(223, 223, 230);}

.quote-section {
  text-align: center;
  background-color: black;
  color: white;
}
.quote-section> h2 {
  width: 65%;
  line-height: 150%;
}

.quote-person {font-size: 120%;}
.quote-section > h2:before {content: open-quote;}
.quote-section > h2:after {content: close-quote;} 

.quote-person > a {
  color: white;
  margin-left: 0.5%;
}
.twitter-logo:hover .fa-twitter {
   transform: scale(1.2);
   text-shadow: 3px 3px 7px rgb(96, 118, 224);
}
.newspaper-logo:hover .fa-newspaper {
  transform: scale(1.2);
  text-shadow: 3px 3px 7px #F37020;
}
.codepen-logo:hover .fa-codepen {
    transform: scale(1.2);
  text-shadow: 2px 2px 5px #6d6d6d;
}
.insta-logo:hover .fa-instagram {
   transform: scale(1.2);
  text-shadow: 2px 2px 5px #6d6d6d;
}
.github-logo:hover .fa-github {
  transform: scale(1.2);
 text-shadow: 2px 2px 5px #6d6d6d;
}
.fab, .fas {transition: 0.3s ease-in-out;}
.fa-twitter {color: #1DA1F2;}
.fa-codepen {color: black;font-size: 25px;}
.fa-instagram {color: #000000;font-size: 25px;}
.fa-github{color: #000000;font-size: 25px;} 

.project-card {
  border: 1px solid black;
  margin: 2%;
  height: auto;
  box-shadow: 2px 2px 5px black;
  transition: 0.7s ease-in-out;
  width: 700px;
}

.project-card img {
  width: 100%;
  height: auto;
}

.project-desc {
  position: absolute;
  top: 0;
  left: 0;
  padding: 5%;
  background-color: black;
  color: white;
  opacity: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
  transition: 1s ease-in-out;
}
.project-card:hover .project-desc {
  opacity: 0.8;
  cursor: pointer;
}
.project-card:hover {
  box-shadow: 5px 5px 10px black;
  transform: scale(1.05);
  z-index: 1;
}
.view-project-button {
  border-radius: 5px;
  color: white;
  border: 2px solid white;
  width: relative;
  height: 40px;
  padding: 7px;
  margin: 0 auto;
  transition: 1s ease; 
}
.view-project-button:hover {
  background-color: white;
  color: black !important; 
  text-decoration: none;
}
.text-wrapper {
  display: flex;
  width: 100%;
  height: 100%;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  margin: auto;
  margin-top: 1.5%;
}
.image-text {
  width: 700px;
  text-align: justify;
  align-self: flex-start;
  height: 100%;
}

.row {flex-direction: row;}
.row-reverse {flex-direction: row-reverse;}

.large-card {width: 1050px;}
.small-card, .small-text {width: 500px;}
.small-card-wrapper{width: auto; height: auto; display: flex; flex-direction: column; align-items: center;}
.small-card-container {margin: 2% auto; width: 100%; height: auto; display: flex; flex-direction: row; justify-content: center; align-items:flex-start; flex-wrap: wrap; gap: 2%;}

footer {
  width: 100%;
  background-color:white;
  height: auto;
  padding: 2%;
  text-align: center;
}
footer > h4 {
  line-height: 130%;
}
footer > p {
  font-size: 1em;
  margin-top: 1%;
}
footer > .responsive-hr {
  margin-top: 1%;
}
.social-media-links-container {
  width: 100px;
  display:flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin: 0 auto;
}
.social-media-links-container > a {
  width: 20px;
  height: 20px;
}

img { /* Test 1 */
  max-width: 2000px; 
  display: block;
}

@media screen and (max-width: 1050px) {
  .project-card, .large-card, .small-card-wrapper, .small-card-container, .image-text {
    width: 100%;
    margin-left:0%;
    margin-right: 0%;
  }
  .quote-section> h2 {
  width: 100%;
  line-height: 150%;
}
  .responsive-hr {
  width: 50%; 
  margin: 10px auto;
  border: 2px solid black;
  box-shadow: 2px 2px 5px black;
}
}
@media screen and (max-width: 2000px) {
  .quote-section> h2 {
  width: 85%;
  line-height: 150%;
}
    .responsive-hr {
  width: 25%; 
  margin: 10px auto;
  border: 2px solid black;
  box-shadow: 2px 2px 5px black;
}
}

@media screen and (max-width: 650px) {
 .responsive-hr{
  width: 75%; 
  margin: 10px auto;
  border: 2px solid black;
  box-shadow: 2px 2px 5px black;
}
}

@media screen and (max-width: 1500px) {
  .header-image-text{
  padding: 0.5%;
  margin: 10px;
  width: auto;
}
  h1 {
    font-size: 5em;
    text-align:center;
    margin-bottom: 5%;
    line-height: 100%;
  }
.header-image-text > h2{text-align: left; color: white;text-shadow: 2px 2px 5px black;}
}

@media screen and (max-width: 1000px) {
  .header-image-text > h2 {
    text-align: center;
  }
  h2 {
    margin-bottom: 5%;
  }
}

@media screen and (max-width: 500px) {
  nav {
    display: none;
  }
}

```