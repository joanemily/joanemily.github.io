<template>
      <div id="intro">
      <div id="body">
        <div class="container card">
          <div class="card__img"><img src="img/selfportrait.jpg" alt="selfportrait"></div>
          <div class="card__profile">
            <div class="title">
              <h1>Joan Crookston</h1>
              <p>.NET Ninja Warrior</p>
            </div>
            <div class="content">
              <small>As an artist, my mission was to add depth to everyday connections and encounters. As a programmer,
                it remains unchanged. Whether in photography or EMS, I regularly took notice of details that are often
                overlooked by others - a skill that I carried with me into my work in administration. At C.C. Supply, I
                noticed that the system for scheduling and tracking deliveries was unreliable and chaotic. I updated it
                to streamline the information and make sure that it was available to the drivers even when I wouldn't be
                there. At Western Reserve Hospital Gastroenterology, I helped implement a process that assisted
                Pharmaceutical representatives when ordering lunches and saved them over hundreds of dollars while
                preventing food waste.
                <br>
                <br>
                I have always prided myself on being clever and resourceful in working with and around systems to help
                companies save money, capture efficiencies, and eliminate confusion. Currently, I am studying .NET at
                Tech Elevator and I'm energized by the vast amount of new opportunities in the tech field that will
                allow me to reinforce my personal mission of serving others while challenging myself.</small>
            </div>
          </div>
          <div class="card__links">
            <div class="link"><a href="#"><i class="fab fa-instagram"></i></a></div>
            <div class="link"><a href="#"><i class="fab fa-github"></i></a></div>
            <div class="link"><a href="#"><i class="fab fa-linkedin"></i></a></div>
            <div class="link"><a href="#"><i class="fa fa-envelope"></i></a></div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'Intro'
}
</script>

<style>

#intro{
  padding: 0;
  margin: 20px;
  box-sizing: border-box;
  font-family: Raleway;
}
#body{
max-width: 100%;
  background: #eaeaea;
  display: flex;
  justify-content:center;
  align-items: center;
}
.container{
  max-width: 100%;
  max-height: fit-content;
  background: white;
  border-radius: 5px;
  box-shadow: 0 0 10px #ccc;
}
.card__img {
max-width: 50%;
padding: 2em;
}

.card__img img {
max-width: 100%;
}

.card__profile {
  margin: 0.5em;
  background-color: #eaeaea;
  opacity: 70%;
}

.card__profile .title {
  margin-bottom: 1em;
}

.card__profile h1 {
  font-size: 1em;
}

.card__profile p {
  margin: 1em;
  font-size: 0.5em;
}


.card__profile .content{
  padding: 0.5em;
  width: 40em/2;
  font-size: 0.9em;
}

.card__links {
  height: 18em;
  width: 40em/6;
  background: blue;
  margin-left: auto;

}

.link a{
  color: rgba(255,255,255,0.75);
  font-size: 1.6em;

}
  .card{
  display: flex;
  color: #343434;
  
    }
    
    .link:nth-child(1){
      height: 25%;
      background: #1da1f2;
    }
    .link:nth-child(2){
      height: 25%;
      background: #333;
    }
    .link:nth-child(3){
      height: 25%;
      background: #0077b5;
    }
    .link:nth-child(4){
      height: 25%;
      background: #ea4335;
    }


 .link{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 100%;
  transition: width 300ms ease;
 }

 .link:hover {
   width: 120%;
 }

@media screen and (max-width:480px){
  *{
   margin: 0 !important;
    padding: 0 !important;
    box-sizing: border-box;
  }
  .container{
    width: 40em/3;
    height:18em*2;
  }

  .card__img img {
    width: 10%;
    height: auto;
  }

  .card__profile {
    display: block;
    padding: 0;
    margin: 0;
  }

  .card__profile .title h1{
font-size: 2em;
  }

  .card__profile .title p{
    font-size: 0.8em;
      }
    
  .card__profile .subhead {
display: block;
  }    

  .card__profile .subhead small {
    font-size: 0.75em;
    display: block;
}    
    
.card__profile .subhead small:nth-child(2) {
margin-top: 0.6em;
}    

.card .content {
  width: 100%;
  padding: 0;
  margin: 1em 0 0 0;
}

.card__links {
  display: flex;
  height: auto;
  justify-content: center;
  align-items:flex-end;
  width: 40em/3;

}

.card__links a {
  font-size: 1em;
  padding: 1em;
}
  .card{
    display: flex;
    flex-direction: column;
    }
      
      
    .link:nth-child(1){
      width: 25%;
      height: 100%;
      background: #1da1f2;
    }
    .link:nth-child(2){
      width: 25%;
      height: 100%;
      background: #333;
    }
    .link:nth-child(3){
      width: 25%;
      height: 100%;
      background: #0077b5;
    }
    .link:nth-child(4){
      width: 25%;
      height: 100%;
      background: #ea4335;
    }
  }
</style>