<template>
  <div class="home">
   <div class="header" >
     <div class="container" style="padding-top: 140px">
<p style=" font-size: 27px; color: white; font-weight: 400 ">The College Situation</p>
<p style="padding-bottom: 15px; font-size: 16px; color: white; line-height: 1px; font-weight: 100 ">Connecting Students with Schools, Jobs, Oppourtunies, Housing, &  Fellow Students Abroad.</p>
<p style="font-size: 14px; color: white; line-height: 1px; font-weight: 100 ">Learn ● Explore ● Connect</p>
<br/>
<img src="@/assets/playstore.png" width="150px"> &nbsp; <img src="@/assets/appstore.png" width="150px">
<br/>
</div>
   </div>


   <div class="students">
<center><p>For students</p></center>

<div class="row  container" >
      <div class="col s12" style="font-size: 16px; ">If you are  a student looking to study Abroad (United States, Canada, United kingdom, etc), we have done all the hardwork of bringing all the resources you need together to fasten your process.</div>
      <br/><br/> <br/>
      <div style="font-size: 14px; color: grey">
      <div class="col s12 m3">
        
     <b>1.</b> Access to Housing & roommates in whatever city you want to live in
        </div>
      <div class="col s12 m3"> <b>2.</b> We can show you School & their admission Requirements</div>
       <div class="col s12 m3"><b>3.</b> Free Visa Application Tips from students who went though the process</div>
       <div class="col s12 m3"><b>4.</b> Quick facts & infos about cities & what to expect as an international Student</div>
    
       </div>
    </div>
          



          <!--row 2-->


<div class="row  container" >
  
     
      <div style="font-size: 14px; color: grey">
      <div class="col s12 m3">
        
     <b>5.</b> Access to Housing & roommates in whatever city you want to live in
        </div>
      <div class="col s12 m3"><b>6.</b> We can show you School & their admission Requirements</div>
       <div class="col s12 m3"><b>7.</b> Free Visa Application Tips from students who went though the process</div>
       <div class="col s12 m3"><b>8.</b> Quick facts & infos about cities & what to expect as an international Student</div>
    
       </div>
    </div>











   </div>



<div class="visa-agents">


<center><p>For Visa Agents</p></center><br/>

<div class="row  container" >
      <div class="col s12" style="font-size: 16px; ">If you are  a student looking to study Abroad (United States, Canada, United kingdom, etc), we have done all the hardwork of bringing all the resources you need together to fasten your process.</div>
      <br/><br/> <br/>
      <div style="font-size: 14px">
      <div class="col s12 m3">
        
     1. Access to Housing & roommates in whatever city you want to live in
        </div>
      <div class="col s12 m3">2. We can show you School & their admission Requirements</div>
       <div class="col s12 m3">3. Free Visa Application Tips from students who went though the process</div>
       <div class="col s12 m3">4. Quick facts & infos about cities & what to expect as an international Student</div>
    
       </div>
    </div>
          



          <!--row 2-->


<div class="row  container" >
  
     
      <div style="font-size: 14px">
      <div class="col s12 m3">
        
     5. Access to Housing & roommates in whatever city you want to live in
        </div>
      <div class="col s12 m3">6. We can show you School & their admission Requirements</div>
       <div class="col s12 m3">7. Free Visa Application Tips from students who went though the process</div>
       <div class="col s12 m3">8. Quick facts & infos about cities & what to expect as an international Student</div>
    
       </div>
    </div>



</div>



   <footer class="page-footer primary-color" style="height: 440px">
          <div class="container">
            <div class="row">
              <div class="col l6 s12">
                <h5 class="white-text" style="font-weight: 100">College Situation</h5>
                <p class="grey-text text-lighten-4" style="font-weight: 100">Connecting Students with Schools, Jobs, Oppourtunies, Housing, & Fellow Students Abroad.</p>
              </div>
              <div class="col l4 offset-l2 s12">
                <h5 class="white-text" style="font-weight: 100">Helpful Links</h5>
                <ul style="font-weight: 100">
                  <li><a class="grey-text text-lighten-3" href="#!">About</a></li>
                  <li><a class="grey-text text-lighten-3" href="#!">Contact</a></li>
                  <li><a class="grey-text text-lighten-3" href="#!">Support</a></li>
                  <li><a class="grey-text text-lighten-3" href="#!">Register</a></li>
                </ul>
              </div>
            </div>
          </div>
          <div class="footer-copyright">
            <div class="container">
            © 2019 All Rights Reserved
            
            </div>
          </div>
        </footer>









 
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>


<style>

.primary-color{
  background: #243665
}


.header{
height: 470px;
    width: 100%;
    background-position: center;
    background-size: cover;
    background-image:linear-gradient(rgba(42, 119, 206, 0.8),rgba(9, 49, 102, 0.8)),url(https://images.unsplash.com/photo-1503676382389-4809596d5290?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1655&q=80);
    background-attachment: fixed;
}

.students{
  margin-top: 60px;
  font-weight: 400;
  font-size: 22px;
  height: 500px
}

.visa-agents {
background: rgb(217, 252, 239);
height: 500px;
padding-top: 40px;
  font-weight: 400;
  font-size: 22px;
  
}


</style>