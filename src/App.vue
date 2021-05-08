<template>
<section class="info">
    <div id="app">
  
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-light" >
      <router-link class="navbar-brand text-white" href="#" to="/">Adetutu</router-link>
  
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent" style="border:1px solid red;">
 
    <ul class="navbar-nav mr-auto" >
    </ul>
    <form class="form-inline  my-2 my-lg-0" >
      <ul class="navbar-nav mr-auto text-white">
      <li class="nav-item active">
      <router-link class="nav-link text-white" to="/">Home</router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link text-white" to="/">About</router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link text-white" to="/">Blog</router-link>
      </li>
      <li class="nav-item text-white">
       <router-link class="nav-link text-white" to="/">Contact</router-link>
      </li>
      <li class="nav-item ">
       <router-link class="nav-link text-white" to="/">
       <i class="fab fa-linkedin "></i>
       </router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link text-white" to="/">
        <i class="fab fa-linkedin "></i>
       </router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link text-white" to="/">
         <i class="fab fa-github"></i>
       </router-link>
      </li>
      
    </ul>
    </form>
  </div>
</nav>
    </div>
  </div>
 
  <router-view/>


  <!-- Bio -->
    <div class="container" style="padding-top:4rem;">
    <div class="row">
  <div class="col-md-6" id="pix-first">
    <div class="card text-white" style="background:#0e141b;">
     
        
       <p class="about mt-5">
             Hi, I'm Adetutu, a Frontend Developer!
           </p>

           <p class="details ">
             Lorem ipsum dolor sit, amet consectetur adipisicing elit. Impedit quisquam omnis, explicabo molestias optio voluptates at perspiciatis officia numquam eaque tenetur nulla. Atque error labore repellendus. Ex possimus esse id.
           </p>
        
      <a href="">
          <button class="mt-4 GIT px-4 py-2 mb-5">Get in touch</button>
        </a>
    </div>
  </div>
  <div class="col-md-6" id="text-sec">
    <div class="card" style="background:#0e141b;">
     
         <img class="pix mx-auto pb-4" src="../img1.jpg" alt="Omooba">
       
        
     
    </div>
  </div>
</div>


    </div>

  
    <div class="container">
      <h4 class="know-more mb-5 can-help">I can help you with</h4>
      <div class="row ml-0" stle="text-align: justify;">
        <div class="col-md-4">
          <h5 class=" pt-3 know-more">Software development</h5>
        <p class="p-details">  Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam totam ipsam animi ipsa cupiditate beatae modi sint ipsum illo est?</p>
        </div>
        <div class="col-md-4">
          <h5 class=" pt-3 know-more">Software development</h5>
        <p class="p-details" style="color:whitesmoke;"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora ut, non similique provident voluptatem obcaecati earum? Fuga omnis adipisci hic.</p>
        </div>
        <div class="col-md-4">
          <h5 class=" pt-3 know-more">Software development</h5>
       <p class="p-details">  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde blanditiis explicabo doloribus distinctio laborum labore, perferendis aperiam nesciunt eligendi fuga.</p>
        </div>
      </div>

      <div class="row   ml-0" stle="text-align: justify;">
        <div class="col-md-1">

        </div>
        <div class="col-md-5">
          <h5 class=" pt-3 know-more">Software development</h5>
       <p class="p-details">  Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum placeat eveniet libero sed voluptas pariatur fugit dolores, id debitis neque?</p> 
        </div>
        <div class="col-md-5">
          <h5 class=" pt-3 know-more">Software development</h5>
        <p class="p-details">  Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore voluptatibus cumque maiores. Suscipit dolorum possimus doloribus tempora aspernatur sequi doloremque hic unde.</p>
        </div>
        <div class="col-md-1"></div>
      </div>
    </div>
    
   

  <div class="container  mb-4 ">
  <div class="row about-me-sect">
  <div class="col-md-12">
    <div clss="card">
      <h1 class=" pt-5 latest text-center">Latest Blog Post</h1>
    <div class="row text-white" v-for= "data in myBlog" :key="data.id">
      <div class="col-md-12 p-3 text-center" >
      <div class="text-white">
      <h3 class="text-white">{{data.title}}</h3>
        {{data.description}}
      </div>
      </div>
      </div>
    </div>
  </div>
  >
</div>
  </div>

         <div class="container pt-5 about-me-sect">
                    <div class="row">
              <div class="col-md-8">
                <div class="card about-me px-4 mb-3" stye="border:1px solid red;">
                 <h5 class="know-more mt-4 pb-2" >About Me</h5>
            <p class="text-white pb-3 " >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deserunt at molestiae reiciendis autem nam! Sit corrupti labore mollitia repellat, unde praesentium tempore hic expedita eum, minima repellendus aspernatur incidunt nobis nulla ea amet delectus voluptas maiores totam quisquam dignissimos. Repudiandae enim nostrum doloremque quos sequi unde. Veniam dolores, vel optio perspiciatis cupiditate hic nesciunt facere qui debitis odio fuga commodi aperiam itaque eius sapiente omnis earum eligendi voluptatibus excepturi minus quidem et culpa! Vero voluptatum corporis quaerat ut impedit doloribus ratione deleniti voluptas eos recusandae dignissimos numquam cumque obcaecati quisquam reiciendis fugit est, neque sint nesciunt hic repellat id blanditiis! Ipsam cupiditate sequi praesentium, exercitationem id ipsa consectetur labore natus adipisci, maiores harum eaque dolorum eligendi nesciunt corporis tempore! Eius assumenda dolorem, quam aperiam nostrum quis dolore officia natus expedita at iure facilis officiis ullam architecto.</p>
                </div>
              </div>
              <div class="col-md-4">
                <div class="cad about-me px-4 pt-4 pb-3 mb-3" >
                  <h5 class="know-more mt-4 pb-2">Projects and Opportunity am interested in</h5>
           <div class="text-white">
             <p>Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam, assumenda.</p>
             <p class="">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Itaque esse libero quo!</p>
           </div>
                </div>
              </div>
            </div>

        <div class="row pt-3 pb-5" style="text-aign: justify;">
          <div class="col-md-8 ">
           <div class="card about-me px-4 mb-3">
            <h5 class="know-more mt-4 pb-2">Current Location</h5>
            <p class="location pb-3 pt-1">Lagos, Nigeria</p>
          </div>
          </div>

          <div class="col-md-4">
             <div class="px-4 py-2 " id="aa">
            <h5 class="know-more mt-4 pb-2 ">Favourite Tools</h5>
            <i class="fab fa-html5 soc-icon"></i>
            <i class="fab fa-css3 soc-icon" ></i>
            <i class="fab fa-sass soc-icon"></i> <br>
            <i class="fab fa-vuejs soc-icon"></i>
            <i class="fab fa-bootstrap soc-icon"></i>
            <i class="fab fa-js soc-icon"></i>

          </div>
        </div>
        </div>
      </div>

            <div class="container">
        <div class="row pb-5" style="padding-top:5rem;">
          <div class="col-md-6 contact-more">
            <h5 class="know-more">Want to Know More</h5>
            <p class="text-white">
            What to know more about my design process? Have an <br> exciting  project that could use my help? Drop me a <br> line and let's chat!</p>
          </div>
          <div class="col-md-6 pt-5">
            
                  <div>
                  
                  </div>
                  <form >
                    <!-- <input type="hidden" data-form-email="true"> -->
                    <div class="form-group">
                      <input type="text " class="form-control" name="name" required="" placeholder="Name*" data-form-field="Name">
                    </div>
                    <div class="form-group">
                      <input type="email" class="form-control" name="email" required="" placeholder="Email*" data-form-field="Email">
                    </div>
                    <div class="form-group">
                      <input type="tel" class="form-control" name="phone" placeholder="Phone" data-form-field="Phone">
                    </div>
                    <div class="form-group">
                      <textarea class="form-control" name="message" placeholder="Message" rows="7" data-form-field="Message"></textarea>
                    </div>
                    <div>
                      <button type="submit" class="btn btn-lg sub-btn">Send</button>
                    </div>
                  </form>
               
          </div>
        </div>
      </div>
  </section>


</template>

<script>

import { onMounted, ref } from 'vue';
import axios from 'axios'

export default {
  name: "App",
  
  setup() {
    // const apidata = ref(null)
    let myBlog=ref('')
 
    onMounted (() => {
    axios.get('https://dev.to/api/articles?username=okeken')
    // .then( response => console.log('i love you', response.data))
    .then( response => myBlog.value = response?.data)
   .catch(error => console.log(error))
   })
    console.log(myBlog)
   return { myBlog }
  }
  

  
}
</script>



<style scoped>
.info{
    font-family: 'Lato', sans-serif;
    background:#0e141b;
}


#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-active .router-link-exact-active .nav-link  {
  color: #42b983;
  background: red;
  border: 1px solid red;
}

.pix{
width: 50%;
height: 10%;
border-radius: 150%;
}

.about{
 
  font-size: 2rem;
  font-weight: bold;
}
.about-me-sect{

  background:#192430;

}
.sec-about{
  padding-top: 5rem;
}
.p-details{
  color: whitesmoke;
}

.details{
 
  font-size: 1.3rem;
  line-height: 1.4;
  
}

.details-two{
  color: wheat;
}

.latest{
    color: wheat;
    
}

.GIT, 
.sub-btn{
  background: wheat;
  font-size: 1.5rem;
  text-decoration: none;
  color:#0e141b;
  font-weight: 500;
  border: 1px solid wheat;
  border-radius: 0.3rem 1rem 0.3rem 1rem;
}



.can-help{
  padding-top: 5rem;
}

.can-help h3{
  color: wheat;

}

.about-me,
#aa{
   background:#0e141b; 
 border-radius: .5rem;
  
}

#aa{
 
  margin-top: -5rem;
 
}

.soc-icon{
  font-size: 2rem;
  padding: .8rem;
  color: rgb(141, 111, 54);
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
 }
</style>

