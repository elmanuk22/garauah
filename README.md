

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8"/>
        <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <link rel="stylesheet" 
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" 
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" 
        crossorigin="anonymous" 
        referrerpolicy="no-referrer"
         />
        <link rel="stylesheet" href="style6.css"/>
        <title>PENGEN APA YA</title>
    </head>
    <body>
        <header>
            <div class="navbar">
                <div class="logo"><a href="#"> AKU SI GANTENG</a></div>
                <ul class="links">
                    <li><a href="hero">Home</a></li>
                    <li><a href="about">about</a></li>
                    <li><a href="servis.html">services</a></li>
                    <li><a href="contact">contact</a></li>
                </ul>
                <a href="#" class="action_btn">Get Started</a>
                <div class="toggle_btn">
                    <i class="fa-solid fa-bars"></i>
                </div>
            </div>

            <div class="dropdown_menu">
            <li><a href="index6.html">Home</a></li>
                <li><a href="about">about</a></li>
                <li><a href="servis.html">services</a></li>
                <li><a href="contact">contact</a></li>
                <li> <a href="#" class="action_btn">Get Started</a></li>
            </div>    
        </header>
        
        <main>
            <section id="hero">
                <h1>SELAMAT DATANG</h1>
                <p>
                    TIDAK PERLU KATA KATA <br />
                     YANG PENTING BUKTI NYATA 
                    </p>   
            </section>
        </main>

        <script>
            const toggleBtn = document.querySelector('.toggle_btn')
            const toggleBtnIcon = document.querySelector('.toggle_btn i')
            const dropDownMenu = document.querySelector('.dropdown_menu')

            toggleBtn.onclick = function () {
                dropDownMenu.classList.toggle('open')
                const isOpen = dropDownMenu.classList.contains('open')
                
            toggleBtnIcon.classList = isOpen
                ? 'fa-solid fa-xmark'
                : 'fa-solid fa-bars'
            }
        </script>
    </body>
</html>
