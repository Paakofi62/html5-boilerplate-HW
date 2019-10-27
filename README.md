# html5-boilerplate-HW
<!doctype html> <!--this is used to inform a website that the document is a html documeent-->
<html class="no-js" lang=""> <!-- no-js replaces js when modernizer runs and allows different css rules which depends on javascript. lang is used to set the primary language for the html code  -->

<head> <!-- is a container for a metadata, placed between <html> and <body> this about how the html document will be run -->
  <meta charset="utf-8"><!--  is used to specify the character encoding for the html document. UTF-8 specifies the character encoding for the unicode -->
  <title></title> <!-- defines the title of a html document, provides a title for search engine for the website -->
  <meta name="description" content=""> <!-- describes and summarizes the contents of the page, makes it easier for the user and search engines to understand the purpose of the website. -->
  <meta name="viewport" content="width=device-width, initial-scale=1"> <!-- sets the width of the viewpoint to make sure it matches the width of the device. initial-scale=1 sets the initial zoom level when you visit the page -->

  <link rel="manifest" href="site.webmanifest"> <!-- A JSON file that tells the browser about the web application and how it should behave when installed on users mobile drive or desktop -->
  <link rel="apple-touch-icon" href="icon.png"> <!-- makes website look appealing and functional to IOS users -->
  <!-- Place favicon.ico in the root directory -->

  <link rel="stylesheet" href="css/normalize.css"> <!-- specifies the relationship between the html file and the normalize.css,  the relationship being stylesheet -->
  <link rel="stylesheet" href="css/main.css"> <!-- specifies the relationship between the html file and the main.css, the relationship being stylesheet -->

  <meta name="theme-color" content="#fafafa"> <!-- checks if a single theme-color is specified in the <head>, the cole of the header bar/background color -->
</head>

<body> <!-- defines the document body,contains all the contents of the html documents(text,hyperlinks,images,tables) -->
  <!--[if IE]>
    <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
  <![endif]-->

  <!-- Add your site or application content here -->
  <p>Hello world! This is HTML5 Boilerplate.</p> <!-- represents  a paragraph and the majority of the website content can be find in this line of code --> 
  <script src="js/vendor/modernizr-{{MODERNIZR_VERSION}}.min.js"></script> <!-- modernizr is a javascript library that detects hmtl5 and css features in the web browse --> 
   <script src="https://code.jquery.com/jquery-{{JQUERY_VERSION}}.min.js" integrity="{{JQUERY_SRI_HASH}}" crossorigin="anonymous"></script>
  <script>window.jQuery || document.write('<script src="js/vendor/jquery-{{JQUERY_VERSION}}.min.js"><\/script>')</script>
  <script src="js/plugins.js"></script>
  <script src="js/main.js"></script>

  <!-- Google Analytics: change UA-XXXXX-Y to be your site's ID. -->
  <script>
    window.ga = function () { ga.q.push(arguments) }; ga.q = []; ga.l = +new Date;
    ga('create', 'UA-XXXXX-Y', 'auto'); ga('set','transport','beacon'); ga('send', 'pageview')
  </script>
  <script src="https://www.google-analytics.com/analytics.js" async></script>
</body>

</html>
