<html lang="en">
    <head>
        <title>Home &#8211; Hema Prathaban</title>
    

    <meta name="author" content="Hema Prathaban" />
    <meta name="description" content=" Home" />

    <link rel="start" href="/" />

   
   

    <link rel="stylesheet" href="https://github.com/madhur/madhur.github.com/blob/master/files/css/bootstrap.min.css" type="text/css" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="https://github.com/madhur/madhur.github.com/blob/master/files/font-awesome/css/font-awesome.min.css" type="text/css" />
    <link rel="stylesheet" href="https://github.com/madhur/madhur.github.com/blob/master/files/css/jquery.fancybox.css" type="text/css" />

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

        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#mainmenu">
          <!--  <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>-->
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
            </li>
        </ul>




    </div>

</div>
</nav>


            </header>
       
        <div id="content" class="row">

            <section  class="col-md-9">
	<h1>Intro</h1>

<p>I am  HemaPrathaban. I am freelancer. I work as Kernel and Debian
developer. I had opportunity  to be first women from India to be part
of OPW. It is still the gateway for women for being part of
opensource. I am one of the intern  of linux kernel 2013 batch
I had made contributions in Linux thermal sensor and Linux kernel staging tree.

I work as Debian developer and involved in packaging and maintaining
Linux kernel, touch driver, custom Firefox based browser, Debian and
calarames installer, and meta packages for the Debain derived
operating system.</p>
</section>
</div>

<div class="c"></div>
	

	



	

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
