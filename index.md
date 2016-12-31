<html lang="en">
    <head>
        <title>Home &#8211; Hema Prathaban</title>
    

    <meta name="author" content="Hema Prathaban" />
    <meta name="description" content=" Home" />

    <link rel="start" href="/" />

   
   

    <link rel="stylesheet" href="https://github.com/madhur/madhur.github.com/blob/master/files/css/bootstrap.min.css" type="text/css" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="https://github.com/madhur/madhur.github.com/blob/master/files/font-awesome/css/font-awesome.min.css" type="text/css" />
    <link rel="stylesheet" href=https://github.com/madhur/madhur.github.com/blob/master/files/css/jquery.fancybox.css" type="text/css" />

    <link rel="stylesheet" type="text/css" href="https://github.com/madhur/madhur.github.com/blob/master/files/css/styles.css" />
    
    

    <link rel="stylesheet" type="text/css" media="print" href="https://github.com/madhur/madhur.github.com/blob/master/files/css/print.css">

     
   
    <script src="https://github.com/madhur/madhur.github.com/blob/master/files/js/vendor/pace.min.js" type="text/javascript"></script>
</head>

<body>

    <div class="container">
       
            <header id="header" class="row">

                <nav id="navigation" class="navbar navbar-inverse navbar-fixed-top " role="navigation">
    <div class="container">

    <div class="navbar-header">

     <div class="hidden-md hidden-sm hidden-lg searchli">

                <form method="get" role="search" id="searchform" action="/results" onsubmit="return checkfrm_search();">

                    <div class="form-group">
                        <input type="search" required id="q2" name="q" value="" class="form-control mobile" placeholder="Search" />
                    </div>
                </form>
        </div>

        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#mainmenu">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
        </button>
        <!--  <a class="navbar-brand " href="/">Home</a> -->
    </div>

    <div class="collapse navbar-collapse" id="mainmenu">
        <ul id="nav" class="nav navbar-nav">
            
            <li><a class="home" href="/">Home</a>
            </li>
            <li><a class="blog" href="/blog">Blog</a>
            </li>
            <!--<li><a class="work" href="/work">Resume</a></li>-->
            <li><a class="code" href="/projects">Work</a>
            </li>
            <!--<li><a class="papers" href="/papers">Papers</a></li>-->
            <li><a class="info" href="/info">About</a>
            </li>
            <li><a class="contact" href="/contact">Contact</a>
            </li>

        </ul>

        <ul class="nav navbar-nav visible-md visible-lg visible-sm searchbox">
            <li>
                <form method="get" role="search" id="searchform" action="/results" onsubmit="return checkfrm_search();">

                    <div class="form-group">
                        <input type="search" required id="q1" name="q" value="" class="form-control desktop" placeholder="Search" />
                    </div>
                </form>
            </li>
        </ul>




    </div>

</div>
</nav>


            </header>
       
        <div id="content" class="row">

            <section  class="col-md-9">
	<h1>Intro</h1>

<p>Hi there, I&#39;m Hema, a programmer, and FOSS enthusiast in general.  I&#39;d like to present you some information on several topics of my interest. .</p>


<h2>Contact</h2>


</ul>

</section>


</div>


</aside>

<div class="c"></div>
	

	



	


        </div>

    </div>

    <script data-main="/files/js/app" src="/files/js/require.js"></script>

    
        <script type="text/javascript">
	  var _gaq = _gaq || [];
	  _gaq.push(['_setAccount', 'UA-23769089-1']);
	  _gaq.push(['_trackPageview']);

	  (function() {
		var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
		ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
		var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
	  })();

	</script>
    

    <!-- serviceWorker.html -->
<script>
if ('serviceWorker' in navigator) {
    navigator.serviceWorker.register('/serviceWorker.js').then(function(reg) {
        if (!reg.installing) return;
        console.log("[*] ServiceWorker is installing...");

        var worker = reg.installing;
        worker.addEventListener('statechange', function() {
            if (worker.state == 'redundant') {
                console.log('[*] Install failed');
            }
            if (worker.state == 'installed') {
                console.log('[*] Install successful!');
            }
        });
    });
}

</script>

</body>

</html>
