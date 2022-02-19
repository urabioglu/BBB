<!DOCTYPE html>
<html lang="tu">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text.css" href="style.css">
    <title>google templet ödevi </title>
    <style> 
    *{
      margin: 0;
     padding: 0;}
     section {
        position: relative;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;}
      section header{
         position: absolute; 
         top:0;
         width: 100%;
         display: flex;
         justify-content: flex-end;
         padding: 20px;}
         
      section header ul { 
        display: flex;
        justify-content: center;
        align-items: center;}

      section header ul li {
        list-style: none;
        margin-left: 30px ;}
      section header ul li a {
        color: black;
        text-decoration: none;
        font-size: 13px;}
      section header ul li button {
        background:  #4584ef;
        border: none;
        outline: none;
        padding: 8px 14px ;
        color: white;
        font-size: 14px;
        font-weight: 700;
        border-radius: 3px;
        cursor: pointer;}
      section .main{
       width: 580px ;
       display: flex;
       flex-direction: column;
       align-items: center;
       justify-content: center;
}

section .main{
    width: 580px ;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    
}
section .main .paragraf {
  margin: 0;
  padding: 0;
}
section .main .searchBox{
    position: relative;
    width: 100%;
    margin-top: 20px;

}
section .main .searchBox .search{
    width: 100%;
    padding: 13px;
    padding-left: 30px;
    padding-right: 0;
    border-radius: 30px;
    border: 1PX solid #CCC;
    outline: none;
    font-size: 16px;

}
section .main .searchBox .icons{
  position: absolute;
  top: 0;
  border: 0;
  width: 100%;
  display: flex;
  padding: 13px 15px;
  justify-content: space-between;
  align-items: center;
  pointer-events: none;

}
section .main .buttons{
  margin-top: 20px;
position: absolute;
justify-content: space-between;
}
section .main .buttons button {
  margin: 5px 72px;
  padding: 12px 20px;
  color: #555;
  font-size: 14px;
  border: none;
  cursor: pointer;
  border-radius: 10px;
  border: 1px solid transparent;
  outline: none;
  justify-content: space-around;
}
section .main .buttons button:hover{
  border: 1px solid #ccc;
}
section header ul li a:hover{
  
  text-decoration: underline;
}
section header ul li button:hover{
  text-decoration: underline;
}
section .main .searchBox .search:hover{
  background:#C3C9CA;
}
.footer{
  display: flex;
  justify-content: space-around;
  background: #79BCC7;
  width: 100%;
  top: -200px;
  border-radius: 5px;
  padding: 2px 1px;
  margin:100px;
  position:absolute;
  list-style: none;
  height: 100px;
  border: 20px;
  
  
}
.search1 li{
  margin: 10px;
  text-align: center;
  color: black;
}
.about li{
  margin: 5px;
  text-align: center;
  
}
.search2 li {
  margin: 5px ;
  text-align: center;
  padding: 1px;
  text-decoration:dashed;
  
}
.search2 button {
  background: hsl(187, 48%, 78%);
  border: 1px solid none;
  padding: 2px;
  border-radius: 6px;
}
.search1 li a:hover{
  color: black;
}
.about li a:hover{
  color: black;
}


    </style>
</head>

<body>
    <section>
      <header> 
        <ul>
         <li> <a href="https://www.google.com/gmail/"> Gmail</a></li>
         <li> <a href="https://www.google.com/search?q=images&hl=ar&tbm=isch&sxsrf=APq-WBs7t29ElHXFWWJG6P_6gOp6JfjORw%3A1645229449414&source=hp&biw=1366&bih=600&ei=iTUQYraeFvCRxc8P2IGdoAg&iflsig=AHkkrS4AAAAAYhBDmT2M5Biv-LJhaTUH3rNnHXh_-y-8&ved=0ahUKEwj2hp2nvYr2AhXwSPEDHdhAB4QQ4dUDCAY&uact=5&oq=images&gs_lcp=CgNpbWcQAzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQ6BwgjEO8DECc6BAgAEB5QAFi6N2DFSWgCcAB4AIABlAGIAecIkgEDMC44mAEAoAEBqgELZ3dzLXdpei1pbWc&sclient=img">Images</a></li>
         <li> <a href=""><img src="img/bars.png"></a></li>
         <li> <a href="https://accounts.google.com/servicelogin"><button> sign in</button> </a></li>
        </ul>
      </header>

      <div class="main">
         <img src="img/google.jpg">
         <p class="paragraf"> Search The Web Using Google</p>
         <div class="searchBox" >
           <input type="text" class=" search">
           <div class="icons">
             <div> <img src="img/search.png" alt=""></div>
             <div> <img src="img/mic.png" alt=""></div>
           </div>
         <div/>
         <div class="buttons">
           <button>Google Search </button>
           <button>I'm Feeling Lucky </button>
         </div>
         
      </div>
    </section>


    <section>
      <div class="footer">

        <div class="search1">
          <li><a href="">Specil Searches</a></li>
          <li><a href="">Stanford search </a></li>
          <li><a href="">Linux search</a></li>
          
       </div>

        <div class="about">
          <li><a href="https://support.google.com/">Help! </a></li>
          <li><a href="https://about.google/">About Google </a></li>
          <li><a href="https://company.info/">Company Info</a></li>
          <li><a href="https://www.google.com/doodles/about"> Google Logos</a></li>
        </div>
        
        <div class="search2">
          <li> Get Google </li>
          <li> updates monthly  </li>
          <input type="text" name="your e-mail " id="" value="Your e-mail" >
          <a href=""><button> Subscribe</button></a>

          
        </div>
        </div>
    </section>

</body>
</html>
