<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no">
        <link rel="icon" type="image/png" sizes="16x16" href="assets/img/favicon.png">
        <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
        <title> Devilish x Hush </title>
        <!-- CSS -->
        <link href="https://fonts.googleapis.com/css?family=Montserrat:200,300,400,500,600%7CRoboto:400" rel="stylesheet" type="text/css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/material-design-iconic-font/2.2.0/css/material-design-iconic-font.min.css">
        <link href="assets/css/style.css" rel="stylesheet" type="text/css">
        <!-- Head Libs -->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js"></script>
        <script type="text/javascript">
            function makeState(el) {
                var display = document.getElementById(el).style.display;
                if (display == "none") document.getElementById(el).style.display = 'block';
                else document.getElementById(el).style.display = 'none';
            }
        </script>
    </head>

    <style>
        form-group {
            background-color: transparent;
        }
    </style>

    <body style="background-color: #151721;" class="content-dark">
        <!-- /.site-sidebar -->
        <main class="main-wrapper clearfix">
            <!-- /.page-title -->
            <!-- =================================== -->
            <!-- Different data widgets ============ -->
            <!-- =================================== -->
            <div class="widget-list row">


                <!-- /.widget-holder -->
                <div class="widget-holder widget-full-height widget-flex col-lg-6">

                        <!-- /.widget-heading -->
                        <div class="widget-body">
                            <div class="page-title-left pangalan">
                                <center>
                                    <img src="https://cdn.discordapp.com/avatars/988687146896490539/6cc9231ef7f5d2c7829f85b272da04c1.webp?size=80" style = "border-radius:50%; height: 58px; width: 58px;">
                                        <h2 class="page-title-description mr-0 d-none d-md-inline-block">&nbsp; x o . d e v i l i s h</h2>
                                    <img>
                                </center>
                            </div>
                            <br>
                            <button type="button" id="sh_apr" onclick="makeState('aprovadasapp');" class="btn btn-outline-eiiyz">Approved:&nbsp;<span id="aprovada_conta">0</span></button>
                            <br>
                            <p id="aprovadasapp"></p>
                            <!-- <button type="button" id="sh_ccn" onclick="makeState('ccnapp');" class="btn btn-outline-eiiyz">CCN:&nbsp;<span id="ccn_conta">0</span></button>
                            <br>
                            <p id="ccnapp"></p> -->
                            <button type="button" id="sh_rep" onclick="makeState('reprovadasapp');" class="btn btn-outline-eiiyz">Declined:&nbsp;<span id="reprovada_conta">0</span></button>
                            <br>
                            <p id="reprovadasapp"></p>
                        </div>
                        <!-- /.widget-body -->
                    <!-- /.widget-bg -->
                </div>



                <!-- /.widget-holder -->
                <div class="widget-holder widget-full-content widget-full-height col-lg-6">
                    <div class="widget-bg.transparent">
                        <div class="widget-body">
                            <div class="container-fluid pd-100">
                                <div class="row">
                                    <div class="col">
                                        <div class="row">
                                            <small>
                                                &nbsp;<span class = "badge badge-eiiyz"><i class='fas fa-check-circle'></i> Success: <span id="CLIVE">0</span></span>
                                                &nbsp;&nbsp;&nbsp;<span class = "badge badge-eiiyz"><i class='fas fa-exclamation-circle'></i> Declined: <span id="CDIE">0</span></span>
                                                &nbsp;&nbsp;&nbsp;<span class = "badge badge-eiiyz"><i class='fas fa-credit-card'></i> Total: <span id="testado">0</span> / <span id="carregada">0</span></span>
                                            </small>
                                        </div>
                                        <br>
                                        <textarea id="listz" class="form-control" style="resize:none;outline:none;width:100%; height:150px;"></textarea>
                                        <br>
                                        <button type="button" id="iniciar" onclick="start()" class="btn btn-outline-eiiyz bouncy" style="animation-delay:0.07s"><span id="demo">Start</span></button>
                                        <button type="button" onclick="stop()" id="parar" class="btn btn-outline-eiiyz bouncy">Stop</button>
                                        <button type="button" onclick="cleanInput()" id="clearpepe" class="btn btn-outline-eiiyz bouncy">Clear</button>
                                        <select type="select" id="angcute" class="btn btn-outline-eiiyz bouncy">
                                                <option value="api.php">Main API</option>
                                        </select>
                                        <!-- <br>
                                        <br>
                                        <button type="button" onclick="gatewaySelect()" class="btn btn-outline-eiiyz bouncy"><span id='gateway2'>Enable (Gateway 2)</span></button> -->
                                        <!-- /.col-6 -->
                                    </div>
                                    <!-- /.row -->
                                </div>
                                <!-- /.col-lg-6 -->
                            </div>
                            <!-- /.row -->
                        </div>
                        <!-- /.container-fluid -->
                    </div>
                    <!-- /.widget-body -->
                </div>
                <!-- /.widget-bg -->


            </div>
            <!-- /.widget-holder -->
            <!--/ #wrapper -->
            <!-- Scripts -->
            <script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"></link>
            <script src="assets/js/theme.js"></script>
            <script src="assets/js/custom.js"></script>
            <script src="jquery.js"></script>
            <script src="jquery-ui.js"></script>
            <script src="js.js"></script>
    </body>
</html>
