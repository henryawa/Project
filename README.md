# Project
<body>
  <div class="container">
      <div class="row">
        <div class="col-sm-6">
         <img src="https://i.imgur.com/Z1iMnzk.png" class="phone">
         </div>
         <div class="col-sm-6">
           <div class="right-column text-center">
           <img src="https://i.imgur.com/ME3DYmj.png" class="instagram-logo">
             
                          <form>
               <div class="form-group">
               <input type="text" class="form-control"
               placeholder="Phone number, username or Email">       
               </div>
      
               <div class="form-group">
               <input type="password" class="form-control"
               placeholder="Password">       
               </div>
               <button type="submit" class="btn btn-primary btn-block">Log In</button>
               
             </form>
             
             <p class="or">OR</p>
             
                 <p><a href="#"><img src="https://i.imgur.com/jipx0Be.png" >Log in with Facebook</a></p>  
             <p><a href="#">Forgot passoword? </a></p>
             

             
             </div>
             <div class="right-column-login text-center">          
                 <p >Don't have an account?<a href="#"> Sign up</a></p>            
           </div>
         </div>
        
       </div>
   </div>  

  
  <footer>
    <ul>
      <li><a href="#">ABOUT</a></li>
      <li><a href="#">HELP</a></li>
      <li><a href="#">PRESS</a></li>
      <li><a href="#">API</a></li>
      <li><a href="#">JOBS</a></li>
      <li><a href="#">PRIVACY</a></li>
      <li><a href="#">TERMS</a></li>
      <li><a href="#">LOCATIONS</a></li>
      <li><a href="#">TOP ACCOUNTS</a</li>
      <li><a href="#">HASHTAGS</a></li>
      <li><a href="#">LANGUAGE</a></li>
    </ul>
  
  <p>©2020 INSTAGRAM FROM FACEBOOK</p>
 
</footer>
  
</body>







*{
   margin:0;
   padding: 0; 
}


.phone
{
  padding: 0 200px;
  height: 650px;
  float: left;
  margin: 10px;
  
}
body
{
  background-color:#fafafa!important;
}

.container
{
  margin-top:20px;
}
.right-column
{
  background: #fff;
  border: 1px solid #e6e6e6;
  width: 300px;
  margin: 10px;
  padding: 0 100px 190px 10px;
  position: absolute;
  right: 150px;
}

.instagram-logo
{
  margin: 15px auto;
}

button img
{
 height: 18px !important;
 padding: 0 8px 2px;
}
.or
{
  font-size: 13px!important;
  color: #999;
  font-weight: 600;
  text-align: center;
}
.or::before
{
  content: '';
  background: #efefef;
  display: block;
  height: 2px;
  width: 110px;
  position: relative;
  top: 11px;
}

.or::after
{
  content: '';
  background: #efefef;
  display: block;
  height: 2px;
  width: 110px;
  position: relative;
  bottom: 10px;
  left: 160px;
}
.form-group
{
  margin-bottom: 6px!important;
}
.form-control
{
  background: #fafafa!important;
  border: 1px solid #efefef!important;
  font-size: 30px!important;
}
::placeholder
{
  color: #999!important;
  font-size: 10px;
  text-indent: 10px;
}
.btn
{
  margin: 12px auto;
  padding: 2px!important;
  font-weight: 600!important;
}
.btn-primary
{
  background-color: #3897f0!important;
  border: 1px solid #3897f0!important;
   margin: 12px auto;
  padding: 2px!important;
  font-weight: 600!important;
}
.terms
{
  line-height: 18px;
  font-size: 14px;
  color: #999;
  margin: 5px 20px;
}
.right-column-login
{
  background: #fff;
  border: 1px solid #e6e6e6;
  width: 350px;
  margin: 10px;
  padding: 40px;
  position: absolute;
  bottom: -300px;
  right: 50px;
  }

.right-column-login a
{
  text-decoration: none; 
  font-color: #ffffff;
}

a
{
  text-decoration: none; 
  text-align: center;
}

ul
{
  display: flex;
}
