<div class="animated-text">

          <h3>Graphic Designer</h3>
          <h3>Cyber Security Analyst</h3>
          <h3>Photography</h3>
          
        </div>
<style>


@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  scroll-behavior: smooth;
}

section{
  padding: 100px 200px;
}

.main{
  position: relative;
  width: 100%;
  min-height: 100vh;
  display: flex;
  align-items: center;
  background: url(images/business.jpg)no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;

}

.main .content{
  max-width: 800px;
}

.main .content h2{
  color: rgb(3, 3, 88);
  font-size: 2em;
  font-weight: 500;
}

.main .content h2 span{
  font-size: 2.6em;
  font-weight: 600;
}

.animated-text{
  position: relative;
  height: 70px;
  overflow: hidden;
}

.animated-text h3{
  color: #4e9eff;
  font-size: 3em;
  font-weight: 700;
  line-height: 70px;
  letter-spacing: 1px;
}

h3 {}

.animated-text h3:nth-child(1){
  animation: text-move 10s infinite;
}

h3 {}

@keyframes text-move{
  0%{
    margin-top: 0;
  }
  25%{
    margin-top: -70px;
  }
  50%{
    margin-top: -140px;
  }
  75%{
    margin-top: -70px;
  }
  100%{
    margin-top: 0;
  }
}

.btn{
  color: #fff;
  background: #3a6cf4;
  font-size: 1em;
  font-weight: 600;
  display: inline-block;
  padding: 10px 20px;
  text-transform: uppercase;
  text-decoration: none;
  letter-spacing: 1px;
  border-radius: 2px;
  margin-top: 30px;
  transition: 0.5s ease;
}

.btn:hover{
  background: #235bf6;
}

.media-icons{
  margin-top: 50px;
}

.media-icons a{
  color: #fff;
  font-size: 25px;
  margin-right: 30px;
}

header{
  z-index: 999;
  position: fixed;
  background: rgba(255, 255, 255, 0.1);
  top: 0;
  left: 0;
  width: 100%;
  padding: 15px 200px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: 0.5s ease;
}

header.sticky{
  background: #3a6cf4;
  padding: 10px 200px;
}

header .brand{
  color: #fff;
  font-size: 1.8em;
  font-weight: 700;
  text-transform: uppercase;
  text-decoration: none;
}

header .navigation{
  position: relative;
}

header .navigation a{
  color: #fff;
  font-size: 1em;
  font-weight: 500;
  text-decoration: none;
  margin-left: 30px;
}

header .navigation a:hover{
  color: #3a6cf4;
}

header.sticky .navigation a:hover{
  color: #000;
}

body{
  min-height: 110vh;
}

.title{
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.section-title{
  position: relative;
  color: #3a6cf4;
  font-size: 2.2em;
  font-weight: 800;
  margin-bottom: 60px;
}

.section-title:before{
  content: '';
  position: absolute;
  top: 56px;
  left: 50%;
  width: 140px;
  height: 4px;
  background: #3a6cf4;
  transform: translateX(-50%);
}

.section-title:after{
  content: '';
  position: absolute;
  top: 50px;
  left: 50%;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: #3a6cf4;
  transform: translateX(-50%);
}

.about .content{
  position: relative;
  width: 100%;
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}

.about .content .col-left{
  position: relative;
  width: 45%;
}

.about .content .col-right{
  position: relative;
  width: 50%;
}

.about .content .col-left .img-card{
  position: relative;
  width: 100%;
  min-height: 450px;
}

.about .content .col-left .img-card img{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
}

.about .content .col-right .content-title{
  font-size: 2em;
  font-weight: 800;
  margin-bottom: 20px;
}

.about .content .col-right .paragraph-text{
  font-size: 1em;
}

.skills{
  background: #000016;
}

.skills .content{
  position: relative;
  width: 100%;
  display: flex;
  justify-content: space-between;
  color: #fff;
  margin-top: 20px;
}

.skills .content .col-left{
  position: relative;
  width: 46%;
}

.skills .content .col-left .content-title{
  margin-bottom: 20px;
}

.skills .content .col-right{
  position: relative;
  width: 46%;
}

.skills .content .col-right .bar{
  margin-bottom: 15px;
  padding: 10px;
}

.skills .content .col-right .bar .info{
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 5px;
}

.skills .content .col-right .bar .info span{
  font-size: 18px;
  font-weight: 500;
}

.skills .content .col-right .bar .line{
  position: relative;
  width: 100%;
  height: 15px;
  background: #ccc;
  border-radius: 2px;
}

.skills .content .col-right .bar .line:before{
  content: '';
  position: absolute;
  height: 100%;
  top: 0;
  left: 0;
  border-radius: 2px;
}

.skills .content .col-right .bar .html:before{
  width: 95%;
  background: #e45126;
}

.skills .content .col-right .bar .css:before{
  width: 90%;
  background: #0c73b8;
}

.skills .content .col-right .bar .javascript:before{
  width: 80%;
  background: #e3a324;
}

.skills .content .col-right .bar .jquery:before{
  width: 80%;
  background: #30dd6d;
}

.skills .content .col-right .bar .php:before{
  width: 75%;
  background: #6d7eb8;
}

.skills .content .col-right .bar .ux:before{
  width: 75%;
  background: #31c545;
}

.services .content{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: row;
  margin-top: 20px;
}

.title p{
  font-size: 1em;
  width: 80%;
}

.services .content .card{
  background: #fff;
  width: 340px;
  margin: 10px;
  padding: 25px;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  box-shadow: 0 5px 25px rgba(1 1 1 / 15%);
  border-radius: 10px;
}

.services .content .card .service-icon{
  color: #3a6cf4;
  font-size: 8em;
  text-align: center;
  transition: transform 0.5s ease;
}

.services .content .card:hover .service-icon{
  transform: translateY(-10px);
}

.services .content .card .info{
  text-align: center;
}

.services .content .card .info h3{
  color: #3a6cf4;
  font-size: 1.2em;
  font-weight: 700;
  margin: 10px;
}






/* projects section styling */






.projects .title::after{
  width: 100%;
  display:flex ;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  content: "  projects   ";
}

.proj {
  position: relative;
  color: #3a6cf4;
  font-size: 2.2em;
  font-weight: 800;
  margin-bottom:  60px;
}

.proj::before{
  
  content: '';
  justify-content: start ;
  position: absolute;
  top: 56px;
  left: 0%;
  width: 20%;
  height: 4px;
  background: #3a6cf4;
}

.proj::after{
content: '';
position: absolute;
top: 50px;
left: 10%;
width: 15px;
height: 15px;
border-radius: 50%;
background: #3a6cf4;
transform: translate(-50%);

}

.projects .carousel .card{
  background: rgb(130, 82, 219);
  border-radius: 6px;
  padding: 25px 35px;
  text-align: center;
  overflow: hidden;
  transition: all 0.3s ease;
}




.projects .carousel .card:hover{
  background: rgb(38, 3, 99);
  color: #fff;
}
.projects .carousel .card .box{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  transition: all 0.3s ease;
}
.projects .carousel .card:hover .box{
  transform: scale(1.05);
}
.projects .carousel .card .text{
  font-size: 25px;
  font-weight: 500;
  margin: 10px 0 7px 0;
}
.projects .carousel .card img{
  height: 150px;
  width: 150px;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid crimson;
  transition: all 0.3s ease;
}
.projects .carousel .card:hover img{
  border-color: #fff;
}
.owl-dots{
  text-align: center;
  margin-top: 20px;
}
.owl-dot{
  height: 13px;
  width: 13px;
  margin: 0 5px;
  outline: none!important;
  border-radius: 50%;
  border: 2px solid crimson!important;
  transition: all 0.3s ease;
}
.owl-dot.active{
  width: 35px;
  border-radius: 14px;
}
.owl-dot.active,
.owl-dot:hover{
  background: crimson!important;
}







.work{
  background: #000016;
}

.work .content{
  display: flex;
  justify-content: center;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 20px;
}

.work .content .card{
  width: 340px;
  margin: 15px;
}

.work .content .card .card-img{
  position: relative;
  width: 100%;
  height: 260px;
  overflow: hidden;
  border-radius: 10px;
}

.work .content .card .card-img img{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
  transition: 0.5s ease;
}

.work .content .card .card-img img:hover{
  transform: scale(1.2);
}

.contact .content{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: column;
  margin-top: 20px;
}

.contact .content .row{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: row;
}

.contact .content .row .card{
  background: #fff;
  width: 240px;
  margin: 20px;
  padding: 25px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  box-shadow: 0 5px 25px rgba(1 1 1 / 15%);
  border-radius: 10px;
}

.contact .content .row .card .contact-icon{
  color: #3a6cf4;
  font-size: 4em;
  text-align: center;
  transition: transform 0.5s ease;
}

.contact .content .row .card:hover .contact-icon{
  transform: translateY(-10px);
}

.contact .content .row .card .info{
  text-align: center;
}

.contact .content .row .card .info h3{
  color: #111;
  font-size: 1.2em;
  font-weight: 700;
  margin: 10px;
}

.contact .content .row .card .info span{
  color: #666;
  font-weight: 500;
}

.contact-form{
  background: #fff;
  max-width: 600px;
  margin-top: 50px;
  padding: 50px;
  border-radius: 10px;
  box-shadow: 0 5px 25px rgba(1 1 1 / 15%);
}

.contact-form h3{
  color: #111;
  font-size: 1.6em;
  font-weight: 600;
  text-align: center;
  margin-bottom: 40px;
}

.contact-form .input-box{
  position: relative;
  width: 100%;
  margin-bottom: 20px;
}

.contact-form .input-box input,
.contact-form .input-box textarea{
  color: #111;
  width: 100%;
  padding: 10px;
  font-size: 1em;
  font-weight: 400;
  outline: none;
  border: 1px solid #111;
  border-radius: 5px;
  resize: none;
}

.contact-form .input-box .send-btn{
  color: #fff;
  background: #3a6cf4;
  display: inline-block;
  font-size: 1.1em;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 2px;
  width: 100%;
  border: none;
  cursor: pointer;
  transition: 0.5s ease;
}

.contact-form .input-box .send-btn:hover{
  background: #235bf6;
}

.footer{
  background: #000016;
  color: #fff;
  text-align: center;
  padding: 2em;
}

.footer .footer-title{
  font-size: 20px;
  font-weight: 600;
}

.footer p{
  font-size: 16px;
  margin-top: 10px;
}

.footer p a{
  color: #3a6cf4;
  font-weight: 600;
  text-decoration: none;
}

@media (max-width: 1040px){
  header{
    padding: 12px 20px;
  }

  header.sticky{
    padding: 10px 20px;
  }

  header .navigation{
    display: none;
  }

  header .navigation.active{
    z-index: 888;
    position: fixed;
    background: #fff;
    top: 0;
    right: 0;
    width: 380px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    box-shadow: 0 5px 25px rgba(1 1 1 / 15%);
    transition: 0.3s ease;
  }

  header .navigation a{
    color: #000;
    font-size: 1.2em;
    margin: 10px;
    padding: 0 20px;
    border-radius: 20px;
  }

  header .navigation a:hover{
    background: #3a6cf4;
    color: #fff;
    transition: 0.3s ease;
  }

  .menu-btn{
    position: absolute;
    background: url(images/menu.png)no-repeat;
    background-size: 30px;
    background-position: center;
    width: 40px;
    height: 40px;
    right: 0;
    margin: 0 20px;
    cursor: pointer;
    transition: 0.3s ease;
  }

  .menu-btn.active{
    z-index: 999;
    background: url(images/close.png)no-repeat;
    background-size: 25px;
    background-position: center;
    transition: 0.3s ease;
    filter: invert(1);
  }

  section{
    padding: 80px 20px;
  }

  .main .content h2{
    font-size: 1em;
  }

  .animated-text h3{
    font-size: 2.2em;
  }

  .section-title{
    font-size: 1.8em;
  }

  .about .content{
    flex-direction: column;
  }

  .about .content .column{
    position: relative;
    width: 100%;
  }

  .about .content .col-right{
    margin-top: 40px;
  }

  .skills .content{
    flex-direction: column;
  }

  .skills .content .column{
    position: relative;
    width: 100%;
  }

  .skills .content .col-right{
    margin-top: 40px;
  }

  .contact-form{
    padding: 35px 40px;
  }
}

.scrollToTop-btn{
  z-index: 999;
  position: fixed;
  background: #3a6cf4;
  color: #fff;
  width: 45px;
  height: 45px;
  right: 0;
  bottom: 10px;
  font-size: 22px;
  text-align: center;
  line-height: 45px;
  border-radius: 3px;
  cursor: pointer;
  pointer-events: none;
  opacity: 0;
  transition: all 0.3s ease;
}


}

.reveal{
  position: relative;
  transform: translateY(50px);
  opacity: 0;
  transition: all 1.5s ease;
}

.reveal.active{
  transform: translateY(0);
  opacity: 1;
}



.max-width{
 

  
}
.animated-text h3:nth-child(1) {


  animation: text-move 10s infinite;
    animation-duration: 10s;
    animation-timing-function: ease;
    animation-delay: 0s;
    animation-iteration-count: infinite;
    animation-direction: normal;
    animation-fill-mode: none;
    animation-play-state: running;
    animation-name: text-move;
    animation-timeline: auto;
    animation-range-start: normal;
  
}

    animation-range-end: normal;
}
</style>
