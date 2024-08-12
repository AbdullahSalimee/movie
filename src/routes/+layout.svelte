
<script>
   
</script>

<style>
 body {
    background-color: #111;
}

ul {
    list-style-type: none;
    margin-top:12px ;
    padding: 0;
    overflow: hidden;
    background-color: rgb(198, 198, 198);
}

 
li{
    float: left;
}

li:last-child {
    border-right: none;
}

li a {
    display: block;
    color: rgb(0, 0, 0);
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: large;
    width: 70px; 
    transition: width 0.5s ease; 
    overflow: hidden; 
    white-space: nowrap; 
}

li a:hover:not(.active) {
    background-color: #111;
    color: aliceblue;
    width: 200px; 
}

.active {
    background-color: red;
}

.home-link {
    float: right;
    border-right: none;
    width: 100px; 
    transition: width 0.5 ease-out ;
}

.home-link a:hover{
    float: right;
    border-right: none;
    width: 200px; 
    transition: width 0.5 ease-out ;
}





nav {
  z-index: 10; 
}
 

.end h1{

    text-align: center;
  justify-content: center;
  color: antiquewhite;
  font-size: 30px;
 display: flex;
 margin-top: 50px;
}
b{
    color: rgb(79, 17, 17);

}

p{
    color:beige;

    padding: 30px;
}

</style>
<body>
    <nav>
        <ul>
           <div class="center">
           
            <li><a href="/adventure">Adventure</a></li>
            <li><a href="/horror">Horror</a></li>
            <li><a href="/action">Action</a></li>
            <li><a href="/comedy">Comedy</a></li>
            <li><a href="/thriller">Thriller</a></li>
            <li><a href="/animated">Animated</a></li>
        </div>
            <li class="home-link"><a href="/" class="active">Home</a></li>
        </ul>
    </nav>
        
    

    </body>
    <slot>
    </slot>
    

    <div class="end">
      <h1>This website was made by  <b>MOVPIRE</b></h1>
   <p>© MOVPIRE, 2024. All Rights Reserved.

    This website was created and designed by MOPIRE. All content, including but not limited to text, images, graphics, and code, is the intellectual property of MOVPIRE and is protected by copyright laws. Unauthorized use, duplication, or distribution of any material from this site without prior written permission is strictly prohibited.
   
    This website was developed as a passion project to share MY CHANNEL with a wider audience. Every element on this site, from the design to the content, reflects hours of dedication and creative effort. By visiting this site, you acknowledge and respect the intellectual property rights vested in this work. If you wish to use any part of this site, please contact me directly for permission.
    
   </p>
   
    </div>
 
    