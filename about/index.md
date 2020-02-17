<!-- saved from url=(0033)http://localhost:50510/Home/About -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

    <link href="./About_files/bootstrap.min.css" rel="stylesheet" integrity="sha384-0Mou2qXGeXK7k/Ue/a1hspEVcEP2zCpoQZw8/MPeUgISww+VmDJcy2ri9tX0a6iy" crossorigin="anonymous">
    <style>

        body {
            padding-top: 4.0rem;
        }
    </style>

</head>
<body>

    <header>

        <nav class="navbar navbar-expand-md navbar-dark fixed-top" style="background-color:black">

            <div class="container">
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <a class="navbar-brand" href="http://localhost:50510/">
                    <img class="img-fluid" src="./About_files/Alicetrixlogoblack.png" width="150" alt="">
                </a>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <ul class="navbar-nav mr-auto">

                            <li class="nav-item active">
                                <a class="nav-item nav-link" href="http://localhost:50510/">Home <span class="sr-only">(current)</span></a>
                            </li>
                            <li class="nav-item">

                                <a class="nav-item nav-link" href="http://localhost:50510/Home/About">Help</a>
                            </li>

                    </ul>


                    
    <ul class="nav navbar-nav navbar-right">
        <!--<li><a class = "btn btn-outline-success mr-sm-2" asp-area="" asp-controller="Account" asp-action="Register">Register</a></li> -->
        <li><a class="btn btn-outline-success mr-sm-2" href="http://localhost:50510/Account/Login">Log in</a></li>
    </ul>

                   

                </div>


            </div>

        </nav>

    </header>


    <div class="container">
        <script type="text/javascript" src="./About_files/jquery-1.7.1.min.js.download"></script>




<div class="row">
    <div class="col-lg-2">

        <div id="navbar1" class="nav nav-pills bg-light">
            <a id="Introduction" class="nav-link active" href="http://localhost:50510/Help/Introduction.htm" target="myframe">Introduction</a>
            <a id="Setup" class="nav-link" href="http://localhost:50510/Help/Setup.htm" target="myframe">Setup</a>
            <a id="GoogleOnetime" class="nav-link ml-3 my-1" href="http://localhost:50510/help/GoogleOneTimeSetup.htm" target="myframe">Google Onetime Configuration</a>
            <a id="BoxOnetime" class="nav-link ml-3 my-1" href="http://localhost:50510/Help/BoxOneTimeAuth.html" target="myframe">Box Onetime Configuration</a>
            <a id="OneDriveOnetime" class="nav-link ml-3 my-1" href="http://localhost:50510/Help/OneDriveOneTimeSetup.html" target="myframe">OneDrive &amp; SharePoint Onetime Configuration</a>
            <a id="Authentication" class="nav-link ml-3 my-1" href="http://localhost:50510/Help/Authentication.html" target="myframe">Authentication</a>
            <a id="Remediation" class="nav-link" href="http://localhost:50510/Help/Remediation.html" target="myframe">Remediation</a>
            <a id="Migration" class="nav-link" href="http://localhost:50510/Help/Migration.html" target="myframe">Migration</a>
            <a id="Advanced" class="nav-link ml-3 my-1" href="http://localhost:50510/Help/MigrationAdvanced.html" target="myframe">Advanced Concepts</a>
            <a id="Reports" class="nav-link" href="http://localhost:50510/Help/Reports.html" target="myframe">Reports</a>
            <a id="Admin" class="nav-link" href="http://localhost:50510/Help/Admin.html" target="myframe">Admin</a>

        </div>
    </div>
    <div class="col-lg-10">
        <div class="embed-responsive embed-responsive-1by1">

            <iframe id="frame001" class="embed-responsive-item" name="myframe" src="./About_files/Introduction.html"></iframe>
        </div>
    </div>
</div>
<script>
    $(document).ready(function () {

        $("#navbar1 a").click(function () {
            $("#navbar1 a").removeClass("active");
            $(this).addClass("active");
        });
    });
</script>

<script>

    var main_route = (window.location.pathname.split("/")[3]);
    if (main_route) {      
        document.getElementById(main_route).click();
        document.getElementById(main_route).className = "nav-link active";
    }
    else {
        document.getElementById("Introduction").className = "nav-link active";
    }

   
</script>





        <hr>
        <footer>
            <div class="row">

                <div class="col-md-4" style="outline: 0px;">
                    <h5>© 2019 - Alicetrix LLC</h5>
                    
                </div>
                <div class="col-md-8" style="outline: 0px;">
                    <h5>
                        Contact us at our support email with your queries
                        at: <a href="mailto:contacts@alicetrix.com?subject=Support%20Needed">support@alicetrix.com</a><br>
                    </h5>

                    <div class="" id="accordion">

                        <div class="" id="headingOne">

                            <a href="http://localhost:50510/Home/About#" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                Assumptions and Liability Disclaimers
                            </a>


                        </div>
                        <div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
                            <div class="card-body">
                                <p>
                                    *Active tenants for migration should be deprovisioned to stop charges. Microsoft Azure provides options to provision and deprovision tenants on a click of a button from cloud platforms.
                                </p>
                                <p>
                                    ²Any Speed advertised is not promised but based on our results in labs and active customers.
                                </p>
                                <p>
                                    *Under consideration for Patent
                                </p>
                                <p>
                                    ³In some cases Bandwidth charges may apply. Please visit your current bandwidth requirements with your cloud provider for both source and destination tenant as well as Hosting environment
                                </p>

                                <p>
                                    <span class="badge badge-warning">Safe Harbor</span>
                                    SOFTWARE HAS BEEN TESTED AND VALIDATED IN CONFINES OF GENERIC REQUIREMENTS. YOU ARE EXPECTED TO TEST AND ENSURE SOFTWARE IS ABLE TO MEET YOUR REQUIREMENTS.
                                    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
                                    Please direct all your queries  on know-how of application to company support email address.NO SLA Applies.
                                </p>
                            </div>
                        </div>
                    </div>
                    &nbsp;
                    <h6>
                        
                        ©Copyrighted
                    </h6>

                </div>
             
            </div>

                    
                       
                     
            </footer></div>
        
  
    <script src="./About_files/jquery.min.js.download"></script>
    <script src="./About_files/popper.min.js.download"></script>
    <script src="./About_files/jquery.unobtrusive-ajax.min.js.download"></script>
    <script src="./About_files/bootstrap.min.js.download"></script>

    


<!-- Visual Studio Browser Link -->
<script type="text/javascript" src="./About_files/browserLink" async="async" id="__browserLink_initializationData" data-requestid="a2a43851a8b24832bc66dd5e5110abde" data-requestmappingfromserver="False"></script>
<!-- End Browser Link -->





</body></html>