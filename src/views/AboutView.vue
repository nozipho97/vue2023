/<template>
  <div class="about_container">
    <div class="about_contents">
      <section class="img">
        <img src="https://i.postimg.cc/SRRk1Pw0/Nozipho-Mayila-picture-1.jpg" alt="">
      </section>
      <section class="infoSection">
        <h2>About Me</h2>
        <h3>Web Developer</h3>
        <p> I am very dedicated to my work and I believe that anything you put your mind is highly possible. I started at Life Choices in September 2022 , I had no prior experience in web development. During the course I was very scared that I might not even make it but I started believing in myself more and dedicated every piece of me to my work and now I am proud to announce that I am a full stack developer.
        </p>
        <div class="personalInfo">
          <div><span>Name:</span><span>Nozipho Mayila</span></div>
          <div><span>D.O.B:</span><span>1997/03/20</span></div>
          <div><span>Languages:</span><span>English & IsiXhosa</span></div>
          <div><span>Hobbies:</span><span>Learning new languages, spending my time mostly coding and upskilling. Reading</span></div>
          <div><span>Email:</span><span>mayilanozipho@gmail.com</span></div>
          <div><span>Address:</span><span>31989 Lwesine STR, Khayelitsha.</span></div>
        </div>
        <div class="button">
          <a href="https://docs.google.com/document/d/1EWy5su53nxujjTa6Jm-63Tdk3BE28hXGV-6XGUOUtxA/edit?usp=sharing" target="_blank"><button>Download Resume</button></a>
        </div>
      </section>
    </div>
  </div>
</template>

<style scoped>
.about_container{
  width: 100%;
  padding: 50px 8%;
  overflow-x: hidden;
  
}
.about_container .about_contents{
  display: grid;
  grid-template-columns: 2fr 5fr;
  grid-gap: 70px;
  /* text-align: left; */
 
}
.about_contents .img{
  position: relative;
  min-width: 300px;
  height: 380px;
}
.img img{
  width: 100%;
  height:100%;
  object-fit: cover;
  position: relative;
  z-index: 2;
}
.about_contents .img::after{
  position: absolute;
  content: '';
  width: 100%;
  height: 100%;
  outline: 3px solid orangered;
  top: 15px;
  left:15px;
  z-index: 1;
}
.infoSection h2{
  color: orangered;
  font-size: 30px;
  text-transform: uppercase;
  display: inline-block;
  margin-bottom: 5px;
  position: relative;
  text-align: start;
}
.infoSection h2::before{
  content: '';
  position: absolute;
  width: 100%;
  height: 1px;
  top: 110%;
  left: 0;
  background-color: orangered;
}
.infoSection h2::after{
  content: '';
  position: absolute;
  width: 40%;
  height: 3px;
  top:calc(110% -1px);
  left:0px;
  background-color: orangered;
}
.infoSection h3{
  font-size: 20px;
  font-weight: 600;
  padding: 14px 0px 15px;
  text-transform: capitalize;
  letter-spacing: 1px;
}
.infoSection p{
  color:#36454F;
  font-size: 18px;
  line-height: 1.2;
  text-align:start;
  padding-bottom: 8px;
  word-wrap: break-word;
  width: fit-content;
}
.personalInfo{
  display: grid;
  grid-template-columns: 5fr 5fr;
  grid-gap:5px;
  margin-top: 14px;
  padding-bottom: 10px;
  border-bottom: 1px solid orangered;
  width: 100%;
}.personalInfo div{
  display: grid;
  grid-template-columns: 1fr 5fr;
}
.personalInfo div span{
  letter-spacing: 1px;
  color: black;
}
.infoSection button{
  min-width: 150px;
  padding: 8px 18px;
  border: 1px solid orangered;
  border-radius: 25px;
  font-size: 18px;
  background-color: orangered;
  color: white;
  letter-spacing: 1px;
  cursor: pointer;
  transition: all 0.4s;
  margin-top: 20px;
}
.infoSection button:hover{
  color: white;
}
.infoSection{
  word-wrap:break-word;
}


</style>