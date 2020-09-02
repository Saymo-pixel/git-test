# git-test
<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Required meta tags always come first -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css" />

    <!-- Additional CSS must be placed after Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css" />
    <link rel="stylesheet" href="node_modules/bootstrap-social/bootstrap-social.css" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lobster|Open+Sans" />
    <link rel="stylesheet" href="css/styles.css" />

    <title>NuCamp: A Better Way To Camp</title>
</head>

<body>

    <header class="jumbotron jumbotron-fluid">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h1>NuCamp</h1>
                    <h2>a better way to camp</h2>
                </div>
            </div>
        </div>
    </header>

    <nav class="navbar navbar-expand-sm navbar-dark sticky-top">
        <div class="container">
            <button class="navbar-toggler ml-auto" type="button" data-toggle="collapse" data-target="#nucampNavbar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="nucampNavbar">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link" href="index.html"><i class="fa fa-home fa-lg"></i> Home</a>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="aboutus.html"><i class="fa fa-info fa-lg"></i>
                            About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#"><i class="fa fa-list fa-lg"></i> Sites</a></li>
                    <li class="nav-item active"><a class="nav-link" href="#"><i class="fa fa-address-card fa-lg"></i>
                            Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
        <div class="row">
            <div class="col">
                <ol class="breadcrumb">
                    <li class="breadcrumb-item"><a href="index.html">Home</a></li>
                    <li class="breadcrumb-item active">Contact</li>
                </ol>
                <h2>Contact Us</h2>
                <hr />
            </div>
        </div>

        <div class="row row-content align-items-center">
            <div class="col-sm-4">
                <h5>Our Address</h5>
                <address>
                    1 Nucamp Way<br />
                    Seattle, WA 98001<br />
                    U.S.A.
                </address>
            </div>
            <div class="col">
                <a role="button" class="btn btn-link" href="tel:+12065551234"><i class="fa fa-phone"></i>
                    1-206-555-1234</a><br>
                <a role="button" class="btn btn-link" href="mailto :campsites@nucamp.co"><i
                        class="fa fa-envelope-o"></i> campsites@nucamp.co</a>
            </div>
        </div>

        <div class="row row-content">
            <div class="col-12">
                <h2>Send us your Feedback</h2>
                <hr />
            </div>
            <div class="col-md-10">
                <form>
                    <div class="form-group row">
                        <label for="firstName" class="col-md-2 col-form-label">First Name</label>
                        <div class="col-md-10">
                            <input type="text" class="form-control" id="firstName" name="firstName" placeholder="First Name" />
                        </div>
                    </div>
                    <div class="form-group row">
                        <label for="lastName" class="col-md-2 col-form-label">Last Name</label>
                        <div class="col-md-10">
                            <input type="text" class="form-control" id="lastName" name="lastName" placeholder="Last Name" />
                        </div>
                    </div>
                    <div class="form-group row">
                        <label for="areaCode" class="col-md-2 col-form-label">Contact Tel.</label>
                        <div class="col-5 col-md-3">
                            <input type="tel" class="form-control" id="areaCode" name="areaCode" placeholder="Area code" />
                        </div>
                        <div class="col-7">
                            <input type="tel" class="form-control" name="telNum" placeholder="Tel. number" />
                        </div>
                    </div>
                    <div class="form-group row">
                        <label for="email" class="col-md-2 col-form-label">Email</label>
                        <div class="col-md-10">
                            <input type="email" class="form-control" id="email" name="email" placeholder="Email" />
                        </div>
                    </div>
                    <div class="form-group row">
                        <div class="col offset-md-2">
                            May we contact you?
                            <div class="form-check form-check-inline">
                                <input type="radio" class="form-check-input" id="contactYes" name="contactRadios" value="yes" />
                                <label for="contactYes" class="form-check-label">Yes</label>
                            </div>
                            <div class="form-check form-check-inline">
                                <input type="radio" class="form-check-input" id="contactNo" name="contactRadios" value="no" />
                                <label for="contactNo" class="form-check-label">No</label>
                            </div>
                        </div>
                    </div>
                    <div class="form-group row">
                        <label for="feedback" class="col-md-2 col-form-label">Your Feedback</label>
                        <div class="col-md-10">
                            <textarea class="form-control" id="feedback" name="feedback" rows="8"></textarea>
                        </div>
                    </div>
                    <div class="form-group row">
                        <div class="offset-md-2 col-md-10">
                            <button type="submit"  class="btn btn-primary">Send Feedback</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>

    </div>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-4 col-sm-2 offset-1">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="index.html">Home</a></li>
                        <li><a href="aboutus.html">About</a></li>
                        <li><a href="#">Sites</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="col-6 col-sm-5 text-center">
                    <h5>Social</h5>
                    <a class="btn btn-social-icon btn-instagram" href="http://instagram.com/"><i
                            class="fa fa-instagram"></i></a>
                    <a class="btn btn-social-icon btn-facebook" href="http://facebook.com/"><i
                            class="fa fa-facebook"></i></a>
                    <a class="btn btn-social-icon btn-twitter" href="http://twitter.com/"><i
                            class="fa fa-twitter"></i></a>
                    <a class="btn btn-social-icon btn-youtube" href="http://youtube.com/"><i
                            class="fa fa-youtube"></i></a>
                </div>
                <div class="col-sm-4 text-center">
                    <a role="button" class="btn btn-link" href="tel:+12065551234"><i class="fa fa-phone"></i>
                        1-206-555-1234</a><br>
                    <a role="button" class="btn btn-link" href="mailto :campsites@nucamp.co"><i
                            class="fa fa-envelope-o"></i> campsites@nucamp.co</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- jQuery must come first, then Popper.js, then the Bootstrap JavaScript plugins.-->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>

</body>

</html>
