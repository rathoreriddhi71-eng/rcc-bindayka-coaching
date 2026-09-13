# rcc-bindayka-coaching
RCC Bindayka Coaching Institute - Quality education and expert guidance in Jaipur
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>RCC Bindayka Coaching</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f5f7fb;
    color:#222;
}

header{
    background:linear-gradient(135deg,#082567,#1769aa);
    color:white;
    text-align:center;
    padding:35px 15px;
}

header h1{
    font-size:36px;
}

header p{
    font-size:18px;
    margin-top:8px;
}

nav{
    background:#061b3a;
    padding:15px;
    text-align:center;
    position:sticky;
    top:0;
    z-index:10;
}

nav a{
    color:white;
    text-decoration:none;
    margin:8px;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:65px 20px;
    background:white;
}

.hero h2{
    font-size:34px;
    color:#082567;
}

.hero p{
    margin:15px auto 25px;
    max-width:600px;
    font-size:18px;
}

.btn{
    display:inline-block;
    padding:14px 24px;
    margin:6px;
    border-radius:8px;
    text-decoration:none;
    color:white;
    background:#ff7200;
    font-weight:bold;
}

.whatsapp{
    background:#20b858;
}

section{
    padding:45px 20px;
    text-align:center;
}

section h2{
    color:#082567;
    margin-bottom:25px;
    font-size:28px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}

.card{
    background:white;
    width:270px;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 15px #ddd;
}

.card .icon{
    font-size:40px;
    margin-bottom:12px;
}

.card h3{
    color:#1769aa;
    margin-bottom:10px;
}

.director{
    background:#eaf3ff;
}

.director-box{
    background:white;
    max-width:500px;
    margin:auto;
    padding:30px;
    border-radius:18px;
    box-shadow:0 4px 15px #ddd;
}

.photo{
    width:120px;
    height:120px;
    border-radius:50%;
    background:#1769aa;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:0 auto 18px;
    font-size:45px;
}

.director-box h3{
    font-size:24px;
    color:#082567;
}

.contact{
    background:white;
}

footer{
    background:#061b3a;
    color:white;
    text-align:center;
    padding:25px;
}

footer p{
    margin:6px;
}

@media(max-width:600px){
    header h1{
        font-size:28px;
    }

    .hero h2{
        font-size:27px;
    }

    nav a{
        font-size:14px;
        margin:4px;
    }
}
</style>
</head>

<body>

<header>
    <h1>RCC BINDAYKA</h1>
    <p>Coaching Institute | Bindayka, Jaipur, Rajasthan</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#courses">Courses</a>
    <a href="#facilities">Facilities</a>
    <a href="#director">Director</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">

    <h2>Welcome to RCC Bindayka</h2>

    <p>
        Quality education, expert guidance and a better learning
        environment for students.
    </p>

    <a class="btn" href="tel:9352048226">
        📞 Call Now
    </a>

    <a class="btn whatsapp"
       href="https://wa.me/919352048226"
       target="_blank">
        💬 WhatsApp
    </a>

</section>

<section id="courses">

    <h2>📚 Our Courses</h2>

    <div class="cards">

        <div class="card">
            <div class="icon">📖</div>
            <h3>School Coaching</h3>
            <p>
                Regular academic coaching and subject guidance
                for school students.
            </p>
        </div>

        <div class="card">
            <div class="icon">🎯</div>
            <h3>Exam Preparation</h3>
            <p>
                Focused preparation, practice and revision
                for examinations.
            </p>
        </div>

        <div class="card">
            <div class="icon">🧠</div>
            <h3>Special Guidance</h3>
            <p>
                Personal attention and guidance to help students
                improve their learning.
            </p>
        </div>

    </div>

</section>

<section id="facilities">

    <h2>⭐ Our Facilities</h2>

    <div class="cards">

        <div class="card">
            <div class="icon">🏫</div>
            <h3>Good Learning Environment</h3>
            <p>Comfortable environment for focused study.</p>
        </div>

        <div class="card">
            <div class="icon">👨‍🏫</div>
            <h3>Experienced Guidance</h3>
            <p>Proper guidance and support for students.</p>
        </div>

        <div class="card">
            <div class="icon">📝</div>
            <h3>Regular Tests</h3>
            <p>Practice and tests to check student progress.</p>
        </div>

        <div class="card">
            <div class="icon">💡</div>
            <h3>Concept Learning</h3>
            <p>Focus on understanding concepts clearly.</p>
        </div>

    </div>

</section>

<section class="director" id="director">

    <h2>👨‍💼 Our Director</h2>

    <div class="director-box">

        <div class="photo">
            RC
        </div>

        <h3>Roshan Chaudhary</h3>

        <p style="margin-top:10px;">
            Director, RCC Bindayka
        </p>

        <p style="margin-top:15px;">
            Leading RCC Bindayka with a focus on quality
            education and student development.
        </p>

    </div>

</section>

<section class="contact" id="contact">

    <h2>📞 Contact Us</h2>

    <p>📍 Bindayka, Jaipur, Rajasthan</p>

    <p style="margin:15px;font-size:20px;">
        <b>9352048226</b>
    </p>

    <a class="btn" href="tel:9352048226">
        📞 Contact Director
    </a>

    <a class="btn whatsapp"
       href="https://wa.me/919352048226"
       target="_blank">
        💬 WhatsApp Us
    </a>

</section>

<footer>

    <p><b>RCC Bindayka Coaching Institute</b></p>
    <p>Bindayka, Jaipur, Rajasthan</p>
    <p>© 2026 RCC Bindayka. All Rights Reserved.</p>

</footer>

</body>
</html>
