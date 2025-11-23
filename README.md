
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <header class="header">
        <a href="#" class="logo"><span>Ron Christian Glorioso</span></a>

        <nav class="navbar">
            <a href="#" class="active">Portfolio</a>
            <a href="#">Services</a>
            <a href="#">Experience</a>
            <a href="#">Projects</a>
            <a href="#">Education</a>
        </nav>

        <a href="#" class="Contact">Contact Me</a>
    </header>

    <section class="home">
        <div class="home-content">
            <h3>Hi</h3>

            <h1>I'm <span>Ron<br></span>a Digital Artist</h1>

            <p>I’m currently developing my skills in digital illustration, learning new art techniques, and exploring different styles. I enjoy creating expressive characters and experimenting with color and design.</p>
            
            <div class="btn-box">
                <button class="btn-1">Hire Me</button>
                <button class="btn-2">Experience</button>
            </div>
        </div>
        <div class="img-box">
            <img src="images/img.jpeg" alt="">
        </div>
    </section>

    <section class="about">

        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Digital <span>Artist</span></h3>
            <p>Hi! I’m a digital artist who loves drawing anime-style characters, fantasy worlds, and creating my own original characters. I enjoy designing personalities, outfits, and stories, and I’m always experimenting to bring my ideas to life. Art is something I genuinely love doing, and I’m excited to keep growing and finding my own voice in it.</p>
        </div>        
    </section>

    <section class="skills">

        <div class="skills-content">
            <h2 class="heading">What I've learned / <span>Skills Section</span></h2>
            <p>I’ve been building my skills in digital illustration, especially anime-inspired art. I’m comfortable sketching, doing line art, and polishing pieces with color and shading. I also enjoy designing characters from scratch and imagining the worlds they come from.</p>
            <p>Right now, I’m working on getting better at anatomy, lighting, and creating more dynamic poses. I’m also exploring ways to make my style feel more expressive and unique. Overall, I’m focused on becoming more confident and consistent with my artwork.</p>
        </div>
    </section>

    <section class="contact-form">
        <h2 class="contact-me">Contact <span>Me</span></h2>

        <form action="#">

            <div class="input-box">
                <input type="text" placeholder="Full Name">
                <input type="email" placeholder="Email">
            </div>

            <div class="input-box">
                <input type="number" placeholder="Phone Number">
                <input type="text" placeholder="Subject">
            </div>

            <textarea name="" id="" cols="30" rows="10" placeholder="Your Message"></textarea>
            <input type="submit" value="Send Message" class="btn-1">
        </form>
    </section>

    <footer class="footer">
        <div class="social">
            <a href="#"><i class='bx bxl-facebook-circle'></i></a>
            <a href="#"><i class='bx bxl-twitter'></i></a>
            <a href="#"><i class='bx bxl-instagram'></i></a>
            <a href="#"><i class='bx bxl-gmail'></i></a>
        </div>

        <ul class="list">
            <li>
                <a href="#">FAQ</a>
            </li>
            <li>
                <a href="#">Services</a>
            </li>
            <li>
                <a href="#">About Me</a>
            </li>
            <li>
                <a href="#">Contact</a>
            </li>
            <li>
                <a href="#">Privacy Policy</a>
            </li>
        </ul>

        <p class="copyright">© 2025 Ron | All Rights Reserved</p>
    </footer>
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins' ,sans-serif;
    text-decoration: none;
    list-style: none;
}
.header{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 35px 12%;
    background: rgba(8, 2, 29, 0.705);
    backdrop-filter: blur(10px);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}
.logo{
    font-size: 25px;
    color: rgb(255, 255, 255);
    font-weight: 600;
    transition: 0.3s ease;
}
.logo:hover{
    color: black;
    text-shadow: 0 0 25px purple,
                 0 0 50px purple;
    transform: scale(1.1);    
}
span{
    color: rgb(0, 195, 255);
}
.navbar a{
    font-size: 18px;
    color: white;
    font-weight: 500;
    margin: 0 20px;
    border-bottom: 3px solid transparent;
    transition: 0.3s ease;    
}
.navbar a:hover,
.navbar a.active{
    color: rgb(0, 196, 245);
    border-bottom: 3px solid rgb(0, 195, 255);
}
.contact{
    padding: 10px 28px;
    background-color: white;
    color: black;
    border: 2px solid transparent;
    border-radius:  18px;
    font-size: 16px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
}
.contact:hover{
    background-color: rgb(0, 195, 255);
    box-shadow: 0 0 25px rgb(0, 195, 255);
    color: white;
}
.home{
    width: 100%;
    min-height: 100vh;
    background-color: aliceblue;
    display: flex;
    align-items: center;
    gap: 7em;
    padding: 30px 12% 0;
}
.home-content{
    max-width: 800px;
}
.home-content h3{
    font-size: 42px;
}
.home-content h1{
    font-size:  62px;
    line-height: 1.2;
}
.home-content p{
    font-size: 18px;
    margin: 25px 0 30px;
}
.btn-box{
    width: 345px;
    display: flex;
    gap: 2em;
}
.btn-1{
    padding: 15px 28px;
    background-color: black;
    color: white;
    border: 2px solid transparent;
    border-radius: 8px;
    font-size: 18px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
    cursor: pointer;
}
.btn-1:hover{
    background-color: white;
    color: black;
    border: 2px solid black;
}
.btn-2{
    padding: 15px 28px;
    background-color: black;
    color: white;
    border: 2px solid transparent;
    border-radius: 8px;
    font-size: 18px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
    cursor: pointer;
}
.btn-2:hover{
    background-color: white;
    color: rgb(0, 195, 255);
}
.img-box img{
    border-radius: 50%;
    width: 550px;
}

::-webkit-scrollbar{
    width: 15px;
}
::-webkit-scrollbar-thumb{
    background-color: rgb(0, 195, 255);
}
::-webkit-scrollbar-track{
    background-color: black;
}

.about{
    display: flex;
    justify-content: center;
    align-items: 12% 8%;
    gap: 10em;
    background: black;
}
.about-content h2{
    text-align: left;
    color: white;
    font-size: 42px;
}
.about-content h3{
    font-size: 62px;
    color: white;
}
.about-content p{
    color: white;
    font-size: 20px;
    margin: 2em 0 3em;
}

.skills{
    display: flex;
    justify-content: center;
    align-items: 12% 8%;
    gap: 10em;
    background: black;
}    
.skills-content h2{
    text-align: left;
    color: white;
    font-size: 42px;
}
.skills-content p{
    color: white;
    font-size: 20px;
    margin: 2em 0 3em;
}    
.skills-content p{
    color: white;
    font-size: 20px;
    margin: 2em 0 3em;
}    
.contact-form h2{
    text-align: center;
    margin-top: 3em;
    margin-bottom: 1em;
    font-size: 36px;
}
.contact-form form{
    max-width: 50em;
    margin: 1rem auto;
    text-align: center;
    margin-bottom: 3em;
}

.contact-form form .input-box{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
.contact-form form .input-box input,
.contact-form form textarea{
    width: 100%;
    padding: 1.5em;
    font-size: 18px;
    color: black;
    background: rgb(255, 255, 255);
    border-radius: .8rem;
    margin: 1rem 0;
    resize: none;
}
.footer{
    position: relative;
    bottom: 0;
    width: 100%;
    padding: 40px 0;
    background-color: black;
}
.footer .social{
    text-align: center;
    padding-bottom: 25px;
    color: white;
}
.footer .social a{
    font-size: 24px;
    color: white;
    border: 2px sold aqua;
    width: 40px;
    height: 40px;
    line-height: 38px;
    display: inline-block;
    text-align: center;
    border-radius: 50%;
    margin: 0 8px;
    box-shadow: inset 0 0 10px aqua, 0 0 10px aqua;
    transition: 0.3s ease;
}
.footer .social a:hover{
    transform: scale(1.2)translateY(-10px);
    color: white;
    border: 2px solid aqua;
}
.footer ul{
    margin-top: 0;
    padding: 0;
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 0;
    text-align: center;
}
.footer ul li a{
    color: white;
    border-bottom: 3px solid transparent;
    transition: 0.3s ease;
}
.footer ul li a:hover{
    border-bottom: 3px solid transparent;
}
.footer ul li{
    display: inline-block;
    padding: 0 15px;
}
.footer .copyright{
    margin-top: 15px;
    text-align: center;
    font-size: 12px;
    color: whi;
}
