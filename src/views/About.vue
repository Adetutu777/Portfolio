<template>
<section class="info">

    <div id="all-div">
  <div class="container">
  <!-- Navbar -->
    <nav class="navbar navbar-expand-lg">
	<a class="navbar-brand" href="">Ade<b>tutu</b></a>  		
	<button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
		<span class="navbar-toggler-icon text-white"><img src="../../src/assets/menu2.png" alt="image"> </span>
		
	</button>
	<!-- Collection of nav links, forms, and other content for toggling -->
	<div id="navbarCollapse" class="collapse navbar-collapse justify-content-start my-nav" >
		<div class="navbar-nav">
		
			<a href="#about-about" class="nav-item nav-link text-white">About</a>			
			<a href="#help-with" class="nav-item nav-link text-white">Services</a>			
		
			<a href="#writing" class="nav-item nav-link active ">Writing</a>
			<a href="#my-contact" class="nav-item nav-link text-white">Contact</a>
			<a href="https://drive.google.com/file/d/1tgCg4BmJDDLzrvPiQHGZMjGwZ5drJ4i6/view?usp=sharing" target="_blank" class="nav-item nav-link text-white">Resume</a>
        </div>
		<div class="navbar-nav ml-auto social ">
      <div class="all-soc my-soc-nav mt-2 text-center">
			<a href="https://www.linkedin.com/in/adetutu-gbangbola-05a48070/" class="nav-item nav-link soc-link"><i class="fab fa-linkedin pr-3 ">
      </i></a>
			<a href="https://github.com/Adetutu777" class="nav-item nav-link soc-link"><i class="fa fa-github pr-3"></i></a>
			<a href="https://twitter.com/adetutu2222" class="nav-item nav-link soc-link"><i class="fa fa-twitter"></i></a>
        </div>
        </div>		
	</div>
</nav>
  <router-view/>
  
  <!-- Bio -->
  <section>
              <div class="container contain-all">
              <div class="row">
            <!-- <div class="col-md-6  animate__animated animate__fadeInLeft" id="pix-first"> -->
            <div class="col-md-6 cola pt-4  animate__animated animate__fadeInLeft" id="pix-first">
              <div class="card text-white col-one">
                <h1 class="about mt-5 pb-3">
                      Hi, I'm Adetutu, a Frontend Developer
                    <span class="dot-dot">.</span>
                    </h1>
                    <p class="details pb-3 pt-3">
                      I am a creative individual with passion for technology.  Providing solution to real life problems gives me Joy. 
                    </p>
                <a href="#my-contact">
                    <button class="mt-3 GIT px-4 py-2 mb-3">Get in touch</button>
                  </a>
              </div>
            </div>
            
            <div class="col-md-6 coly pt-5 animate__animated animate__fadeInRight" id="text-sec">
              <div class="card card-pix">
                  <img class="pix mx-auto " src="../../src/assets/img4.jpg" alt="Adetutu">
              </div>
            </div>
          </div>
              </div>
              </section>

<!-- What i can do -->
            <section>
              <div class="container" id="help-with">
              <div class="tech-wri">
                <h2 class="know-more mb-4 can-help ">I can help you with
                </h2>
                </div>
              <div class="row help-row animate__animated animate__flash">
            <!-- <div class="col-md-4 animate__animated animate__bounceIn"> -->
             <div class="columny sec-cont  px-2 mb-r">
            <div class="text-center pb-4 mt-3">
              <img class="icon-img" src="../../src/assets/web.svg" alt="image">
              </div>
              <div class="card text-white  border-each mb-3">
                <div class="card-body ">
                  <h3 class="card-title know-more">Web Development</h3>
                  <p class="card-text text-text"> Either it's a simple web app or a single web app, get it done with the latest tools and frameworks.to build powerful and robust apps.</p>
                </div>
              </div>
            </div>
          
            <!-- <div class="col-md-4 animate__animated animate__bounceIn pt-2"> -->
             <div class="columna sec-cont px-2 mb-r">
             <div class="text-center pb-4 mt-3">
              <img class="icon-img " src="../../src/assets/internet.svg" alt="img">
              </div>
              <div class="card text-white  border-each ">
                <div class="card-body ">
                  <h3 class="card-title know-more ">PSD to Html, Css & Js</h3>
                  <p class="card-text text-text">Turning graphic models to a pixel perfect web page. The converted web pages will be fully responsive on mobile phone and large screens..</p>
                </div>
              </div>
            </div>

            <!-- <div class="col-md-4 animate__animated animate__bounceIn "> -->
             <div class="columna sec-cont px-2 " id="write">
             <div class="text-center pb-4 mt-4">
              <img class="icon-img " src="../../src/assets/prototype.svg" alt="Omooba">
              </div>
              <div class="card text-white  border-each" >
                <div class="card-body ">
                  <h3 class="card-title know-more" >Technical Writing</h3>
                  <p class="card-text text-text">My passion for web development brings out the writing skills in me, I love to pen things down as I learn new things while coding</p>
                </div>
              </div>
            </div>
          
          </div>
              </div>
    </section>

<!-- Projects -->
            <section class="pb-5">
              <div class="container" >
              <div class="myicons pb-4">
                      <span class=" pr-3 latest ">Projects</span>
                      <img class="pb-2 icon-img head-write"  src="../../src/assets/monitor.svg" alt="">
                      </div>
              <div class="row animate__animated animate__pulse">
            <!-- <div class="col-md-4 animate__animated animate__bounceIn"> -->
             <div class="columny px-2 mb-r first-cont">
             <a href="https://cryptotokens.netlify.app/" target="_blank">
            <img class="myImg"
            src="../../src/assets/screen4.png" alt="project-image">
            </a>
                      <div class="middle">
              <div class="mytext">
              <h6>Top 100 cryptocurrency</h6>
            <p>A web app displaying
            the top 100 cryptocurrency coin
            </p>
            <p>Tools used: Vue.js, Bootstrap</p>

              </div>
            </div>
            </div>
          
            <!-- <div class="col-md-4 animate__animated animate__bounceIn pt-2"> -->
             <div class="columna first-cont px-2 mb-r pt-4">
             <a href="https://adetutu777.github.io/budget-app/" target="_blank">
              <img class="myImg"
            src="../../src/assets/budgetdisp.png" alt="project-image">
            </a>
             <div class="middle">
              <div class="mytext">
              <h6>Budget app</h6>
            <p>A web app to plan your budget expenses
            </p>
            <p>Tools used: Html, BulmaCss, JavaScript</p>
              </div>
            </div>
            </div>

            <!-- <div class="col-md-4 animate__animated animate__bounceIn "> -->
             <div class="columna first-cont px-2 pt-4" id="write">
             <a href="https://adetutu777.github.io/frontend-booking-page/" target="_blank">
            <img class="myImg"
            src="../../src/assets/new.jpg" alt="project-image">
            </a>
             <div class="middle">
              <div class="mytext">
              <h6>Bookmark Landing Page</h6>
            <p>A challenge from frontend mentors
            </p>
            <p>Tools used: Html, TailwindCss, JavaScript</p>
              </div>
            </div>
            </div>   
          </div>
              </div>
    </section>              

   
<!-- Writing -->
          <section class="pt-5">
                              <div class="container animate__pulse" id="writing" >       
                              <div class="myicons">
                              <span class=" pr-3 latest">Writing</span>
                              <img class="pb-2 head-write"  src="../../src/assets/notes.svg" alt="">
                              </div>
                              <div class="row pb-5 pt-3 mb-2 text-white">
                        <!--<div class="col-md-4 ml-2 blog-des" v-for= "data in myBlog" :key="data.id"-->
                        <div class="columny px-2 mb-r" v-for= "data in myBlog" :key="data.id">
                          <div class="cad about-me pb-0" >  
                          <a class="text-decoration-none" :href="data.url" target="_blank">
                          <img class="img-img w-100" :src="data.social_image" alt="image">
                          <p class="text-center text-white size-text">  {{data.title}} </p></a>
                        </div>
                        </div>
                      </div>
                      </div>
                </section>


<!-- About me -->
        <section class="">
                  <div class="container pt-5  about-me-sect" id="about-about">
                              <div class="row px-1">
                        <div class="col-md-7">
                          <div class="card about-me px-4 mb-3">
                          <h3 class="know-more mb-4 pt-5" >About Me</h3>
                      <p class="text-white pb-4 pt-0 my-details " >I am a meticulous web developer with BSc. degree in computer science with front end experience and passion for responsive website design. I am a firm believer in the mobile-first approach.</p>
                       <p class="text-white pb-4 pt-0 my-details ">I enjoy learning new things and using them to create new ideas. When am not coding you can find me listening to music, reading, Hanging out with friends or exploring nature.</p>
                          </div>
                        </div>
                        <div class="col-md-5">
                          <div class="cad about-me px-4 pt-5 pb-3 mb-3" >
                            <h3 class="know-more" >Area of Interest</h3>
                    <div class="text-white my-details">
                      <p>Web development.</p>
                      <p>Technical writing.</p> 
                           </div>
                          </div>
                        </div>
                      </div>

                  <div class="row pt-3 pb-5 px-1 row-all">
                    <div class="col-md-7 ">
                    <div class="card about-me px-4 mb-3">
                      <h5 class="know-more mt-4 pb-2">Current Location</h5>
                      <p class="location pb-3 pt-1">Lagos, Nigeria</p>   
                    </div>
                    </div>

                    <div class="col-md-5">
                      <div class="px-4 py-2 mt-0 " id="aa">
                      <h5 class="know-more mt-3 pb-2 ">Favourite Tools</h5>
                      <i class="fab fa-html5 soc-icon first-cont pb-4">
                              <div class="middle">
                      <div class="mytext">
                      <h6 class="pt-3">Html5 </h6>
                      </div>
                          </div>
                          </i>
                      <i class="fab fa-css3 soc-icon first-cont" >
                        <div class="middle">
                      <div class="mytext">
                      <h6 class="pt-4">Css3 </h6>
                      </div>
                          </div>
                      </i>
                      <i class="fab fa-sass soc-icon first-cont">
                        <div class="middle">
                      <div class="mytext">
                      <h6 class="pt-4">Scss </h6>
                      </div>
                          </div>
                      </i> 
                      <i class="fab fa-vuejs soc-icon first-cont">
                        <div class="middle">
                      <div class="mytext">
                      <h6 class="pt-4">Vue.js </h6>
                      </div>
                          </div>
                      </i>
                      <i class="fab fa-bootstrap soc-icon first-cont">
                        <div class="middle">
                      <div class="mytext">
                      <h6 class="pt-4">Bootstrap</h6>
                      </div>
                          </div>
                      </i>
                      <i class="fab fa-js soc-icon first-cont">
                        <div class="middle">
                      <div class="mytext">
                      <h6 class="pt-4">Js </h6>
                      </div>
                          </div> 
                      </i>
                    
                    </div>
                  </div>
                  </div>
                </div>

                </section>

<section class="pt-5">
            <div class="container" id="my-contact">
        <div class="row pb-5 last-sec" >
          <div class="col-md-6 contact-more">
            <div class="myicons">
                  <span class=" know-more pb-4 latest pr-3 ">Want to Know More</span>
                  <img class="pb-2 head-write" src="../../src/assets/email-me.svg" alt="">
                  </div>
            <p class="text-white my-details pt-4">
            Want to know more about me? <br> Have an exciting  project that could use my help? <br> Drop me a  message and let's chat!</p>
          </div>
          <div class="col-md-6 pt-5"><div>
                  </div>

<!-- contact me section -->
                  <div class="my-container">
                  <div class="pop-up text-white text-center bg-info font-weight-bold p-3 mb-4"
                  v-if="mesg_show_alert" :class="mesg_alert_variant">
                  {{ mesg_alert_msg }}
                  </div>
                  <form class="contact-form" @submit.prevent= "sendEmail" >
                    <!-- <input type="hidden" data-form-email="true"> -->
                    <div class="form-group">
                      <!-- <input type="text" class="form-control" name="name" required="" placeholder="Name*" data-form-field="Name"> -->
                      <input type="text" v-model="name" class="form-control"  name="name" required="" placeholder="Name*">
                    </div>
                    <div class="form-group">
                      <input type="email"  v-model="email" class="form-control"  name="email" required="" placeholder="Email*">
                    </div>
                    <div class="form-group">
                      <textarea class="form-control" name="message" v-model="message" required placeholder="Message" rows="7"></textarea>
                    </div>
                    <div>
                      <button type="submit" :disabled="mesg_in_submission"
                       class="btn btn-lg sub-btn">Send</button>
                    </div> 

                  </form>
                  </div>
               
                </div>
              </div>
            </div>
            </section>
        </div>
        <footer class=" myfooter text-white text-center py-1">
      
       <p class="pt-3">Handcrafted by me ©️ <span class="text-success me-me"> <i>Adetutu</i></span> </p>
        </footer>
        </div>
  </section>



</template>

<script>

import { onMounted, ref } from 'vue';
import axios from 'axios'
import  emailjs  from 'emailjs-com';


export default {
  name: "About",
  
  setup() {
    // const apidata = ref(null)
    let myBlog =ref('')
    let name = ref("");
    let email = ref("");
   let message = ref("");

     let mesg_in_submission= ref( false );
     let mesg_show_alert = ref( false );
    let mesg_alert_variant= ref('pink');
    let mesg_alert_msg= ref('Sending');
       
 
    onMounted (() => {
    axios.get('https://dev.to/api/articles?username=adetutu777')
    // .then( response => console.log('hello', response.data))
    .then( response => myBlog.value = response?.data)
   .catch(error => console.log(error))
   })

    const sendEmail= (e) => {
      emailjs.sendForm('Contact_Me', 'template_l99nigo', e.target,
        'user_qqNYHHVb84i1Mh5uUtZN2',)
        .then((result) => {
            // console.log('SUCCESS!', result.status, result.text);
        }, (error) => {
            // console.log('FAILED...', error);
        });

       mesg_show_alert.value = true;
      mesg_in_submission.value = true;
      mesg_alert_variant.value = 'pink';
      mesg_alert_msg.value = 'Sending';

     mesg_alert_variant.value = 'green';
     mesg_alert_msg.value = 'Message sent, Thank you.';
      // console.log(e);
       
        name.value = '';
        email.value = '';
        message.value ='';
      
    }
      
    // console.log(myBlog)
   return { myBlog, sendEmail, name, email, message, mesg_in_submission,
    mesg_show_alert, mesg_alert_variant, mesg_alert_msg }
  }
}
  
</script>

<style scoped>

    .info{
        font-family: 'Lato', sans-serif;
        background:#0e141b;
    }
    .all-soc{
    display: flex;
    }

    .contain-all{
      padding-top:2rem;
     
    }

    .col-one,
    .col-two{
    background:#0e141b;
    }

    .dot-dot{
      font-size:3rem;
       color:White;

    }
    .icon-img{
    width:11%
    }

    .card-pix{
    background:#0e141b;
    }
    .pix{
    width: 65%;
    border-radius: 50%;
    border: 12px solid #192430;
    }

    .about-me-sect{
    margin-top: 8rem;
      background:#192430;

    }
    .sec-about{
      padding-top: 5rem;
    }
    .p-details{
      color: whitesmoke;
    }

    .details-two{
      color: rgb(245, 222, 179);
    }

    .latest{
      color: rgb(250, 237, 214);
    font-size:2.1rem;
    }

    .head-write {
        max-width:1.4rem;
    }

    .blog-des, .myImg{
      border: 5px solid #192430;
    }


      .GIT:hover{
      border: 1px solid  rgb(250, 237, 214);
      color: palegoldenrod;
      background: inherit;

      }
      .sub-btn:hover{
      border: 1px solid  rgb(250, 237, 214);
      color: palegoldenrod;
      background: inherit;

      }

      .GIT, 
      .sub-btn{
        background:  rgb(245, 222, 179);
        font-size: 1.5rem;
        text-decoration: none;
        color:#0e141b;
        font-weight: 600;
        border: 1px solid  rgb(250, 237, 214) ;
        border-radius: 0.3rem 1rem 0.3rem 1rem;
        transition: 0.5s ease;
      }
      .sub-btn{
      padding: .3rem 2.5rem .3rem 2.5rem;
      }

      .can-help{
        padding-top: 5rem;
      }

      .can-help h3{
        color: rgb(245, 222, 179);
      }

      .text-text{
      font-size: 1.3rem;
      }

      .border-each{
      border: 5px solid #192430;
      padding: 1rem;
      border-radius: 1rem;
      background:none;
      }

      .help-row{
      padding: 2rem 0 7rem 0;
      }


      .about{
      color:rgb(250, 237, 214) ;
      }

      .about-me,
      #aa{
        background:#0e141b; 
      border-radius: .5rem;
      }
      .size-text{
      font-size: 1rem;
      }

      .my-details, .details{
      font-size: 1.5rem;
      line-height: 1.5;
      }

      .first-cont{
        position: relative;
        cursor: pointer;

      }

      .sec-cont{
        cursor: pointer;
      }

    .myImg {
      opacity: 1;
      display: block;
      width: 100%;
      height: auto;
      transition: .5s ease;
      backface-visibility: hidden;

    }

    .middle{
      transition: .5s ease;
      opacity: 0;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      -ms-transform: translate(-50%, -50%);
      text-align: center;
    }

    .first-cont:hover .myImg {
      opacity: 0.3;
    }

    .first-cont:hover .middle {
      opacity: 1;
    } 
      .mytext {
      background-color: transparent;
      margin-top: 2rem;
      color: white;
      font-size: 13px;
      }


      #aa{
        margin-top: -5rem;
      }

      .soc-icon{
        font-size: 1.5rem;
        padding: .8rem;
        color: rgb(241, 202, 127);
        cursor: pointer;
      }

      .location{
        font-size: 1.2rem;
        color: whitesmoke;
      }



      .know-more{
      color: rgb(248, 234, 206);
      }

      .contact-more{
        padding-top: 6rem;
      }
      .myfooter{
        background:#2b3949

      }

      .myfooter p{
      cursor: pointer;
      }


      .navbar-header.col {
        padding: 0 !important;
      }	
      .navbar {		
        padding: 2rem 1rem 0 1rem;
        box-shadow: 0 0 4px rgba(0,0,0,.1);
      }

      .nav-link {
        margin: 0 8px;
        color: white;
        font-size: 1.1rem;
      }

      .nav-link img {
        border-radius: 50%;
        width: 36px;
        height: 36px;
        margin: -8px 0;
        float: left;
        margin-right: 10px;
      }
      .navbar .navbar-brand {
        color: rgb(129, 129, 129);
        padding-left: 0;
        font-size: 25px;
        padding-right: 50px;
        font-family: 'Raleway', sans-serif;
      }
      .navbar .navbar-brand b {
        font-weight: bold;
        color: #ec8375;
      }
      .navbar .navbar-nav a:hover, .navbar .navbar-nav a:focus {
        color: #f08373 !important;
      }

      .navbar .nav-item i {
        font-size: 18px;
        color: white;

      }
      .navbar .dropdown-item i {
        font-size: 16px;
        min-width: 22px;
      }
      .navbar .nav-item.show > a {
        background: none !important;
      }

      .navbar .navbar-form {
        margin-right: 0;
        margin-left: 0;
        border: 0;
      }

      .animate__animated{
      animation-duration: 1.5s ;
      }

      .pop-up{
      border-radius: 0.3rem 1rem 0.3rem 1rem;
      clip-path: polygon(0 0, 100% 0, 100% 100%, 0 69%);
      }

 @media screen and (max-width: 480px) {
      #aa{
        margin-top: 1rem;
      }

      .last-sec{
      padding-top:5rem;
      }
          
      .all-soc{
      display: flex;
      justify-content: center;
      }

      .social{
      margin: 0 auto;
      }

      .my-nav,
      .my-soc-nav{
      text-align: center;
      }
    }

      @media (max-width: 767px) {
          .columna,
          .columny {
              width: 100%;
          }

          #pix-first{
          order: 1;
        }
      }

@media (min-width: 768px) and (max-width: 991px) {
        .my-nav,
      .my-soc-nav{
      text-align: center;
      }

    .all-soc{
    display: flex;
    justify-content: center;
   }

    .columna {
        width: 100%;
    }
    .columny {
        width: 100%;
    }

     .cola,
    .coly{
      width: 100%;
      
    }

    .coly{
      margin-top: 3rem;
      
    
    }
    .pix{
     width: 90%;
    }

    .latest{
    font-size:2.5rem;
    }

    .size-text{
    font-size: 1.6rem;
    }

    .contact-more{
       padding-top: 3.8rem;
    }
}

@media (min-width: 992px) {
    .columny,
    .columna {
        width: 33%;
    }
}
</style>

