<!DOCTYPE html>
<html lang="en">

<head>
    <title>Page Title</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <!-- Load font awesome icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <link rel="stylesheet" href="CSS/style.css">
    <script src="js/script.js" defer></script>

</head>

<body>

    <div class="topnav" id="myTopnav">
        <a href="#default" class="logo"><i class="fa fa-camera-retro"></i> Certificates</a>

        <div class="topnav-right">
            <a class="#home" href="#home"><i class="fa fa-fw fa-home"></i> Home</a>
            <a href="#news"><i class="fa fa-fw fa-search"></i> News</a>
            <a class="page" href="#home"><i class="fa fa-camera-retro"></i> Certificates</a>
            <a href="#contact"><i class="fa fa-fw fa-envelope"></i> Contact</a>
            <a href="#about"><i class="fa fa-fw fa-user"></i> About</a>
        </div>
        <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
    </div>


    <!-- The social media icon bar -->
    <div class="icon-bar">
        <a href="#" class="linkedin"><i class="fa fa-linkedin"></i></a>
        <a href="#" class="kaggle"><img src="https://www.kaggle.com/static/images/site-logo.svg" alt="kaggle"
                height="10" /></a>
        <a href="#" class="tableau"><img src="https://www.tableau.com/favicon.ico" alt="linux" height='20'></a>
        <a href="#" class="medium"><i class="fa fa-medium"></i></a>
        <a href="#" class="github"><i class="fa fa-github"></i></a>
        <a href="#" class="youtube"><i class="fa fa-youtube"></i></a>
    </div>

    <!-- MAIN (Center website) -->
    <div class="main">


        <h2>PORTFOLIO</h2>

        <div id="myBtnContainer">
            <button class="btn active" onclick="filterSelection('all')"> Show all</button>
            <button class="btn" onclick="filterSelection('nlp')"> Natural Language Processing</button>
            <button class="btn" onclick="filterSelection('dl')"> Deep Learning</button>
            <button class="btn" onclick="filterSelection('ml')"> Machine Learning</button>
            <button class="btn" onclick="filterSelection('stat')"> Data Analytics and Statistics</button>
            <button class="btn" onclick="filterSelection('data')"> Data Analysis and Visualization</button>
            <button class="btn" onclick="filterSelection('sql')"> SQL and Visualization</button>
            <button class="btn" onclick="filterSelection('python')"> Python</button>
            <button class="btn" onclick="filterSelection('basics')"> Basics</button>
        </div>

        <!-- Portfolio Gallery Grid -->
        <div class="row">
            <div class="column nlp">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/52633947857472?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/52633947857472.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Oct 31h, 2022</p>
                </div>
            </div>

            <div class="column dl">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/50463577522724?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/50463577522724.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Oct 27th, 2022</p>
                </div>
            </div>

            <div class="column ml">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/83967736502601?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/83967736502601.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Sep 22th, 2022</p>
                </div>
            </div>

            <div class="column stat">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/70911612031898?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/70911612031898.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Aug 29th, 2022</p>
                </div>
            </div>
            <div class="column stat">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/19204865521083?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/19204865521083.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Jul 15th, 2022</p>
                </div>
            </div>

            <div class="column data">
                <div class="content">
                    <a target="blank" href="https://c11n.clarusway.com/en/verify/02465464528354?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/02465464528354.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Jun 12th, 2022</p>
                </div>
            </div>
            <div class="column data">
                <div class="content">
                    <a target="blank" href="https://c11n.clarusway.com/en/verify/90382328093570?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/90382328093570.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Jun 12th, 2022</p>
                </div>
            </div>

            <div class="column sql">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/39735402594596?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/39735402594596.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Aug 03th, 2022</p>
                </div>
            </div>
            <div class="column sql">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/17113084238615?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/17113084238615.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Jul 15th, 2022</p>
                </div>
            </div>

            <div class="column python">
                <div class="content">
                    <a target="blank" href="https://www.sololearn.com/Certificate/CT-QDWCZPOH/png">
                        <img src="https://www.sololearn.com/Certificate/CT-QDWCZPOH/png" alt="">
                    </a>
                    <h4><a href="https://www.sololearn.com">sololearn.com</a></h4>
                    <p>July 04th, 2022</p>
                </div>
            </div>
            <div class="column python">
                <div class="content">
                    <a target="blank" href="https://www.sololearn.com/Certificate/CT-WWTS6GH2/png">
                        <img src="https://www.sololearn.com/Certificate/CT-WWTS6GH2/png" alt="">
                    </a>
                    <h4><a href="https://www.sololearn.com">sololearn.com</a></h4>
                    <p>Apr 26th, 2022</p>
                </div>
            </div>
            <div class="column python">
                <div class="content">
                    <a target="blank" href="https://www.sololearn.com/Certificate/CT-7BMPKVLT/png">
                        <img src="https://www.sololearn.com/Certificate/CT-7BMPKVLT/png" alt="">
                    </a>
                    <h4><a href="https://www.sololearn.com">sololearn.com</a></h4>
                    <p>Apr 27th, 2022</p>
                </div>
            </div>

            <div class="column basics">
                <div class="content">
                    <a target="blank" href="https://d34lllqo5jm5il.cloudfront.net/en/verify/35188065836243?ref=email">
                        <img src="https://verified-bucket.s3.eu-central-1.amazonaws.com/cert/35188065836243.png" alt="">
                    </a>
                    <h4><a href="https://clarusway.com/">clarusway.com</a></h4>
                    <p>Apr 10th, 2022</p>
                </div>
            </div>

            <!-- END GRID -->
        </div>

        <!-- END MAIN -->
    </div>

</body>

</html>
