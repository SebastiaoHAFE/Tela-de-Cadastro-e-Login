# Tela-de-Cadastro-e-Login
Tela de Casdatro e Login Feita com Html, CSS e javascript


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tela de Login e Cadastro Interativo</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href=" https://use.fontawesome.com/releases/v5.8.2/css/all.css"
        integridade="sha384-oS3vJWv + 0UjzBfQzYUhtDYW + Pj2yciDJxpsK1OYPAYjqT085Qqz/ 1cq5FLXAZQ7Ay 
        "crossorigin="anônimo">
</head> 
<body>
    <div class="container">
        <div class="content first-content">
        <div class="first-column">
            <h2 class="title title-primary">Welcome Back!</h2>
            <p class="description description-primary">To Keep Connected With Us</p>
            <p class="description description-primary">Please Login With Your Info</p>
            <button id="signin" class="btn btn-primary">Sign Ip</button>
       </div>
        <div class="second-column">
        <h2 class="title title-second">Create Account</h2>
        <div class="social-media">
            <ul class="list-social-media">
            <a class="link-social-media" href="#">
                <li class="item-social-media">
                    <i class="fab fa-facebook-f"></i>
                </li>
            </a>
            <a class="link-social-media" href="#">
                <li class="item-social-media">
                    <i class="fab fa-google-plus-g"></i>
                </li>
            </a>
            <a class="link-social-media" href="#">
                <li class="item-social-media">
                    <i class="fab fa-linkedin-in"></i>
                </li>
             </a>
            </ul>
        </div><!-- social media -->
        <p class="description description-second">Or Use Your E-mail for Registration:</p>
        <form class="form"> 
         <label class="label-input" for="">
            <i class="fas fa-users icon-modify"></i>
            <input type="name" placeholder="name">
        </label>
           <label class="label-input" for="">
            <i class="far fa-envelope icon-modify"></i>
            <input type="email" placeholder="email">
        </label>
           <label class="label-input" for="">
            <i class="fas fa-unlock icon-modify"></i>
            <input type="password" placeholder="password">
        </label>
           <button class="btn btn-second">Sign Up</button>
           </form> 
        </div><!-- second column -->
     </div><!-- first content -->
        <div class="content second-content">
            <div class="first-column">
                <h2 class="title title-primary">Hello, Friend!</h2>
                <p class="description description-primary">Enter Your Personal Details</p>
                <p class="description description-primary">And Start Jourmey With Us</p>
                <button id="signup" class="btn btn-primary">Sign Up</button>
            </div>
            <div class="second-column">
            <h2 class="title title-second">Sing In To Developer</h2>
            <div class="social-media">
                <ul class="list-social-media">
                    <a class="link-social-media" href="#">
                        <li class="item-social-media">
                            <i class="fab fa-facebook-f"></i>
                        </li>
                    </a>
                    <a class="link-social-media" href="#">
                        <li class="item-social-media">
                            <i class="fab fa-google-plus-g"></i>
                        </li>
                    </a>
                    <a class="link-social-media" href="#">
                        <li class="item-social-media">
                            <i class="fab fa-linkedin-in"></i>
                        </li>
                     </a>
                    </ul>
            </div>
            <p class="description description-second">Or Use Your E-mail Account</p>
            <form class="form">
                <label class="label-input" for="">
                    <i class="far fa-envelope icon-modify"></i>
                    <input type="email" placeholder="email">
                </label>
                   <label class="label-input" for="">
                    <i class="fas fa-unlock icon-modify"></i>
                    <input type="password" placeholder="password">
                </label>
                <a class="password" href="#">Forgot Your Password?</a>
                <button class="btn btn-second">Sing In</button>
            </form>
            </div><!--Second column-->
            <script src="js/app.js"></script>
</body>
</html>
