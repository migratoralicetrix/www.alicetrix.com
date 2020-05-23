

<script type="text/javascript" src="/about/About_files/jquery-1.7.1.min.js.download"></script>


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





  

