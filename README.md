<!DOCTYPE html>
<!--Design By ProtoBeer Based on Template-->
<!--Seccion personal del usuario donde administra sus puntos, logros y experiencias-->
<html lang="en">
    <head>
        <title>Mi Patagonia</title>
        <!--Config-->
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <meta name="keywords" content="Travel Hunt App Responsive web template, Bootstrap Web Templates, Flat Web Templates, Android  Compatible web template, Smartphone Compatible web template, free webdesigns for Nokia, Samsung, LG, SonyEricsson, Motorola web design" />
        <script type="application/x-javascript"> addEventListener("load", function() {setTimeout(hideURLbar, 0); }, false); function hideURLbar(){ window.scrollTo(0,1); } </script>
        <meta charset utf="8">
        <!--font-awsome-css-->
        <link rel="stylesheet" href="css/font-awesome.min.css"> 
        <!--bootstrap-->
        <link href="css/bootstrap.min.css" rel="stylesheet" type="text/css">
        <!--custom css-->
        <link href="css/style.css" rel="stylesheet" type="text/css"/>
        <!--component-css-->
        <script src="js/jquery-2.1.4.min.js"></script>
        <script src="js/bootstrap.min.js"></script>
        <!--script-->
        <script src="js/modernizr.custom.js"></script>
        <script src="js/bigSlide.js"></script>
        <script>
            $(document).ready(function () {
                $('.menu-link').bigSlide();
            });
        </script>
        <!-- web-fonts -->  
        <link href='//fonts.googleapis.com/css?family=Abril+Fatface' rel='stylesheet' type='text/css'>
        <link href='//fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600,600italic,700,700italic,800,800italic' rel='stylesheet' type='text/css'>
        <!-- //web-fonts -->
        <!-- pop-up-box -->
        <script src="js/jquery.magnific-popup.js" type="text/javascript"></script>
        <script>
            $(document).ready(function () {
                $('.popup-top-anim').magnificPopup({
                    type: 'inline',
                    fixedContentPos: false,
                    fixedBgPos: true,
                    overflowY: 'auto',
                    closeBtnInside: true,
                    preloader: false,
                    midClick: true,
                    removalDelay: 300,
                    mainClass: 'my-mfp-zoom-in'
                });
            });
        </script>
        <!--//pop-up-box -->
    </head>
    <body>
        <div class="body-back">
            <div class="masthead pdng-stn1">
                <div id="menu" class="panel" role="navigation">
                    <div class="wrap-content">
                        <div class="profile-menu text-center">
                            <a class=" link link--yaku  active" href="main.php"><h3>MENU</h3></a>
                            <div class="pro-menu">
                                <div class="logo">
                                    <li><a class=" link link--yaku" href="miPatagonia.php">Mi&nbspPatagonia</a></li>
                                    <li><a class=" link link--yaku" href="comunidad.php">Comunidad</a></li>
                                    <li><a class=" link link--yaku" href="cervezas.php">Cervezas</a></li>
                                    <li><a class=" link link--yaku" href="refugios.php">Refugios</a></li>
                                    <li><a class=" link link--yaku" href="cerveceria.php">Cerveceria</a></li>
                                    <li><a class=" link link--yaku" href="growler.php">Growler</li>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="phone-box wrap push" id="home">
                    <div class="menu-notify">
                        <div class="profile-left">
                            <a href="#menu" class="menu-link"><i class="fa fa-list-ul"></i></a>
                        </div>
                        <div class="Profile-mid">
                            <h5 class="pro-link"><a href="main.php">Patagonia</a></h5>
                        </div>
                        <div class="Profile-right">
                            <a href="#small-dialog" class="sign-in popup-top-anim"> <i class="fa fa-user"></i></a> 
                            <!-- modal -->
                            <div id="small-dialog" class="mfp-hide">
                                <div class="login-modal"> 	
                                    <div class="booking-info">
                                        <h3><a href="main.php">Patagonia - LogIn</h3>
                                    </div>
                                    <div class="login-form">
                                        <form action="#" method="post">
                                            <p>Usuario</p>
                                            <input type="text" name="Name" required=""/>
                                            <p>Contraseña</p>
                                            <input type="password" name="Password" required=""/>	 
                                            <div class="wthree-text"> 
                                                <ul> 
                                                    <li> <a href="#">Olvidaste tu Contraseña?</a> </li>
                                                </ul>
                                                <div class="clear"> </div>
                                            </div> 
                                            <input type="submit" value="Sign In">		
                                        </form>
                                        <p>No Tienes Cuenta?<a href="#small-dialog1" class="sign-in popup-top-anim">Registrate</a></p>
                                    </div> 
                                </div>
                            </div>
                            <!-- //modal --> 
                            <!-- modal-2 -->
                            <div id="small-dialog1" class="mfp-hide">
                                <div class="login-modal">  
                                    <div class="booking-info">
                                        <h3><a href="main.html">Patagonia - Sing Up</a></h3>
                                    </div>
                                    <div class="login-form signup-form">
                                        <form action="#" method="post">
                                            <p>Usuario</p>
                                            <input type="text" name="Name"  required=""/>
                                            <p>Email </p>
                                            <input type="text" name="Email"  required=""/>
                                            <p>Contraseña</p>
                                            <input type="password" name="Password" placeholder="" required=""/>	
                                            <div class="wthree-text"> 
                                                <input type="checkbox" id="brand1" value="1">
                                                <label for="brand1">Acepta Terminos y Condiciones</label> 
                                            </div>
                                            <input type="submit" value="Sign Up">		
                                        </form> 
                                    </div> 
                                </div>
                            </div>
                            <!-- //modal-2 --> 
                        </div>
                        <div class="clearfix"></div>
                    </div> 
                    <div class="w3agile banner-bottom">
                        <!--Page-->
                        <ul style="horizontal-align: left;">
                            <li><img src="images/profilePic.jpg" style="width: 100px; height: 100px;" /></li>
                            <li style="text-align: left;"> <h2>Filomena</h2><h3>Barese</h3></li>
                            <li style="horizontal-align: right;"><img src="images/qr.png" style="width: 90px; height: 90px;" /></li>
                        </ul>
                        <hr  style=" border-width: 3px;">
                        <a href="puntos.php">
                            <ul style="text-align: left;">
                                <li style="margin-right: 30px;"><i class="fa fa-bookmark" aria-hidden="true"></i></li>
                                <li style="text-align: left; vertical-align: middle;">
                                    <h3>Puntos</h3>
                                    <h4>Revisa y canjea tus Puntos</h4>
                                </li>
                            </ul>
                        </a>
                        <hr  style=" border-width: 3px;">
                        <a href="logros.php">
                            <ul style="text-align: left;">
                                <li style="margin-right: 30px;"><i class="fa fa-bookmark" aria-hidden="true"></i></li>
                                <li style="text-align: left; vertical-align: middle;">
                                    <h3>Logros</h3>
                                    <h4>Mira hasta donde llegaste</h4>
                                </li>
                            </ul>
                        </a>
                        <hr  style=" border-width: 3px;">
                        <a href="camino.php">
                            <ul style="text-align: left;">
                                <li style="margin-right: 30px;"><i class="fa fa-bookmark" aria-hidden="true"></i></li>
                                <li style="text-align: left; vertical-align: middle;">
                                    <h3>Camino Patagonia</h3>
                                    <h4>Rumbo a Bariloche</h4>
                                </li>
                            </ul>
                        </a>
                        <hr  style=" border-width: 3px;">
                        <a href="historial.php">
                            <ul style="text-align: left;">
                                <li style="margin-right: 30px;"><i class="fa fa-bookmark" aria-hidden="true"></i></li>
                                <li style="text-align: left; vertical-align: middle;">
                                    <h3>Mis Experiencias</h3>
                                    <h4>Viejos Recuerdos</h4>
                                </li>
                            </ul>
                        </a>
                        <hr  style=" border-width: 3px;">
                        <a href="miGrowler.php">
                            <ul style="text-align: left;">
                                <li style="margin-right: 30px;"><i class="fa fa-bookmark" aria-hidden="true"></i></li>
                                <li style="text-align: left; vertical-align: middle;">
                                    <h3>Mi Growler</h3>
                                    <h4>Hora de cargarlo</h4>
                                </li>
                            </ul>
                        </a>
                        <hr  style=" border-width: 3px;">
                        <a href="invitaAmigos.php">
                            <ul style="text-align: left;">
                                <li style="margin-right: 30px;"><i class="fa fa-bookmark" aria-hidden="true"></i></li>
                                <li style="text-align: left; vertical-align: middle;">
                                    <h3>Invita Amigos</h3>
                                    <h4>Para sumar puntos</h4>
                                </li>
                            </ul>
                        </a>
                        <!--//Page-->
                    </div>
                </div>
            </div>
            <script src="js/jquery.nicescroll.js"></script>
            <script src="js/scripts.js"></script>
    </body>
</html>

