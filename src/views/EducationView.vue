<template>
    <H3>E D U C A T I O N</H3>
    <div class="container">
        <main class="row">
            <section class="col">
                <header class="title">
                    <h2>EDUCATION</h2>
                </header>
                <div class="contents">
                    <div class="box">
                        <h4>2014</h4>
                        <h3>Matriculated</h3>
                    </div>
                    <div class="box">
                        <h4>2015 - 2017</h4>
                        <h4>iKapa Dance Theatre</h4>
                        <h3>Choreography</h3>
                        <p>A dance school where I learnt dance and Movement Technics.</p>
                    </div>
                    <div class="box">
                        <h4>2020 - 2021</h4>
                        <h4>CTU Training Solutions</h4>
                        <h3>IT Leanership</h3>
                        <p>An IT Learnership, where I studied IT Technical Support.</p>
                    </div>
                    <div class="box">
                        <h4>2022 - 2023</h4>
                        <h4>Life Choices Coding Academy</h4>
                        <h3>Full-Stack Development</h3>
                        <p>I did a 6 months on-site Full-Stack training.</p>
                    </div>

                </div>
            </section>

            <section class="col">
                <header class="title">
                    <h2>EXPERIENCE</h2>
                </header>
                <div class="contents">
                    <div class="box">
                        <h4>iKapa Dance Theatre</h4>
                        <h3>Choreographer</h3>


                    </div>
                    <div class="box">
                        <h4>Volunteer Work</h4>
                        <h3>Danie Ackerman Primary School</h3>
                        <p>I volunteered there to teach kids to dance.</p>
                    </div>
                    <div class="box">
                        <h4>Amy Foundation</h4>
                        <h3>Hospitality and Beauty</h3>
                        <p>I did work there during holidays.</p>
                    </div>
                    <div class="box">
                        <h4>2021 Oct - 2022 June</h4>
                        <h4>ZA Online Cafe</h4>
                        <h3>Technical Support</h3>
                        <p>I worked there as an assistant.</p>
                    </div>
                </div>
            </section>
        </main>
    </div>
    <div class="inner">
        <div class="heading">
            <h2>MY SKILLS</h2>
        </div>
        <div class="container-2">
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/15X7tJbQ/html-5.png" alt="" class="skill-icon">
                        <h3>HTML</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/zvr5N4x8/css-3.png" alt="" class="skill-icon">
                        <h3>CSS</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/0Nz90Y6R/js_(1).png" alt="" class="skill-icon">
                        <h3>JAVASCRIPT</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/kg4C7Qv6/VUE.jpg" alt="" class="skill-icon">
                        <h3>VUE JS</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/8PTD0QFb/node-js.png" alt="" class="skill-icon">
                        <h3>NODE JS</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                       <img src="https://i.postimg.cc/mrKBXPMc/mysql.png" alt="" class="skill-icon">
                        <h3>MYSQL</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/2S10rG3K/wordpress.png" alt="" class="skill-icon">
                        <h3>WORDPRESS</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/CMGS7LK1/ui.png" alt="" class="skill-icon">
                        <h3>UI/UX</h3>
                    </div>
                </div>
            </div>
            <div class="skill-box">
                <div class="skill-tittle">
                    <div class="img">
                        <img src="https://i.postimg.cc/7YsKFdPz/github.png" alt="" class="skill-icon">
                        <h3>GITHUB</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    width: 100%;
    min-height: 100vh;
    background-color: #fafafa;
    display: flex;
    justify-content: center;
    align-items: center;
}
h3{
    text-align:center;
}
.container{
    width: 100%;
    padding: 35px 10%;
}
.container{
    padding-right: calc(10% - 30px);
    text-align: center;
}
main.row{
    display: grid !important;
    grid-template-columns: 1fr 1fr;
    grid-column-gap:20px;
}
.col header.title{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #36454F;
    padding: 0px 0px 20px 30px;
}
.col .contents{
    padding: 0px 30px;
    border-left: 2px solid orangered;
}
.col .contents .box{
    position: relative;
    padding: 20px;
    cursor: pointer;
    transition: all 0.4s;
    margin-bottom: 20px;
}
.col .contents .box:hover{
    box-shadow: 0px 3px 12px 0px #ccc;
    border: 1px solid transparent;
}
.col .contents .box::before{
   content: '';
   position: absolute;
   width: 16px;
   height: 16px;
   border-radius: 50%;
   right: calc(100% + 22px);
   top: 0;
   background-color: orangered;
   border: 2px solid white; 
}
.box h4{
    position: relative;
}
.box h3{
    font-size: 19px;
    padding: 10px 0px 6px;
    font-family: Georgia, 'Times New Roman', Times, serif;
    color:#36454F;
}
.box h3{
    line-height: 1.2;
    font-size: 17px;
}
@media(max-width:768px){
    main.row{
        grid-template-columns: 1fr;
    }
    .row .col:nth-child(2){
        margin-top:30px;
    }
}
.container-2{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    justify-content: center;
    align-items: center;
    text-align: center;
    grid-gap:1rem;
    padding: 1rem 80px;
    font-size: 1.2rem;

}
.skill-box{
    padding: 1rem;
    cursor: pointer;
}
.inner{
    padding-top: 20px;
}
.header{
    text-align: center;
    color: orangered;
    padding: 1rem;
    position: absolute;
}
.header:after{
    content: '';
    position: absolute;
    bottom:0;
    left:50%;
    transform:translate(-50%);
    height: 4px;
    width: 100px;
}
.skill-tittle{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0.7rem;
    margin-bottom: 0.5rem;
    

}
.skill-tittle h3{
    color: #36454F;
    margin: 0.5rem;
}
.skill-icon{
    width: 50px;
}
.img{
    width: 90px;
    height: 90px;
    position: relative;
    border-radius: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
