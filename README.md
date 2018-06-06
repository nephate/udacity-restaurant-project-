# udacity-restaurant-project-
&lt;!DOCTYPE html> &lt;html>  &lt;head>   &lt;!-- Normalize.css for better cross-browser consistency -->   &lt;link rel="stylesheet" src="//normalize-css.googlecode.com/svn/trunk/normalize.css" />   &lt;!-- Main CSS file -->   &lt;link rel="stylesheet" href="css/styles.css" type="text/css">   &lt;title>Restaurant Info&lt;/title> &lt;/head>  &lt;body class="inside">   &lt;!-- Beginning header -->   &lt;header>     &lt;!-- Beginning nav -->     &lt;nav>       &lt;h1>&lt;a href="/">Restaurant Reviews&lt;/a>&lt;/h1>     &lt;/nav>     &lt;!-- Beginning breadcrumb -->     &lt;ul id="breadcrumb" >       &lt;li>&lt;a href="/">Home&lt;/a>&lt;/li>     &lt;/ul>     &lt;!-- End breadcrumb -->     &lt;!-- End nav -->   &lt;/header>   &lt;!-- End header -->    &lt;!-- Beginning main -->   &lt;main id="maincontent">     &lt;!-- Beginning map -->     &lt;section id="map-container">       &lt;div id="map">&lt;/div>     &lt;/section>     &lt;!-- End map -->     &lt;!-- Beginning restaurant -->     &lt;section id="restaurant-container">       &lt;h1 id="restaurant-name">&lt;/h1>       &lt;img id="restaurant-img">       &lt;p id="restaurant-cuisine">&lt;/p>       &lt;p id="restaurant-address">&lt;/p>       &lt;table id="restaurant-hours">&lt;/table>     &lt;/section>     &lt;!-- end restaurant -->     &lt;!-- Beginning reviews -->     &lt;section id="reviews-container">       &lt;ul id="reviews-list">&lt;/ul>     &lt;/section>     &lt;!-- End reviews -->   &lt;/main>   &lt;!-- End main -->    &lt;!-- Beginning footer -->   &lt;footer id="footer">     Copyright (c) 2017 &lt;a href="/">&lt;strong>Restaurant Reviews&lt;/strong>&lt;/a> All Rights Reserved.   &lt;/footer>   &lt;!-- End footer -->    &lt;!-- Beginning scripts -->   &lt;!-- Database helpers -->   &lt;script type="text/javascript" src="js/dbhelper.js">&lt;/script>   &lt;!-- Main javascript file -->   &lt;script type="text/javascript" src="js/restaurant_info.js">&lt;/script>   &lt;!-- Google Maps -->   &lt;script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyA_tKbW6A5pQ-eupxI56myUnHLqYCzOjKo&amp;libraries=places&amp;callback=initMap">&lt;/script>   &lt;!-- End scripts -->  &lt;/body>  &lt;/html>
