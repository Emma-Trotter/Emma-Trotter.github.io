# Emma-Trotter.github.io
<!DOCTYPE html>
<html lang="en">

<Head>
    <meta charset="utf-8">
    <title> Camp n Go </title>
    <link rel="icon" href="camp n go logo.png">
    <link rel="stylesheet" href="style.css">

    
</Head>

    <body>
        <header>
           <img src="Camp n Go (1).png">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="events.html">Events</a></li>
                    <li> <a href="contact.html"> Contact</a></li>
                    <li><a href="booking.html">Booking</a></li>

                
                        

                    
                </ul>
            </nav>
        </header>
    </body>


<main>
  <section>
        <h1> The future is camping, website by Emma Trotter </h1>
        <img src="https://cdn.pixabay.com/photo/2023/03/31/18/44/hiking-7890733_960_720.jpg" alt="Woman walking twords mountain" width="600" height="400" id="hp"
             >
        <p> As the humanity evolves so does the way we engage with the world around us. Camping however is one tradtion rooted in
             human passtime all over the world. We strive to keep that passtime going, as well as 
             keeping you up to date with the world as it changes.So start here and find your next adventure,
              wether that be in a tent on the side of a mountain, or a luxury cabin with the perfect view, 
              weve got a little somthing for everyone to enjoy.</p>

             <p> Through this website you will be able to start all kinds of adventures! From browsing our local events to find your next day adventure
              to booking the weekend getaway youve been saving up for we have it all. We strive to accomidate all people and intrest to the best of 
              our ability. Like the world our events and sites are always changing and updating to bring all kinds of new experiences to your door and
              to keep you on your toes for that next starting point in your life. So start looking, you just might find the hidden gem in this big world.</p>
           
    </section>

    <h2> Upcoming Events</h2>
    <div class="responsive">
      <div class="gallery">
        <a target="_blank" href="">
          <img src="https://cdn.pixabay.com/photo/2018/11/01/15/10/ride-3788373_960_720.jpg" alt="Two people riding horses" width="600" height="400">
        </a>
        <div class="desc">Enjoy an amazing trail ride through the mountain trails of the blueridge!</div>
      </div>
    </div>
    
    
    <div class="responsive">
      <div class="gallery">
        <a target="_blank" href="events.html">
          <img src="https://cdn.pixabay.com/photo/2018/10/02/16/12/nature-3719233_960_720.jpg" alt="back view of a waterfall" width="600" height="400">
        </a>
        <div class="desc">"Fall" into this amazing hike to discover some beautiful local waterfalls!</div>
      </div>
    </div>
    
    <div class="responsive">
      <div class="gallery">
        <a target="_blank" href="events.html">
          <img src="https://cdn.pixabay.com/photo/2014/07/26/06/29/flowers-402094_960_720.jpg" alt="Butterfly on a flower" width="600" height="400">
        </a>
        <div class="desc">The kids butterfly identification walk is back!</div>
      </div>
    </div>
    
    <div class="responsive">
      <div class="gallery">
        <a target="_blank" href="events.html">
          <img src="https://cdn.pixabay.com/photo/2016/11/21/16/03/campfire-1846142_960_720.jpg" alt="Pot over a fire" width="600" height="400">
        </a>
        <div class="desc">Learn to start a fire, build a shelter, and much more in the survival 101 group!</div>
      </div>
    </div>
    
    <div class="clearfix"></div>
    
    <div style="padding:6px;">

      <div class="container">
        <div style="text-align:center">
          <h3>Contact Us</h3>
          <p>Leave us a message or send us an inquire! </p>
        </div>
        <div class="row">
          <div class="column">
            <img src="https://cdn.pixabay.com/photo/2014/11/25/16/56/hands-545394_960_720.jpg" style="width:100%" alt="Hands typing on computer">
          </div>
          <div class="column">
            <form action="">
              <label for="fname">First Name</label>
              <input type="text" id="fname" name="firstname" placeholder="Your first name">
              <label for="lname">Last Name</label>
              <input type="text" id="lname" name="lastname" placeholder="Your last name">
              <label for="subject">Subject</label>
              <textarea id="subject" name="subject" placeholder="Write us here" style="height:170px"></textarea>
              <input type="submit" value="Submit">
            </form>
          </div>
        </div>
      </div>
      
  
  <style>
   h1{
    text-align: center;
  padding-bottom: 50px;
 

   
   }
   h2{
    text-align: center;
    padding-bottom: 50px;
    color: white;
  
   }
section{
    padding-bottom: 50px;
}
   section p{
    font-size: 175%;
  margin: 100px;
 padding: 50px;
  border-radius: 25px;
  background-color: #8bd491;


   }

  #hp{
float: right;
margin: 0 0 0 15px;
border-radius: 25px;



  }
  div.gallery {
  border: 1px solid #ccc;
  background-color: #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
footer{
  text-align: center;
  padding-top: 50px;
  color: white;
}

* {
  box-sizing: border-box;
}
 

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}


.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 10px;
}


.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

  </style>
 


  
  </main>
<footer>
  
    <p> &copy; 2023, Camp n Go, Griffin Ga 30224</p>
</footer>

<!DOCTYPE html>
<html lang="en">
 

<Head>
    <meta charset="utf-8">
    <title> Camp n Go </title>
    <link rel="icon" href="camp n go logo.png">
    <link rel="stylesheet" href="style.css">

    
</Head>

    <body>
        <header>
           <img src="Camp n Go (1).png">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="events.html">Events</a></li>
                    <li> <a href="contact.html"> Contact</a></li>
                    <li><a href="booking.html">Booking</a></li>

                
                        

                    
                </ul>
            </nav>
        </header>
    </body>

    <main>

        <h1> Who We Are</h1>
        <img src="https://cdn.pixabay.com/photo/2020/02/04/10/42/people-4817872_960_720.jpg" alt="People sitting in campsite" width="400" height="300">
        <p> Camp n Go was created under the foundation of keeping the outdoor experience alive. 
            As technology advances we see the population spending less time outdoors and more time on screens, we aim to change this. 
            By offering all kinds of experiences we can fit the need of even the most picky person.
            We strive to keep the outdoors alive and thriving for centuries to come, and the best way to do that is to get people engaged. 
            Getting people active outside will open windows to all kinds of possibilites, from cleaning our oceans, to waste reduction , to preserving habitats. 
            The world needs protecting and we have chosen to awnser the call. 
        </p>
        <p> 
            The best way to get people involved with problems is to make it personal for them. Issues that are personal to us are the ones we
            most often want to help. Getting people outdoors is the best way we can make it personal, to show them that this planet needs our 
            help and is worth protecting. Doing so has created a huge influx of donations and organizatonal groups striving to clean and patch 
            up this planet we live on. We at camp and go do our part by getting people outdoors and in classes that are focoused on seeing the beauty of nature
            and the balance we as people must strive to have so we can keep this world turning. The farther we as a society fall into the technological advancments
            of the world the less we see the advancments of the world around us. Just like us mother nature is always adding and taking away in a balance that 
            is always opening new doors for discovery and wonder.
        </p>
        <section>
    <p> 
        <img src="https://cdn.pixabay.com/photo/2017/08/12/17/11/roe-deer-2634729_960_720.jpg" alt="Deer standing on hill" width="400" height="300">
        Our companies founder has a huge passion for the perservation of the world we live on and wanted this brand to reflect as such. 
        Their love of wildlife started it all as a small child, always wanting to study and explore the living creature in their backyard 
        as well as the wildlife not as easily avaliable. As time went on different species started to decline or go exitenct entierly and this sturred
        somthing inside them. Learning to be conservative of the worlds natural resources was the first step in how to keep this planet spinning and beautiful 
        People however didnt seemed to be as concerned as they were, how could they not care about the very planet we lived on? It was because most 
        people wernt even as engaged witht the things of nature anymore, and that sparked the first flame of what would become camp and go. 
        Engaging people with the world around them has shown to be a tremandous asset in keeping the world clean, safe, and beautfiul for centuries to come.
    </p>
    </section>
    </main>

        <style>
h1{
    text-align: center;
}
    img{
        float: right;
        border-radius: 25px;
    }

    main p{
        font-size: 150%;
       padding: 25px;
       background-color: #8bd491;
       border-radius: 25px;
       padding: 50px;
    }
    section img{
        float: left;
        padding-right: 25px;
    }
    footer{
        text-align: center;
        color: white;
        padding-top: 50px;
    }
        </style>
    <footer>
        <p> &copy; 2023, Camp n Go, Griffin Ga 30224</p>
    </footer>
    
<!DOCTYPE html>
<html lang="en">

<Head>
    <meta charset="utf-8">
    <title> Camp n Go </title>
    <link rel="icon" href="camp n go logo.png">
    <link rel="stylesheet" href="style.css">

    
</Head>

    <body>
        <header>
           <img src="Camp n Go (1).png">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="events.html">Events</a></li>
                    <li> <a href="contact.html"> Contact</a></li>
                    <li><a href="booking.html">Booking</a></li>

                
                        

                    
                </ul>
            </nav>
        </header>
    </body>
<main>
    <h1> Events </h1>
    <h2>  Blueridge Trail Ride </h2>
    <img src="https://cdn.pixabay.com/photo/2016/12/27/22/50/riding-1935051_960_720.jpg" alt="Group of people on horseback" width="600" height="400">
    <p> Join us June 15th for a relaxing trail ride through some of the most gorgeous mountains youve ever seen. Your guide will teach you all about
        the blueridge mountains while also teaching you how to safley and properly ride a horse. This event is a two hour long ride with one break period 
        for water and pictures. Everyone 10 and up welcome, helments required for those under 18.
    </p>
    <button type="button"> Book Event </button>

    <h2> "Fall" into waterfalls </h2>
    <img src="https://cdn.pixabay.com/photo/2020/12/30/14/23/waterfall-5873630_960_720.jpg" alt="Waterfall with orange trees" width="600" height="400">
    <p> Everyones favorite fall activity is making its return! Join us this september for the annual waterfall hike, here you will see all kinds of 
        beautiful fall scenery and learn a fact or two about the creation and role of waterfalls on the planet. This is a full day trip with a stop for lunch
        at noon. Minors must be accomponied by an adult, exact dates will be announced closer to fall.
    </p>
    <button type="button"> Book Event </button>

    <h2> Butterfly identification walk </h2>
    <img src="https://cdn.pixabay.com/photo/2020/10/10/09/42/nature-5642519_960_720.jpg" alt="Butterfly on a flower" width="600" height="400">
    <p> Our most popular event by far is back! Join us May 20th for the butterfly walk, a one hour kid orenited event where we take a 
        look at some amazing butterflys and their role in the enviroment. Snacks provided, all minors under 15 must be accomponied by an adult.
    </p>
   <button type="button"> Book Event</button>

   <h2> Survival 101</h2>
   <img src="https://cdn.pixabay.com/photo/2020/03/18/08/56/sunset-4943307_960_720.jpg" alt="Man sitting by fire" width="600" height="400">
   <p> Test your survival skills in our overnight survival class where you will learn everything you need to survive a night in the woods. 
    Join your two instructors for a 1 hour hike into the woods to a remote site where you will learn to pitch a tent, build a fire, and all the other
    survival tips youd need for a night in the wild. This is a overnight trip with limited slots, everyone over the age of 16 is welcome. Minors must
    be accomponied by an adult.
   </p>
   <button type="button"> Book Event </button>
</main>
 <style>
    img{
        border-radius: 25%;
    }
    main p{
        background-color:#8bd491 ;
      font-size: 125%;
   margin-bottom: 15px;
   padding: 10px;
   border-radius: 15%;
    }
 h2{
    margin-top: 25px;
    
 }
 footer{
    color: white;
    text-align: center;
 }
h1{
    text-align: center;
}
 </style>
 <footer>
  
    <p> &copy; 2023, Camp n Go, Griffin Ga 30224</p>
</footer>

<!DOCTYPE html>
<html lang="en">

<Head>
    <meta charset="utf-8">
    <title> Camp n Go </title>
    <link rel="icon" href="camp n go logo.png">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



    
</Head>

    <body>
        <header>
           <img src="Camp n Go (1).png">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="events.html">Events</a></li>
                    <li> <a href="contact.html"> Contact</a></li>
                    <li><a href="booking.html">Booking</a></li>

                
                        

                    
                </ul>
            </nav>
        </header>
    </body>
     <main>
 <h1>  Ways to Contact</h1>
 <article>
 <p> We strive to be a company you can reach out to anytime, anywhere. Below you will find many ways to contact us, from social media links to just sending a good ol email. </p>
 </article>
<section>
    <a href="#" class="fa fa-twitter"></a>
    <a href="#" class="fa fa-instagram"></a>
    <a href="#" class="fa fa-facebook"></a>
<p> Contact us on social media!</p>
<p> Most inquires will recive a response within 1-2 buisness days, if you have not recived a response please call our helpline.</p>
</section>

<div style="padding:6px;">

    <div class="container">
      <div style="text-align:center">
        <h3>Contact Us</h3>
        <p>Leave us a message or send us an inquire! </p>
      </div>
      <div class="row">
        <div class="column">
          <img src="https://cdn.pixabay.com/photo/2014/11/25/16/56/hands-545394_960_720.jpg" style="width:100%" alt="Hands typing on computer">
        </div>
        <div class="column">
          <form action="">
            <label for="fname">First Name</label>
            <input type="text" id="fname" name="firstname" placeholder="Your first name">
            <label for="lname">Last Name</label>
            <input type="text" id="lname" name="lastname" placeholder="Your last name">
            <label for="subject">Subject</label>
            <textarea id="subject" name="subject" placeholder="Write us here" style="height:170px"></textarea>
            <input type="submit" value="Submit">
          </form>
        </div>
      </div>
    </div>
     </main>
     <footer>
  
        <p> &copy; 2023, Camp n Go, Griffin Ga 30224</p>
    </footer>
 <style>
h1{
    text-align: center;
}
 

   article p{
       
     
        text-align: center;
        font-size: 150%;
        padding: 50px
        
        
    }
    .fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  
}
.fa-instagram {

  color: white;}

  .fa-twitter {
color: white;
  }
  .fa-facebook {
color: white;
  }
  section{
    text-align: center;}
    * {
  box-sizing: border-box;
}
 

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}


.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 10px;
}


.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

  footer p{
    text-align: center;
    color: white;
    padding-top: 50px;
  }
 </style>
    
     
    <!DOCTYPE html>
<html lang="en">

<Head>
    <meta charset="utf-8">
    <title> Camp n Go </title>
    <link rel="icon" href="camp n go logo.png">
    <link rel="stylesheet" href="style.css">

    
</Head>

    <body>
        <header>
           <img src="Camp n Go (1).png">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="events.html">Events</a></li>
                    <li> <a href="contact.html"> Contact</a></li>
                    <li><a href="booking.html">Booking</a></li>

                
                        

                    
                </ul>
            </nav>
        </header>
    </body>
  
<main>
    <h1> Bookings </h1>
    <h2> Sky high site</h2>
    <img src="https://cdn.pixabay.com/photo/2017/08/04/20/04/camping-2581242_960_720.jpg" alt="Tent ontop of a mountain" width="600" height="400">
    <p> Ever wanted to camp ontop of a mountain? Well now you can! This site is a 3 hour hike or 45 minuite drive from the bottom but so worth the morning view. 
        Campsite includes a fire pit, a nearby outhouse, and a water spicket. The view of the land is sure to leave your breathless. 
    </p>
<button type="button"> Book Now </button>

<h2> Pine forest site
</h2>
<img src="https://cdn.pixabay.com/photo/2020/04/10/09/21/motorhome-5024832_960_720.jpg" alt="Tent campsite in forest" width="600" height="400">
<p> Explore the thick pine forest with this beautfiul backwoods site! With 3 camper setup sites you and the whole gang can make this a trip worth remembering. 
    Campsite includes a fire pit, water and electricity hookups, nearby bathhouse, and is only a 10 minuite drive into town. 
</p>
<button type="button"> Book Now</button>

<h2>  Silent plains site</h2>
<img src="https://cdn.pixabay.com/photo/2016/10/17/21/26/autumn-1748644_960_720.jpg" alt="teepee tents in vally" width="600" height="400">
<p> People have been buildig cabins for centuries, its no wonder we keep coming back to them. This beautfiul cabin sits in a rural vally with mountains on either side 
    to make sure you get the quiet youve been needing. This cabin is 2 bedrooms, 1 bath, with a fully functional kitchen, and is a 30 minuite drive from town. 
</p>
<button type="button"> Book Now </button>
</main>

<style> 
h2{
    margin-top: 25px;
}
img{
    border-radius: 25%;
}
Main p{
    background-color:#8bd491 ;
      font-size: 125%;
   margin-bottom: 15px;
   padding: 10px;
   border-radius: 15%;
}
footer{
    color: white;
    text-align: center;
}
h1{
    text-align: center;
}
</style>
<footer>
  
    <p> &copy; 2023, Camp n Go, Griffin Ga 30224</p>
</footer>  
