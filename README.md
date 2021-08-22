<!DOCTYPE html>
 <html>
   <head>
     <style type="text/css">
     
       html{
       
       
       scroll-behavior:smooth;
       
       }
     
     body{
     
     margin:0;
     padding:0;
     box-sizing:border-box;
     font-family:sans-serif;
     
     transition:0.7s;
     
     }
     #nav_green{
       
       top:0;
       left:0;
       display:inline-block;
       position:sticky;
       background:#004a39;
       width:400px;
       height:120px;
       border-bottom:1px solid #ccc;
       z-index:10000;
       transition:0.7s;
     
     
     
     }
     
     #nav_green #nav_up{
     
     height:48%;
     width:100%;
     display:flex;
     justify-content:space-between;
     align-items:center;
     
     
     }
     #nav_green #nav_up .icon{
     
     display:flex;
     align-items:center;
     justify-content:center;
     
     }
     #nav_green #nav_up h2{
     
     color:#fff;
     padding-left:5px;
     
     
     }
     #nav_green #nav_up input{
     
     
     position:relative;
     padding:7px;
     padding-left:20px;
     color:#fff;
     border-radius:7px;
     outline:none;
     font-size:14px;
     background:#fff;
     width:200px;
     border:none;
     background:#004a39;
     
     
     
     }
    #nav_green #nav_up .icons .svg1{
     
     width:25px;
     margin-left:7px;
     position:relative;
     top:50%;
     margin-top:20px;
     cursor:pointer;
     
     }
    
     
     
     .svg2{
     
     width:25px;
     margin-left:7px;
     position:relative;
     top:50%;
     margin-top:20px;
     margin-right:20px;
     cursor:pointer;
     
     }
     #nav_down{
     
     bottom:0;
     left:0;
     width:100%;
     height:48%;
     display:flex;
     position:relative;
     align-items:center;
     justify-content:space-between;
     transition:1s;
     
     }
      #icon_camera svg{
     
     width:30px;
     height:30px;
     top:40%;
     margin-bottom:0;
     padding-bottom:0;
     position:absolute;
     
     }
     
     #icon_disc{
     
     color:#009683;
     margin-right:px;
     text-align:center;
     justify-content:center;
     margin-bottom:0;
     padding-bottom:0;
     
     }
     #icon_disc a{
     
     color:#fff;
     text-decoration:none;
     
     }
     #icon_disc:hover{
     
     
     border-bottom:2px solid #fff;
   
     
     }
     #icon_disc h2{
     
     
     font-size:18px;
     margin-bottom:5px;
     padding-bottom:6px;
     
     
     
     }
     
     #icon_statut{
     
     
     color:#009683;
     
     }
     
     #icon_statut a{
     
     color:#fff;
     text-decoration:none;
     
     }
     #icon_statut:hover{
     
     
     border-bottom:2px solid #fff;
     
     
     }
     
     #icon_statut h2{
     
     font-size:18px;
     margin-bottom:5px;
     padding-bottom:6px;
     
     }
     #icon_appel{
     
     
     color:#009683;
     
     }
     
     #icon_appel a{
     
     color:#fff;
     text-decoration:none;
     
     }
     #icon_appel:hover{
     
     
     border-bottom:2px solid #fff;
     
     
     }
     
     #icon_appel h2{
     
     font-size:18px;
     margin-bottom:5px;
     padding-bottom:6px;
     
     }
     section{
     
     
     
     display:inline-flex;
     
     
     }
     #disc{
     
     display:inline-block;
     margin-top:20px;
     
     }
    section #disc #disc_element{
     
     width:400px;
     height:75px;
     background:#fff;
     margin-bottom:2px;
     display:flex;
     
     
     
     }
     .elem1{
     
     
     margin-top:20px;
     
     
     
     }
     
     
     section #disc #disc_element:hover{
     
     
      background:#ccc;
     
     }
     section #disc #disc_element #profil{
         
         
      width:23%;
      height:100%;
      float:left;
      background:transparent;
      
      display:flex;
      align-items:center;
      justify-content:center;
      margin-right:2%;
      
     
     
     }
     section #disc #disc_element #profil img{
     
     width:70%;
     height:70%;
     border-radius:50%;
     padding:5%;
     
     float:center;
     left:10%;
     }
     
     section #disc #disc_element .contact_infos{
     
     
    
     width:80%;
     height:100%;
     float:center;
     background:transparent;
     margin-right:2%;
     display:inline-block;
     
     }
       section #disc #disc_element .contact_infos h4{
       
       font-size:17px;
       margin-bottom:0;
       margin-top:20px;
       padding-bottom:2%;
       
       
       }
     section #disc #disc_element .during_info{
     
     
    
     width:15%;
     height:100%;
     float:right;
     background:transparent;
     display:inline-block;
     justify-content:center;
     
     
     
     }
      section #disc #disc_element .during_info h4{
      
      color:green;
      font-size:13px;
      left:10px;
      position:relative;
      
      
      
      }
       section #disc #disc_element .during_info .nbr{
       
       color:#fff;
       width:30px;
       height:30px;
       left:10px;
       border-radius:50%;
       position:relative;
       background:green;
       align-items:center;
       justify-content:center;
       display:flex;
       top:-14px;
       
       
       
       }
       section #statuts{
       
       width:400px;
       height:700px;
       background:#fff;
       position:absolute;
       display:none;
       
       }
       
       
       #statuts{
       
       display:none;
       margin-top:20px;
       
       }
       section #statuts #disc_element{
       
       width:400px;
       height:75px;
       background:#fff;
       margin-bottom:2px;
       display:flex;
       margin-top:15px;
       
       
       
       }
       section #statuts #disc_element:hover{
       
       
       background:#ccc;
       
       }
       section #statuts #disc_element #profil{
       
       
       width:23%;
       height:100%;
       float:left;
       background:transparent;
       
       display:flex;
       align-items:center;
       justify-content:center;
       margin-right:2%;
       
       
       
       }
       section #statuts #disc_element #profil img{
       
       width:70%;
       height:70%;
       border-radius:50%;
       padding:5%;
       
       float:center;
       left:10%;
       }
       
       section #statuts #disc_element .contact_infos{
       
       
       
       width:80%;
       height:100%;
       float:center;
       background:transparent;
       margin-right:2%;
       display:inline-block;
       
       }
       section #statuts #disc_element .contact_infos h4{
       
       font-size:17px;
       margin-bottom:0;
       margin-top:20px;
       padding-bottom:2%;
       
       
       }
       section #statuts #disc_element .during_info{
       
       
       
       width:15%;
       height:100%;
       float:right;
       background:transparent;
       display:inline-block;
       justify-content:center;
       
       
       
       }
       section #statuts #disc_element .during_info h4{
       
       color:green;
       font-size:13px;
       left:10px;
       position:relative;
       
       
       
       }
       section #statuts #disc_element .during_info .nbr{
       
       color:#fff;
       width:30px;
       height:30px;
       left:10px;
       border-radius:50%;
       position:relative;
       background:green;
       align-items:center;
       justify-content:center;
       display:flex;
       top:-14px;
       
       
       
       }
       
       #statuts .bar{
       
       width:100%;
       height:20px;
       color:#000;
       font-size:18px;
       background:#ccc;
       opacity:0.5;
       text-align:center;
       
       
       
       
       }
       section #appel{
       
       
       width:400px;
       height:700px;
       display:none;
       position:absolute;
       margin-top:20px;
       
       
       }
       
       section #appel #disc_element{
       
       width:400px;
       height:75px;
       background:#fff;
       margin-bottom:2px;
       display:flex;
       margin-top:15px;
       
       
       
       }
        section #appel #disc_element.elem3{
        
           margin-top:;
        
        
        }
       section #appel #disc_element:hover{
       
       
       background:#ccc;
       
       }
       section #appel #disc_element #profil{
       
       
       width:23%;
       height:100%;
       float:left;
       background:transparent;
       
       display:flex;
       align-items:center;
       justify-content:center;
       margin-right:2%;
       
       
       
       }
       section #appel #disc_element #profil img{
       
       width:70%;
       height:70%;
       border-radius:50%;
       padding:5%;
       
       float:center;
       left:10%;
       }
       
       section #appel #disc_element .contact_infos{
       
       
       
       width:80%;
       height:100%;
       float:center;
       background:transparent;
       margin-right:2%;
       display:inline-block;
       
       }
       section #appel #disc_element .contact_infos h4{
       
       font-size:17px;
       margin-bottom:0;
       margin-top:20px;
       padding-bottom:2%;
       
       
       }
       section #appel #disc_element .during_info{
       
       
       
       width:15%;
       height:100%;
       float:right;
       background:transparent;
       display:inline-block;
       justify-content:center;
       
       
       
       }
       section #appel #disc_element .during_info h4{
       
       color:green;
       font-size:13px;
       left:10px;
       position:relative;
       
       
       
       }
       section #appel #disc_element .during_info .nbr{
       
       color:#fff;
       width:30px;
       height:30px;
       left:10px;
       border-radius:50%;
       position:relative;
       background:green;
       align-items:center;
       justify-content:center;
       display:flex;
       top:-14px;
       
       
       
       }
       #section_img{
       
       position:absolute;
       width:100%;
       height:100%;
       background:#000;
       z-index:100000;
       display:none;
       
       }
     </style>
   <script type="text/javascript">

  function disc(){
  
          var disc=document.getElementById("disc");
          var statuts=document.getElementById("statuts");
          var appel=document.getElementById("appel");
          disc.style.display="inline-block";
          statuts.style.display="none";
          appel.style.display="none";
          disc.style.display="block";
      
          
  
  }
  
  function statuts(){
 
      var nav_green=document.getElementById("nav_green");
      var disc=document.getElementById("disc");
      var statuts=document.getElementById("statuts");
      var appel=document.getElementById("appel");
      disc.style.display="none";
      statuts.style.display="block";
      appel.style.display="none";
      appel.style.display="none";
      nav_green.style.display="block";
      nav_green.style.position="fixed";
      nav_green.style.top="0";

  
  
  }
  
  function appel(){
  
  var disc=document.getElementById("disc");
  var statuts=document.getElementById("statuts");
  var appel=document.getElementById("appel");
  disc.style.display="none";
  statuts.style.display="none";
  appel.style.display="block";
  
  
  }
  function affich_img(){
  
  document.getElementById("section_img").style.display="block";
  
  }
   
   </script>
   
   </head>
  <body>
  <section id="section_img" >
  
  <div id="img_div" >
  
  <img>
  </div>
  
  
  </section>
  
  
  <nav id="nav_green" >
  
     <nav id="nav_up" >
       <h2>Wattsapp</h2>
       <div class="icons" >
          <input type="search"id="input"   >
          <a href="#input" > <svg class="svg1"xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M19.023,16.977c-0.513-0.488-1.004-0.997-1.367-1.384c-0.372-0.378-0.596-0.653-0.596-0.653l-2.8-1.337 C15.34,12.37,16,10.763,16,9c0-3.859-3.14-7-7-7S2,5.141,2,9s3.14,7,7,7c1.763,0,3.37-0.66,4.603-1.739l1.337,2.8 c0,0,0.275,0.224,0.653,0.596c0.387,0.363,0.896,0.854,1.384,1.367c0.494,0.506,0.988,1.012,1.358,1.392 c0.362,0.388,0.604,0.646,0.604,0.646l2.121-2.121c0,0-0.258-0.242-0.646-0.604C20.035,17.965,19.529,17.471,19.023,16.977z M9,14 c-2.757,0-5-2.243-5-5s2.243-5,5-5s5,2.243,5,5S11.757,14,9,14z"></path></svg></a>         
          <svg class="svg2" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M10 10H14V14H10zM10 4H14V8H10zM10 16H14V20H10z"></path></svg>
          
          
          
       </div>
       
     
     </nav>
     <nav id="params" ></nav>
     <nav id="nav_down" >
        
        <div id="icon_camera">
        
           <svg id="svg" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M11.999,7.377c-2.554,0-4.623,2.07-4.623,4.623c0,2.554,2.069,4.624,4.623,4.624c2.552,0,4.623-2.07,4.623-4.624 C16.622,9.447,14.551,7.377,11.999,7.377L11.999,7.377z M11.999,15.004c-1.659,0-3.004-1.345-3.004-3.003 c0-1.659,1.345-3.003,3.004-3.003s3.002,1.344,3.002,3.003C15.001,13.659,13.658,15.004,11.999,15.004L11.999,15.004z"></path><circle cx="16.806" cy="7.207" r="1.078"></circle><path d="M20.533,6.111c-0.469-1.209-1.424-2.165-2.633-2.632c-0.699-0.263-1.438-0.404-2.186-0.42 c-0.963-0.042-1.268-0.054-3.71-0.054s-2.755,0-3.71,0.054C7.548,3.074,6.809,3.215,6.11,3.479C4.9,3.946,3.945,4.902,3.477,6.111 c-0.263,0.7-0.404,1.438-0.419,2.186c-0.043,0.962-0.056,1.267-0.056,3.71c0,2.442,0,2.753,0.056,3.71 c0.015,0.748,0.156,1.486,0.419,2.187c0.469,1.208,1.424,2.164,2.634,2.632c0.696,0.272,1.435,0.426,2.185,0.45 c0.963,0.042,1.268,0.055,3.71,0.055s2.755,0,3.71-0.055c0.747-0.015,1.486-0.157,2.186-0.419c1.209-0.469,2.164-1.424,2.633-2.633 c0.263-0.7,0.404-1.438,0.419-2.186c0.043-0.962,0.056-1.267,0.056-3.71s0-2.753-0.056-3.71C20.941,7.57,20.801,6.819,20.533,6.111z M19.315,15.643c-0.007,0.576-0.111,1.147-0.311,1.688c-0.305,0.787-0.926,1.409-1.712,1.711c-0.535,0.199-1.099,0.303-1.67,0.311 c-0.95,0.044-1.218,0.055-3.654,0.055c-2.438,0-2.687,0-3.655-0.055c-0.569-0.007-1.135-0.112-1.669-0.311 c-0.789-0.301-1.414-0.923-1.719-1.711c-0.196-0.534-0.302-1.099-0.311-1.669c-0.043-0.95-0.053-1.218-0.053-3.654 c0-2.437,0-2.686,0.053-3.655c0.007-0.576,0.111-1.146,0.311-1.687c0.305-0.789,0.93-1.41,1.719-1.712 c0.534-0.198,1.1-0.303,1.669-0.311c0.951-0.043,1.218-0.055,3.655-0.055c2.437,0,2.687,0,3.654,0.055 c0.571,0.007,1.135,0.112,1.67,0.311c0.786,0.303,1.407,0.925,1.712,1.712c0.196,0.534,0.302,1.099,0.311,1.669 c0.043,0.951,0.054,1.218,0.054,3.655c0,2.436,0,2.698-0.043,3.654H19.315z"></path></svg>
           
        </div>
        <div id="icon_disc" onclick="disc()">
         
           <h2><a href="#disc" >DISC.342</a></h2>
        
        </div>
        <div id="icon_statut" onclick="statuts()" >
        
        
           <h2><a href="#statuts" >STATUT</a></h2>
        
        </div>
        <div id="icon_appel" onclick="appel()">
        
           
           <h2><a href="#appel" >APPELS</a></h2>
        
        </div>
        
     </nav>
  
  
  </nav>
  <section>
     
     <div id="disc" >
     
          <div id="disc_element"class="elem1" >
          
               <div id="profil" onclick="affich_img()" >
               
               <img src="/storage/emulated/0/site wattsapp/img/IMG_20210724_133431_397.JPG" >
               </div>
               
               <div class="contact_infos">
                   
                   <h4>Les blagues du grand toto</h4>
                   <div class="sms_recent"style="opacity:0.7">+228 923331100 le groupe est tros..</div>
               
               </div>
               
               <div class="during_info" >
                    
                    <h4>Hier</h4>
                    <div class="nbr" >3</div>
               
               
               </div>
          
          </div>
          
          <div id="disc_element"class="elem2" >
          
          
                  <div id="profil" >
          
                      <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210502-144517.png" >
                  </div>
          
                  <div class="contact_infos">
          
                       <h4>Nestor</h4>
                       <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 933731180 tu étais passé oú ???</div>
          
                  </div>
          
                  <div class="during_info" >
          
                       <h4>Hier</h4>
                       <div class="nbr" >3</div>
          
          
                  </div>
          
          
          </div>
          
          
          <div id="disc_element"class="elem3" >
          
               
               <div id="profil" >
               
                   <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210504-062706.png" >
               </div>
               
               <div class="contact_infos">
               
                   <h4>vicincia</h4>
                   <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 70365288 je t'ai dis j ai un copin</div>
               
               </div>
               
               <div class="during_info" >
               
                     <h4>Hier</h4>
                    <div class="nbr" >3</div>
               
               
               </div>
          
          
          
          
          </div>
          
          
          <div id="disc_element"class=" elem4" >
          
                 
                 <div id="profil" >
                 
                 <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210524-222906.png" >
                 </div>
                 
                 <div class="contact_infos">
                 
                 <h4>Emera</h4>
                 <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 91683100 salut 😊</div>
                 
                 </div>
                 
                 <div class="during_info" >
                 
                 <h4>Hier</h4>
                 <div class="nbr" >3</div>
                 
                 
                 </div>
          
          
          
          
          </div>
          
          
          
          <div id="disc_element"class="elem5" >
          
                 
                 <div id="profil" >
                 
                 <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210614-072623.png" >
                 </div>
                 
                 <div class="contact_infos">
                 
                 <h4>kady</h4>
                 <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 92367272 c est comment ??😍</div>
                 
                 </div>
                 
                 <div class="during_info" >
                 
                 <h4>Hier</h4>
                 <div class="nbr" >3</div>
                 
                 
                 </div>
          
          
          
          
          </div>
          
          
          
          <div id="disc_element"class="elem6" >
          
                 
                 <div id="profil" >
                 
                 <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210710-183534.png" >
                 </div>
                 
                 <div class="contact_infos">
                 
                 <h4>Les fans de jeux videos </h4>
                 <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 bonsoir ici</div>
                 
                 </div>
                 
                 <div class="during_info" >
                 
                 <h4>Hier</h4>
                 <div class="nbr" >3</div>
                 
                 
                 </div>
          
          
          
          
          </div>
          
          <div id="disc_element"class="elem7" >
          
               
               <div id="profil" >
               
               <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210711-190337.png" >
               </div>
               
               <div class="contact_infos">
               
               <h4>Deborah</h4>
               <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 tu es tros bete</div>
               
               </div>
               
               <div class="during_info" >
               
               <h4>Hier</h4>
               <div class="nbr" >3</div>
               
               
               </div>
          
          
          </div>
          
          
          <div id="disc_element"class="elem8" >
          
                
                <div id="profil" >
                
                <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210718-130338.png" >
                </div>
                
                <div class="contact_infos">
                
                <h4>Laure</h4>
                <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 93333728 hi 💕 mon coeur</div>
                
                </div>
                
                <div class="during_info" >
                
                <h4>Hier</h4>
                <div class="nbr" >3</div>
                
                
                </div>
          
          
          
          </div>
          <div id="disc_element"class="elem9" >
          
               
               <div id="profil" >
               
               <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210805-151611.png" >
               </div>
               
               <div class="contact_infos">
               
               <h4>Le dernier casino</h4>
               <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 le groupe est tros..</div>
               
               </div>
               
               <div class="during_info" >
               
               <h4>Hier</h4>
               <div class="nbr" >3</div>
               
               
               </div>
          
          
          
          </div>
          
          
          <div id="disc_element"class="elem10" >
          
              
              <div id="profil" >
              
              <img src="/storage/emulated/0/Pictures/1621077632363.jpg" >
              </div>
              
              <div class="contact_infos">
              
              <h4>LES DIX COMMANDRMENTS</h4>
              <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 le groupe est tros..</div>
              
              </div>
              
              <div class="during_info" >
              
              <h4>Hier</h4>
              <div class="nbr" >3</div>
              
              
              </div>
          
          
          </div>
          
          
          <div id="disc_element"class="elem11" >
                
                
                <div id="profil" >
                
                <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20210811-205513.png" >
                </div>
                
                <div class="contact_infos">
                
                <h4>INFOS MATH 5eme et 6eme SEMESTRE</h4>
                <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 le groupe est tros..</div>
                
                </div>
                
                <div class="during_info" >
                
                <h4>Hier</h4>
                <div class="nbr" >3</div>
                
                
                </div>
          
          
          </div>
          
          <div id="disc_element"class="elem12" >
          
                
                <div id="profil" >
                
                <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20210724-133856.png" >
                </div>
                
                <div class="contact_infos">
                
                <h4>AYELL</h4>
                <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 le groupe est tros..</div>
                
                </div>
                
                <div class="during_info" >
                
                <h4>Hier</h4>
                <div class="nbr" >3</div>
                
                
                </div>
          
          
          </div>
          
          
          <div id="disc_element"class="elem14" >
          
               
               <div id="profil" >
               
               <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20210805-114209.png" >
               </div>
               
               <div class="contact_infos">
               
               <h4>COLLABO</h4>
               <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 le groupe est tros..</div>
               
               </div>
               
               <div class="during_info" >
               
               <h4>Hier</h4>
               <div class="nbr" >3</div>
               
               
               </div>
          
          
          
          </div>
          
          
          <div id="disc_element"class="elem15" >
          
          
               
               <div id="profil" >
               
               <img src="/storage/emulated/0/Pictures/Screenshots/Screenshot_20210811-205513.png" >
               </div>
               
               <div class="contact_infos">
               
               <h4>PARCOURS MATH </h4>
               <div class="sms_recent"style="opacity:0.7;margin-top:0">+228 923331100 le groupe est tros..</div>
               
               </div>
               
               <div class="during_info" >
               
               <h4>Hier</h4>
               <div class="nbr" >3</div>
               
               
               </div>
          
          
          </div>
     
     
     
     </div>
     
     <div id="statuts" >
     
           <div id="disc_element"class="elem1" >
     
             <div id="profil" >
     
     <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210718-130338.png" >
     </div>
     
     <div class="contact_infos">
     
     <h4>Les blagues du grand toto</h4>
     <div class="sms_recent"style="opacity:0.7"></div>
     
     </div>
     
     </div>
     
     <div id="disc_element"class="" >
     
     
     <div id="profil" >
     
     <img src="/storage/emulated/0/Xender/image/Snapchat-262093968.jpg" >
     </div>
     
     <div class="contact_infos">
     
     <h4>Mon statut</h4>
     <div class="sms_recent"style="opacity:0.7;margin-top:0">à l'instant</div>
     
     </div> 
       
       
    
     
     
     
     
     
     </div>
     <div class="bar" >mises á jour</div>
     <div id="disc_element"class="elem2" >
     
     
     <div id="profil" >
     
     <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210502-144517.png" >
     </div>
     
     <div class="contact_infos">
     
     <h4>Nestor</h4>
     <div class="sms_recent"style="opacity:0.7;margin-top:0">aujourd'hui</div>
     
     </div>
     
     
     
     </div>
     
     
     <div id="disc_element"class="elem3" >
     
     
     <div id="profil" >
     
     <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210504-062706.png" >
     </div>
     
     <div class="contact_infos">
     
     <h4>vicincia</h4>
     <div class="sms_recent"style="opacity:0.7;margin-top:0">hier à 9h00</div>
     
     </div>
     
     
     
     
     
     </div>
     
     
     <div id="disc_element"class=" elem4" >
     
     
     <div id="profil" >
     
     <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210524-222906.png" >
     </div>
     
     <div class="contact_infos">
     
     <h4>Emera</h4>
     <div class="sms_recent"style="opacity:0.7;margin-top:0">il y 35 minutes</div>
     
     </div>
     
     
     
     
     
     </div>
     
     
     
     <div id="disc_element"class="elem5" >
     
     
     <div id="profil" >
     
     <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210614-072623.png" >
     </div>
     
     <div class="contact_infos">
     
     <h4>kady</h4>
     <div class="sms_recent"style="opacity:0.7;margin-top:0">03h40</div>
     
     </div>
     
     
     
     
     
     </div>
     
     
     
     
     
     </div>
     
     <div id="appel" >
     
       <div id="disc_element"class="elem3" >
       
       
       <div id="profil" >
       
       <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210504-062706.png" >
       </div>
       
       <div class="contact_infos">
       
       <h4>vicincia</h4>
       <div class="sms_recent"style="opacity:0.7;margin-top:0">il y a une minute</div>
       
       </div>
       
       
       
       
       
       </div>
       
       
       <div id="disc_element"class="elem4" >
       
       
       <div id="profil" >
       
       <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210524-222906.png" >
       </div>
       
       <div class="contact_infos">
       
       <h4>Emera</h4>
       <div class="sms_recent"style="opacity:0.7;margin-top:0">il y a une minute</div>
       
       </div>
       
       
       
       
       
       </div>
       
       
       
       <div id="disc_element"class="elem5" >
       
       
       <div id="profil" >
       
       <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210614-072623.png" >
       </div>
       
       <div class="contact_infos">
       
       <h4>kady</h4>
       <div class="sms_recent"style="opacity:0.7;margin-top:0">aujourd'hui</div>
       
       </div>
       
       
       
       
       
       </div>
       <div id="disc_element"class="elem8" >
       
       
       <div id="profil" >
       
       <img src="/storage/emulated/0/site wattsapp/img/Screenshot_20210718-130338.png" >
       </div>
       
       <div class="contact_infos">
       
       <h4>Laure</h4>
       <div class="sms_recent"style="opacity:0.7;margin-top:0"> hier</div>
       
       </div>
       
       <div class="during_info" >
       
       <h4>hier</h4>
       <div class="nbr" >3</div>
       
       
       </div>
       
       
       
       </div>
       
     
     
     
     </div>
  
  
  
  
  </section>
  
  
  
   
   
   
  
  
  
  
  
  </body>
 
 </html>
