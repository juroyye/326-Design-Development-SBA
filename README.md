<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Testimonials Challenge</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

  <style>
     
  </style>
</head>
<body>

  <div class="container">
 
<div class="container py-5" style="transform: translateY(30px);">

  <div class="row">

    <div class="col-7" style="height: 225px;">

      <div id="testimonial-card-daniel" class="boxes colored">

        <div class="top">
 <img class="imgs" height="50px" width="50px" src="images/image-daniel.jpg"> 
        <div style="transform: translateX(10px);">
          Daniel Gifford
          <p>Verified Graduate</p>
        </div>
</div>

      <h1>I received a job offer mid-course, and the subjects I learned were current, if not more so, in the company I joined. I honestly feel I got every penny’s worth.</h1>


        <p>“I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a transition and have heard some people who had an amazing experience here. I signed up for the free intro course and found it incredibly fun! I enrolled shortly thereafter. The next 12 weeks was the best - and most grueling - time of my life. Since completing the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup.”</p>


      </div>
      
    </div>
    <div class="col-3" style="height: 225px;">

      <div id="testimonial-card-jon" class="boxes colored">

        <div class="top">
           <img class="imgs" height="50px" width="50px" src="images/image-jonathan.jpg">
        <div style="transform: translateX(10px);">
         
          Jonathan Walters
          <p>Verified Graduate</p>
        </div>
      </div>

        <h1>The team was very supportive and kept me motivated.</h1>

        <p>"I started as a total newbie with virtually no coding skills. I now work as a mobile engineer for a big company. This was one of the best investments I’ve made in myself.”</p>
       
   
      </div>
</div>
</div>
</div>


<div class="container py-5" style="transform: translateY(-30px);">
  <div class="row">
    <div class="col-3" style="height: 225px;">

      <div id="testimonial-card-jeanette" class="boxes lights">


        <div class="top">
          
          <img class="imgs" height="50px" width="50px" src="images/image-jeanette.jpg">
        <div style="transform: translateX(10px);">
          Jeanette Harmon
          <p>Verified Graduate</p>
        </div>
        </div>

        <h1>An overall wonderful and rewarding experience.</h1>

        <p>“Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living while doing something I love.”</p>
       

      </div>
      
    </div>

    <div class="col-7">


      <div id="testimonial-card-patrick" class="boxes colored">


        <div class="top"> 
          
          <img class="imgs" height="50px" width="50px" src="images/image-patrick.jpg">
        <div style="transform: translateX(10px);">
          Patrick Abrams
          <p>Verified Graduate</p>
        </div>
        </div>

        <h1>Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and learning from their experiences was easy.</h1>

        <p>“ The staff seem genuinely concerned about my progress which I find really refreshing. The program gave me the confidence necessary to be able to go out in the world and present myself as a capable junior developer. The standard is above the rest. You will get the personal attention you need from an incredible community of smart and amazing people. ”</p>
        

      </div>
</div>
</div>
</div>


</div>

<div class="lights" id="sidebar">

  <div class="top">
    
    <img class="imgs" width="50px" height="50px" src="images/image-kira.jpg">

  <div style="transform: translateX(10px);">
    Kira Whittle
    <p>Verified Graduate</p>
  </div>
  </div>

  <h1>Such a life-changing experience. Highly recommended!</h1>

  <p>“Before joining the bootcamp, I’ve never written a line of code. I needed some structure from professionals who can help me learn programming step by step. I was encouraged to enroll by a former student of theirs who can only say wonderful things about the program. The entire curriculum and staff did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial could ever have. In fact, I’ve often referred to it during interviews as an example of my developent experience. It certainly helped me land a job as a full-stack developer after receiving multiple offers. 100% recommend!”</p>
  
</div>

<style>

@import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

  body{
    background-color: #edf2f8;
  }

.boxes{
  opacity: 90%;
  border-radius: 10px;
  width: 100%;
  height: 100%;
}

#testimonial-card-daniel{
  background-color: #733fc8;
  display: flex;
  flex-direction: column;
  padding: 10px;
}

#testimonial-card-jon{
  background-color: #49556b;
  display: flex;
  flex-direction: column;
  padding: 10px;
}

#testimonial-card-jeanette{
  background-color: #fefefe;
  display: flex;
  flex-direction: column;
  padding: 10px;
}

#testimonial-card-patrick{
  background-color: #18202d;
  display: flex;
  flex-direction: column;
  padding: 10px;
}


#sidebar{
  position: absolute;
  right: 60px;
  top: 78px;
  height: px;
  width: 200px;
  border-radius: 10px;
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  padding: 10px;
}

.colored{
  color: #ffffff;
}

.colored h1{
  font-size: 13px;
  color: #ffffff;
  font-family: "Barlow Semi Condensed";
}

.colored p{
  font-size: 13px;
  opacity: 70%;
  color: #ffffff;
  font-family: "Barlow Semi Condensed";
}

.imgs{
  border-radius: 60%;
}

.lights{
  font-size: 13px;
  color: #848891;
  font-family: "Barlow Semi Condensed";
}

.lights h1{
  font-size: 13px;
}

.top{
  display: flex;

}

</style>




</body>
</html>