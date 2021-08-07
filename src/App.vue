<template>
<section class="info">

    <div id="app">
  <div class="container">
    <nav class="navbar navbar-expand-lg">
	<a class="navbar-brand" href="">Ade<b>tutu</b></a>  		
	<button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
		<span class="navbar-toggler-icon text-white"><img src="../src/assets/menu2.png" alt=""></span>
	</button>
	<!-- Collection of nav links, forms, and other content for toggling -->
	<div id="navbarCollapse" class="collapse navbar-collapse justify-content-start my-nav" >
		<div class="navbar-nav">
		
			<a href="#about-about" class="nav-item nav-link text-white">About</a>			
			<a href="#help-with" class="nav-item nav-link text-white">Services</a>			
		
			<a href="#" class="nav-item nav-link active ">Blog</a>
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
              <div class="container" style="padding-top:4rem;">
              <div class="row">
            <!-- <div class="col-md-6 wow animate_animated animate_fadeInLeft" id="pix-first"> -->
            <div class="col-md-6 animate__animated animate__fadeInLeft" id="pix-first">
              <div class="card text-white" style="background:#0e141b;">
              
                  
                <h1 class="about mt-5 pb-3">
                      Hello, I'm A Frontend Developer.
                    </h1>

                    <p class="details pb-3 pt-3">
                      I am Adetutu Gbangbola, I create <br> responsive websites & web Applications.
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
              
                  <img class="pix mx-auto " src="../src/assets/img4.jpg" alt="Omooba">
              
                  
              
              </div>
            </div>
          </div>


              </div>

            
              <div class="container" id="help-with">
                <h1 class="know-more mb-4 can-help animate__animated animate__flash">I can help you with</h1>

              <div class="row help-row">
            <div class="col-md-4 animate__animated animate__bounceIn">
            <div class="text-center pb-4 mt-3">
              <img clas="w-25 " style="width:18%" src="../src/assets/web.svg" alt="Omooba">
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
              <img class=" " style="width:20%" src="../src/assets/internet.svg" alt="Omooba">
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
              <img clss="w-25 " style="width:16%" src="../src/assets/prototype.svg" alt="Omooba">
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
    
   


                  <div class="container mb-1 mt-1 animate__pulse" >
                    <h1 class=" pb-5  latest text-center">Latest Blog Post</h1>
                              <div class="row pb-5 pt-3 mb-2" style="border: 5px solid #192430">
                      
                        <div class="col-md-12">
                          <div class="cad about-me px-4 pt-4 pb-3 mb-3" >
                          
                            
                      <div class="row text-white"  v-for= "data in myBlog" :key="data.id">
                <div class="col-md-12 pt-4 pb-0 text-center" style="font-size:1.3rem" >
                <div class="text-white">
                <h3 class="text-white">{{data.title}}</h3>
                  {{data.description}}
                </div>
                </div>
                </div>
                          </div>
                        </div>
                      </div>

                
                </div>


        
                  <div class="container pt-5  about-me-sect" id="about-about">
                              <div class="row px-1">
                        <div class="col-md-8">
                          <div class="card about-me px-4 mb-3" stye="border:1px solid red;">
                          <h3 class="know-more mt-4 pb-4" >About Me</h3>
                      <p class="text-white pb-4 pt-0 my-details " >I am Adetutu Gbangbola, a confident, reliable and enthusiastic individual, with passion for software development I have a BSc. degree in Computer Science, with hands-on experience using HTML, Css, Js. to create and implement web applications.  </p>
                          </div>
                        </div>
                        <div class="col-md-4">
                          <div class="cad about-me px-4 pt-5 pb-3 mb-3" >
                            <h3 class="know-more mt-0 pb-4">Projects and Opportunities am interested in</h3>
                    <div class="text-white my-details">
                      <p>Web development.</p>
                      <p>Web development</p>
                      
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

            <div class="container" id="my-contact">
        <div class="row pb-5 last-sec" style="padding-top:5rem;">
          <div class="col-md-6 contact-more">
            <h4 class="know-more pb-4">Want to Know More</h4>
            <p class="text-white my-details">
            Want to know more about me? Have an <br> exciting  project that could use my help? <br> Drop me a  line and let's chat!</p>
          </div>
          <div class="col-md-6 pt-5">
            
                  <div>
                  
                  </div>

<!-- contact me section -->
                  <div class="my-container">
                  <div class="text-white text-center bg-info font-weight-bold p-3 mb-4"
                  v-if="reg_show_alert" :class="reg_alert_variant">
                  {{ reg_alert_msg }}
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
                      <input type="tel" class="form-control" v-model="phone" required name="phone" placeholder="Phone" data-form-field="Phone" >
                    </div>
                    <div class="form-group">
                      <textarea class="form-control" name="message" v-model="message" required placeholder="Message" rows="7"></textarea>
                    </div>
                    <div>
                      <button type="submit" :disabled="reg_in_submission"
                       class="btn btn-lg sub-btn">Send</button>
                    </div> 

                  </form>
                  </div>
               
                </div>
              </div>
            </div>
        </div>
        </div>
  </section>


</template>

<script>

import { onMounted, ref } from 'vue';
import axios from 'axios'
import  emailjs  from 'emailjs-com';


export default {
  name: "App",
  
  setup() {
    // const apidata = ref(null)
    let myBlog =ref('')
    let name = ref("");
    let email = ref("");
    let phone = ref("");
   let message = ref("");

     let reg_in_submission= ref( false );
     let reg_show_alert = ref( false );
    let reg_alert_variant= ref('pink');
    let reg_alert_msg= ref('Please wait, your account is been created.');
       
 
    onMounted (() => {
    axios.get('https://dev.to/api/articles?username=okeken')
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

       reg_show_alert.value = true;
      reg_in_submission.value = true;
      reg_alert_variant.value = 'pink';
      reg_alert_msg.value = 'Message sending.';

     reg_alert_variant.value = 'green';
      reg_alert_msg.value = 'Message sent, Thank you,';
      // console.log(e);
       
        name.value = '';
        email.value = '';
        phone.value = '';
        message.value ='';
      
    }
      
    // console.log(myBlog)
   return { myBlog, sendEmail, name, email, message, phone, reg_in_submission,
    reg_show_alert, reg_alert_variant, reg_alert_msg }
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
</style>

