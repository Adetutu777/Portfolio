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
              <div class="container" style="padding-top:4rem;">
              <div class="row">
            <!-- <div class="col-md-6 wow animate_animated animate_fadeInLeft" id="pix-first"> -->
            <div class="col-md-6 animate__animated animate__fadeInLeft" id="pix-first">
              <div class="card text-white" style="background:#0e141b;">
              
                  
                <h1 class="about mt-5 pb-3">
                      Hello, I'm A Frontend Developer
                    </h1>

                    <p class="details pb-3 pt-3">
                      I am Adetutu Gbangbola, I create <br> responsive websites & web applications.
                      Innovation is  <br> my  Passion.
                    </p>
                  
                <a href="#my-contact">
                    <button class="mt-4 GIT px-4 py-2 mb-5">Get in touch</button>
                  </a>
              </div>
            </div>
            <!-- <div class="col-md-6 pt-5 wow animate_animated animate_fadeInLeft" id="text-sec"> -->
            <div class="col-md-6 pt-5 animate__animated animate__fadeInRight" id="text-sec">
              <div class="card" style="background:#0e141b;">
              
                  <img class="pix mx-auto " src="../../src/assets/img4.jpg" alt="Omooba">
              
                  
              
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
            <div class="col-md-4 animate__animated animate__bounceIn">
            <div class="text-center pb-4 mt-3">
              <img clas=" " style="width:15%" src="../../src/assets/web.svg" alt="image">
              </div>
              <div class="card text-white  border-each mb-3" style="background:none">
                <div class="card-body ">
                  <h3 class="card-title know-more">Web Development</h3>
                  <p class="card-text text-text"> Either it's a simple web app or a single web app, get it done with the latest tools and frameworks to build powerful and robust apps.</p>
                </div>
              </div>
            </div>
          
            <div class="col-md-4 animate__animated animate__bounceIn">
             <div class="text-center pb-4 mt-2">
              <img class=" " style="width:15%" src="../../src/assets/internet.svg" alt="img">
              </div>
              <div class="card text-white  border-each mb-3" style="background:none">
                <div class="card-body ">
                  <h3 class="card-title know-more">PSD to Html, Css & Js</h3>
                  <p class="card-text text-text">Turning graphic models to a pixel perfect web page. The converted web pages will be fully responsive, good to view on devices.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4 animate__animated animate__bounceIn">
             <div class="text-center pb-4 mt-4">
              <img clss="w-25 " style="width:15%" src="../../src/assets/prototype.svg" alt="Omooba">
              </div>
              <div class="card text-white  border-each mb-3" style="background:none">
                <div class="card-body ">
                  <h3 class="card-title know-more">Technical Writing</h3>
                  <p class="card-text text-text">My passion for web development has helped bring out the writing skills in me, I love to write as I learn new things while coding</p>
                </div>
              </div>
            </div>
          
          </div>
              </div>
    </section>
   
<!-- Writing -->
          <section>
                  <div class="container animate__pulse" id="writing" >       
                  <div class="myicons">
                  <span class=" pr-3 latest" style="font-size:2.1rem">Writing</span>
                  <img class="pb-2" style="max-width:1.5rem;"  src="../../src/assets/notes.svg" alt="">
                  </div>

                              <div class="row pb-5 pt-3 mb-2 text-white">
                        <div class="col-md-3 ml-2 " v-for= "data in myBlog" :key="data.id" style="border: 5px solid #192430">
                          <div class="cad about-me pb-3" >  
                          <a class="text-decoration-none" :href="data.url" target="_blank">
                          <img class="img-img w-100" stle="width:100%" :src="data.social_image" alt="image">
                          <p class="text-center text-white" stle="text-decoration: none;">  {{data.title}} </p></a>
                        </div>
                        </div>
                      </div>
                </div>
                </section>

<!-- Projects -->
                <section>
                
                <div class="container">
                <div class="myicons">
                  <span class=" pr-3 latest" style="font-size:2.1rem">Projects</span>
                  <img class="pb-2" style="max-width:1.5rem;"  src="../../src/assets/monitor.svg" alt="">
                  </div>

                <div class="row animate__animated animate__pulse">
  <div class="col-md-4 pt-2">
    <div clas="card">
    <div class="card-body">
    <a class="proj-img" href="https://cryptotokens.netlify.app/" target="_blank">
       <img class="myImg" style="border:4px solid #192430"
        src="../../src/assets/screen4.png" alt="project-image">
       <div class="middle">
        <div class="mytext">
        <h6>Top 100 cryptocurrency</h6>
        <p>A web app displaying
        the top 100 cryptocurrency coin
        </p>
        <p>Tools used: Vue.js, Bootstrap</p>
        </div>
                  </div>
                  </a>
    </div>
  </div>
  </div>

  <div class="col-md-4">
    <div clas="card">
    <div class="card-body">
    <a class="proj-img" href="https://cryptotokens.netlify.app/" target="_blank">
       <img class="myImg" style="border:4px solid #192430"
        src="../../src/assets/screen4.png" alt="project-image">
       <div class="middle">
        <div class="mytext">
        <h6>Top 100 cryptocurrency</h6>
        <p>A web app displaying
        the top 100 cryptocurrency coin
        </p>
        <p>Tools used: Vue.js, Bootstrap</p>
        </div>
                  </div>
                  </a>
    </div>
  </div>
  </div>
  <div class="col-md-4">
    <div clas="card">
    <div class="card-body">
    <a class="proj-img" href="https://cryptotokens.netlify.app/" target="_blank">
       <img class="myImg" style="border:4px solid #192430"
        src="../../src/assets/screen4.png" alt="project-image">
       <div class="middle">
        <div class="mytext">
        <h6>Top 100 cryptocurrency</h6>
        <p>A web app displaying
        the top 100 cryptocurrency coin
        </p>
        <p>Tools used: Vue.js, Bootstrap</p>
        </div>
                  </div>
                  </a>
    </div>
  </div>
  </div>

          </div>

                </div>
                </section>


<!-- About me -->
        <section>
                  <div class="container pt-5  about-me-sect" id="about-about">
                              <div class="row px-1">
                        <div class="col-md-8">
                          <div class="card about-me px-4 mb-3" stye="border:1px solid red;">
                          <h3 class="know-more mt-4 pb-4" >About Me</h3>
                      <p class="text-white pb-4 pt-0 my-details " >I am a meticulous web developer with BSc. degree in computer science with front end experience and passion for responsive website design. I am a firm believer in the mobile-first approach.</p>

                       <p class="text-white pb-4 pt-0 my-details ">I enjoy learning new things and using them to create new ideas. When am not coding you can find me listening to music, reading, Hanging out with friends or exploring nature.</p>
                          </div>
                        </div>
                        <div class="col-md-4">
                          <div class="cad about-me px-4 pt-5 pb-3 mb-3" >
                            <h3 class="know-more mt-0 pb-4">Projects and Opportunities am interested in</h3>
                    <div class="text-white my-details">
                      <p>Web development.</p>
                      <p>Technical writing.</p>
                      
                    </div>
                          </div>
                        </div>
                      </div>

                  <div class="row pt-3 pb-5 px-1" style="text-aign: justify;">
                    <div class="col-md-8 ">
                    <div class="card about-me px-4 mb-3">
                      <h5 class="know-more mt-4 pb-2">Current Location</h5>
                      <p class="location pb-3 pt-1">Lagos, Nigeria</p>
                    </div>
                    </div>

                    <div class="col-md-4">
                      <div class="px-4 py-2 mt-0 " id="aa">
                      <h5 class="know-more mt-3 pb-2 ">Favourite Tools</h5>
                      <i class="fab fa-html5 soc-icon pb-4"></i>
                      <i class="fab fa-css3 soc-icon" ></i>
                      <i class="fab fa-sass soc-icon"></i> <br>
                      <i class="fab fa-vuejs soc-icon"></i>
                      <i class="fab fa-bootstrap soc-icon"></i>
                      <i class="fab fa-js soc-icon"></i>

                    </div>
                  </div>
                  </div>
                </div>

                </section>

<section>
            <div class="container" id="my-contact">
        <div class="row pb-5 last-sec" style="padding-top:5rem;">
          <div class="col-md-6 contact-more">
          
            <div class="myicons">
                  <span class=" know-more pb-4 latest pr-3" style="font-size:1.5rem">Want to Know More</span>
                  <img class="pb-2" style="max-width:1.5rem;"  src="../../src/assets/email-me.svg" alt="">
                  
                  </div>
            <p class="text-white my-details pt-4">
            Want to know more about me? Have an <br> exciting  project that could use my help? <br> Drop me a  line and let's chat!</p>
          </div>
          <div class="col-md-6 pt-5">
            
                  <div>
                  
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
       <p class="mt-4"> Made with love <span class="text-success me-me"> <i>Adetutu</i></span> </p>
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
.pix{
width: 60%;
border-radius: 50%;
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

.details{

  font-size: 1.9rem;
  line-height: 1.4;
  
}

.details-two{
  color: rgb(245, 222, 179);
}

.latest{
  color: rgb(250, 237, 214);
    
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

}

.help-row{
padding: 2rem 0 7rem 0;
}

.myImg {

  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;

}

.middle {
    transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
    
  
  }
 

  .proj-img:hover .myImg {
    opacity: 0.3;
    background: rgba(0, 255, 255, 0.5);
    
  }
  
  .proj-img:hover .middle {
    opacity: 1;
  }
  
  .mytext {
    color: white;
    font-size: .8rem;
    
   
  }

 

.about{
color:rgb(250, 237, 214) ;
font-size: 3rem;
}

.about-me,
#aa{
   background:#0e141b; 
 border-radius: .5rem;
  
}

.my-details{
font-size: 1.5rem;
line-height: 1.5;
text-align: justify;
}

#aa{
 
  margin-top: -5rem;
 
}

.soc-icon{
  font-size: 1.5rem;
  padding: .8rem;
  color: rgb(236, 161, 22);
}

.location{
  font-size: 1.2rem;
  color: whitesmoke;
}



.know-more{
color: rgb(248, 234, 206);

}

.contact-more{
  padding-top: 8rem;
 }
 .myfooter{
  background:#2b3949

}

.myfooter p{
cursor: pointer;
}

 @media screen and (max-width: 480px) {
   #pix-first{
     order: 1;
   }

   #aa{
    
     margin-top: 1rem;
   }

   .last-sec{
     padding-top: -12rem;
     
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


 .form-inline {
	display: inline-block;
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
	color: #eb5844;
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

@media (min-width: 992px){
	.form-inline .input-group {
		width: 250px;
		margin-right: 30px;
	}
}
@media (max-width: 991px){
	.form-inline {
		display: block;
		margin-bottom: 10px;
		margin-top: 0;
	}
	.input-group {
		width: 100%;
	}
 
}
.pop-up{
border-radius: 0.3rem 1rem 0.3rem 1rem;
}

</style>

