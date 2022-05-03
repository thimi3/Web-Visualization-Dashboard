  
<!DOCTYPE html>
<html lang="en-us">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1" />
    <title> Latitude Weather Analysis</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">

    <link type="text/css" rel="stylesheet" href="https://unpkg.com/bootstrap/dist/css/bootstrap.min.css"/>
    <!-- Add Vue and BootstrapVue scripts just before the closing </body> tag -->
    <link type="text/css" rel="stylesheet" href="https://unpkg.com/bootstrap-vue@latest/dist/bootstrap-vue.min.css"/>
    <script src="https://unpkg.com/vue/dist/vue.min.js"></script>
    <script src="https://unpkg.com/bootstrap-vue@latest/dist/bootstrap-vue.min.js"></script>
</head>

<body>
    <div class="bs-example">
        <nav class="navbar navbar-expand-md navbar-light bg-light">
            
            <button type="button" id="buttonlat">
                <a href="index.html" class="navbar-brand">Latitude</a>
    
            </button>
    
            <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">
                <div class="navbar-nav ml-auto">
                    
                    <div class="nav-item dropdown">
                        <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">Plot</a>
                        <div class="dropdown-menu">
                            <a target= "__blank" href="temperature.html" class="dropdown-item">Temperature</a>
                            <a target= "__blank" href="humidity.html" class="dropdown-item">Humidity</a>
                            <a target= "__blank" href="cloudiness.html" class="dropdown-item">Cloudiness</a>
                            <a target= "__blank" href="wind_speed.html" class="dropdown-item">Windspeed</a>
                        </div>
                    </div>
                    <a target= "__blank" href="data.html" class="nav-item nav-link ">Data</a>
                    <a target= "__blank" href="compare.html" class="nav-item nav-link ">Comparison</a>
                </div>
                
            
            </div>
        </nav>
        
    </div>
    
   

    <div class="container">
        <div class="row">
            <div class= "col-md-8">
                <div class = "box box-left">
                    <section id="Introduction">
                        <h1> Summary: Latitude vs. X </h1>
                        <hr>
                        <figure>
                            <a target= "__blank" href="Images/landingResize.png" alt="Latitude vs X">

                            </a>
                            <img src="Images/Latitude vs. Temperature.png" width="240" height="240"
                            alt="Latitude vs. Temperature" title="Landing page" style="float: left"/>
                        </figure>
                        <section id="Summary">
                            <p> The goal of this website is to analyze how weather changes depending on the location.
                                We accomplish this analysis, we fuse the API from OpenWeatherMap API to collect the dataset across different cities.
                            </p>
                            <p> The data was collected and stored. using Matplotlib, we plot different aspects of the weather tude
                                Factors we looked at included: temperature, cloudiness, wind_speed and humidity. 
                            </p>
                            <ul>
                                <li> Max Temperature(F) vs. City Latitude</li>
                                <li> Humidity (%) vs. City Latitude</li>
                                <li> Cloudiness (%) vs. City Latitude</li>
                                <li>Wind Speed (mph) vs. City Latitude</li> 

                            </ul>
                        </section>
                    </section>
                </div>
            </div>
            <div class="col-md-4">
                <div class= "box box-right">
                    <h6> Visualizations</h6>
                    <hr>
                    <div class ="row">
                        <div class="col-xs-6 col-sm-3 col-md-6">
                            <figure>
                                <a target="__blank" href= "temperature.html">
                                    <img id="landing" src="Images/Latitude vs. Temperature.png" alt="City Latitude vs. Temperature">
                                </a>
                            </figure>
                        </div>
                        <div class="col-xs-6 col-sm-3 col-md-6">
                            <figure>
                                <a target="__blank" href="humidity.html">
                                    <img id="landing" src="Images/Latitude vs. Humidity.png" alt="City Latitude vs. Humidity">
                                </a>
                            </figure>
                        </div>
                        <div class="col-xs-6 col-sm-3 col-md-6">
                            <figure>
                                <a target="__blank" href="cloudiness.html">
                                    <img id="landing" src="Images/Latitude vs. Cloudiness.png" alt="City Latitude vs. Cloudiness">
                                </a>
                            </figure>
                        </div>
                        <div class="col-xs-6 col-sm-3 col-md-6">
                            <figure>
                                <a target="__blank" href="wind_speed.html">
                                    <img id="landing" src="Images/Latitude vs. Windspeed.png" alt="City Latitude vs. Windspeed">
                                </a>
                            </figure>
                        </div>

                    </div>

                </div>
            </div>
        </div>
    </div>



<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>
© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About

