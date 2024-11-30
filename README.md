# Advanced-HTML5-Assignment


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta content="width=width-device, initial-scale=1.0">
    <title>Multimedia Webpage and a Registration Form</title>
</head>

<body>
    <header>
        <h1>Get Your Best Kenyan Gospel Music Here & Now!</h1>

        <h2>Alka Mbumba - Uwepo Wako Bwana (Audio)</h2>
        <section class="audio">
            <div class="audio-container">
                <audio src="c:\Users\pc\AppData\Local\OKmusi\storage\music\ALKA MBUMBA - UWEPO WAKO UWE NAMI (NIGHT OF EXODUS LIVE PERFORMANCE).mp3" controls></audio>
            </div>
        </section>
      

        <h2>Alka Mbumba - Uwepo Wako Bwana (Video)</h2>
        <section class="video">
            <div class="video-container">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/XwChKJF7MAM?si=4w8rv7wbjABS6tZ3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>


                
        </section>
    </header>

    <section id="Sign up Now">
        <h2>Sign Up</h2>
        <form action="/" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <br>
    
            <label for="email">Email:</label>       
            <input type="email" id="email" name="email" required>
            <br>

            <label for="age">Age:</label>
            <input type="number" id="age" name="age" placeholder="minimum age of 18 years old" required>
            <br>

            <radio checked="checked" name="gender">Gender:</radio>
            <input type="radio" name="gender" checked>Male
            <input type="radio" name="gender">Female
            <input type="radio" name="gender">Other
            <br>
    
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" minlength="8" maxlength="20" required>
            <br> 
            
            <input type="checkbox" name="terms" required> I agree to the <a href="terms.html">Terms and Conditions</a>
            <br>
    
            <button type="submit">Register</button>
        </form>   
    </section>



</body>
</html>
