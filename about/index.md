
<body>

   
<div class="container">
    <p>
        &nbsp;
    </p>
   
   
    
</div>
<div class="container">
        <script type="text/javascript" src="./About_files/jquery-1.7.1.min.js.download"></script>

    <p>
    </p>


<div class="row">
    <div class="col-xl-2">

        <div id="navbar1" class="nav nav-pills bg-light">
            <a id="Introduction" class="nav-link active" href="./Help/Introduction.htm" target="myframe">Introduction</a>
            <a id="Installation" class="nav-link" href="./Help/Installation.html" target="myframe">Installation</a>

            <a id="Setup" class="nav-link" href="./Help/Setup.htm" target="myframe">Setup</a>
            <a id="GoogleOnetime" class="nav-link ml-3 my-1" href="./Help/GoogleOneTimeSetup.htm" target="myframe">Google Onetime Configuration</a>
            <a id="BoxOnetime" class="nav-link ml-3 my-1" href="./Help/BoxOneTimeAuth.html" target="myframe">Box Onetime Configuration</a>
            <a id="OneDriveOnetime" class="nav-link ml-3 my-1" href="./Help/OneDriveOneTimeSetup.html" target="myframe">OneDrive &amp; SharePoint Onetime Configuration</a>
            <a id="Authentication" class="nav-link ml-3 my-1" href="./Help/Authentication.html" target="myframe">Authentication</a>
            <a id="Remediation" class="nav-link" href="./Help/Remediation.html" target="myframe">Remediation</a>
            <a id="Migration" class="nav-link" href="./Help/Migration.html" target="myframe">Migration</a>
            <a id="Advanced" class="nav-link ml-3 my-1" href="./Help/MigrationAdvanced.html" target="myframe">Advanced Concepts</a>
            <a id="Reports" class="nav-link" href="./Help/Reports.html" target="myframe">Reports</a>
            <a id="Admin" class="nav-link" href="./Help/Admin.html" target="myframe">Admin</a>
            <a id="PrivacyPolicy" class="nav-link" href="./Help/privacypolicy.html" target="myframe">Privacy Policy</a>


        </div>
    </div>
    <div class="col-xl-10">
        <div class="embed-responsive embed-responsive-1by1">

            <iframe id="frame001" class="embed-responsive-item" name="myframe" src="./Help/Introduction.htm"></iframe>
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

                            <a href="./About#" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
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
                                    Alicetrix Enterprise File Migrator software has been tested and validated in confines of generic requirements. You are expected to test and ensure software is able to meet your requirements. The software is provided "As is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software. Please direct all your queries on know-how of application to company support email address. NO SLA Applies.
                                </p>
                            </div>
                        </div>
                    </div>
                    &nbsp;
                    <h6>
                        
                        ©Copyrighted
                    </h6>

                </div>
             

                    
                       
                     
            </footer>
        </div>
        
    </hr>
    <script src="./About_files/jquery.min.js.download"></script>
    <script src="./About_files/popper.min.js.download"></script>
    <script src="./About_files/jquery.unobtrusive-ajax.min.js.download"></script>
    <script src="./About_files/bootstrap.min.js.download"></script>

    

</div>
<!-- Visual Studio Browser Link -->
<script type="text/javascript" src="./About_files/browserLink" async="async" id="__browserLink_initializationData" data-requestid="a2a43851a8b24832bc66dd5e5110abde" data-requestmappingfromserver="False"></script>
<!-- End Browser Link -->

</body></html>



