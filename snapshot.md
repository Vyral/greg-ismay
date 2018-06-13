---
layout: page
title: Raleigh Home Value Snapshot
permalink: /snapshot/
---

<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
  <title>FREE Market Snapshot</title>


 <link href="http://fonts.googleapis.com/css?family=Anton|Cabin" rel="stylesheet" type="text/css">
<style>

  #leftwrap {
  float: left;
  width: 70%;
  color: #f8f9fb;
  font-size: 18px;
  }
  #rightwrap {
  float: left;
  width: 30%
  }
  #leftwrap h1 {
  color: #d51111;
  font-family: 'Nunito', Arial, sans-serif;
  text-transform: uppercase;
  font-weight: normal;
  font-size: 48px;
  line-height: 60px;
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.35);
  margin: 0;
  padding: 0;
  }
  .free {
  font-size: 80px;
  color: #C2CC46;
  }
  #leftwrap p {
  padding: 0px;
  margin: 5px 0px;
  }
  #leftwrap .arrow{
  font-family: 'Anton', Arial, sans-serif;
  color: #222;
  font-size: 20px;
  line-height: 40px;
  text-transform: uppercase;
  background-image: url('http://www.topproducer.com/campus/images/external/ms-landing-pages/images/arrow.png');
  background-repeat: no-repeat;
  background-size: 90% 100%;
  height: 50px;
  margin: 0px;
  padding-top: 10px;
  padding-left: 8px;
  }
  #leftwrap ul {
  padding: 0px;
  }
  #slidepics {
  display:none;
  }
  #banner {
  background-color: #111;
  margin: 0 -1000px;
  padding: 1px 1000px;
  font-family: 'Anton', Arial, sans-serif;
  text-transform: uppercase;
  font-size: 2.2em;
  text-align: center;
  color: #e6e6e6;
  }
  #iframeWidget {
  border:5px solid #0e0e0e;
  background: url(http://www.topproducer.com/campus/images/external/ms-landing-pages/images/ms-widget-bg.jpg);
  background-repeat:no-repeat;
  background-color:#0e0e0e;
  }
  #iframeWidget:hover {
  border:5px solid #3d3d3d;
  }
  .onehalfbig {
  float: left;
  width: 50%;
  padding-top: 30px;
  }
  .onehalfsmall {
  float: left;
  width: 40%;
  padding-top: 30px;
  }
  .explain {
  font-size: 16px;
  color: #373737;
  display: block;
  background: #e3e3e3;
  margin-top: 30px;
  padding: 10px 30px;
  -webkit-border-radius: 5px 20px 5px;
  -moz-border-radius: 5px 20px 5px;
  border-radius: 5px 20px 5px;
  }
  .explain h1{
  font-size: 23px;
  color: #6f6440;
  text-transform: uppercase;
  line-height: 20px;
  }
  .explain:hover {
  background: #ffe289;
  }
  img .page {
  max-width:100% !important;
  height:auto;
  display: block;
  padding: 0px;
  }
  .single {
  padding-top: 20px;
  }

  /* AGENT INFO */
  #agentinfo {
  float: left;
  width: 47%;
  margin-top: 30px;
  padding: 10px 1.5%;
  background-color: #e8e8e8;
  height: auto;
   -moz-border-radius: 16px;
  -webkit-border-radius: 16px;
  -khtml-border-radius: 16px;
  border-radius: 16px;
  }
  #agentphoto {
  float: left;
  padding-right: 5%;
  max-width: 25%;
  }
  #agentphoto img {
  max-height: 120px;
  max-width: 25%;
  padding: 0;
  margin: 0;
  }
  #agentcontact {
  float: left;
  width: 70%;
  max-height: 120px;
  }
  #agentcontact span {
  display: block;
  font-size: 12px;
  line-height: 15px;
  color: #444;
  word-break: break-all;
  }
  #agentname {
  font-weight: bold;
  }
  #agentlogo {
  float: right;
  max-width: 110px;
  max-height: 80px;
  }
  #agentlogo img {
  padding: 0;
  }
  /*BUTTONS*/
  #buttonwrapper {
  float: left;
  width: 47%;
  margin-top: 30px;
  margin-left: 2%;
  }
   #btncontainer {
   width: 100%;
   list-style: none;
    margin: 0;
    padding: 0;
    }
    a.button {
   display: block;
   position: relative;
   height: 2em;
   width: 100%;
   text-decoration: none;
   font-size: 1.5em;
   font-weight: bold;
   line-height: 2em;
   text-align: center;
   -webkit-border-radius: 16px;
   -moz-border-radius: 16px;
   border-radius: 16px;
   text-transform: uppercase;
   margin-bottom: 8px;
    }

    a.button:before,
    a.button:after {
   content: '';
   position: absolute;
   left: -1px;
   height: 2em;
   width: 100%;
   bottom: -1px;

   -webkit-border-radius: 16px;
   -moz-border-radius: 16px;
   border-radius: 16px;
    }

    a.button:before {
   height: 23px;
   bottom: -4px;
   border-top: 0;

   -webkit-border-radius: 0 0 16px 16px;
   -moz-border-radius: 0 0 16px 16px;
   border-radius: 0 0 16px 16px;

   -webkit-box-shadow: 0 1px 1px 0px #bfbfbf;
   -moz-box-shadow: 0 1px 1px 0px #bfbfbf;
   box-shadow: 0 1px 1px 0px #bfbfbf;
    }

    /* red */
    a.red,
    a.red:hover,
    a.red:visited {
   color: #fff;
   border-bottom: 4px solid #951111;
   text-shadow: 0px 1px 0px #951111;
   background: #de0c0c;
    }
    .red:before,
    .red:after {
   border: 1px solid #951111;
   border-bottom: 1px solid #951111;
    }
    a.red:hover {
   background: #ff4242;
    }

    /* GREEN */
    a.green,
    a.green:hover,
    a.green:visited {
   color: #fff;
   border-bottom: 4px solid #448123;
   text-shadow: 0px 1px 0px #448123;
   background: #60a938;
    }
    .green:before,
    .green:after {
   border: 1px solid #448123;
   border-bottom: 1px solid #448123;
    }
    a.green:hover {
   background: #46c500;
    }

    /* ACTIVE STATE */
    a.button:active {
   border: none;
   bottom: -4px;
   margin-bottom: 22px;

   -webkit-box-shadow: 0 1px 1px #fff;
   -moz-box-shadow:  0 1px 1px #fff;
   box-shadow:  1px 1px 0 #fff, inset 0 1px 1px rgba(0, 0, 0, 0.3);
    }

    a.button:active:before,
    a.button:active:after {
   border: none;

   -webkit-box-shadow: none;
   -moz-box-shadow: none;
   box-shadow: none;
    }

    /* MODERNIZR FALLBACK */
    .no-cssgradients a.button, .no-cssgradients a.button:visited,
    .no-borderradius a.button, .no-borderradius a.button:visited,
    .no-generatedcontent a.button, .no-generatedcontent a.button:visited {
   background: url(images/sprite.png) no-repeat 0 0px;
   height: 32px;
   width: 82px;
    }

    .no-cssgradients a.button:hover,
    .no-borderradius a.button:hover,
    .no-generatedcontent a.button:hover {
   background: url(images/sprite.png) no-repeat 0 -32px;
    }

    .no-cssgradients a.button:active,
    .no-borderradius a.button:active,
    .no-generatedcontent a.button:active {
   background: url(images/sprite.png) no-repeat 0 -64px;
   bottom: 0;
   line-height: 35px;
    }

    .no-cssgradients a.red,
    .no-cssgradients a.red:visited,
    .no-cssgradients a.red:hover { background-position-x: -82px; }

    .no-cssgradients a.green,,
    .no-cssgradients a.green:visited,
    .no-cssgradients a.green:hover { background-position-x: -246px; }

    .no-cssgradients a.button, .no-cssgradients a.button:visited, .no-cssgradients a.button:hover, .no-cssgradients a.button:before, .no-cssgradients a.button:after,
    .no-borderradius a.button, .no-borderradius a.button:visited, .no-borderradius a.button:hover, .no-borderradius a.button:before, .no-borderradius a.button:after,
    .no-generatedcontent a.button, .no-generatedcontent a.button:visited, .no-generatedcontent a.button:hover, .no-generatedcontent a.button:before, .no-generatedcontent a.button:after {
   border: 0;
    }

  /* iPad Landscape */
  @media only screen and (min-width: 768px) and (max-width: 1200px) {
   #banner {
   font-size: 2em;
   }
   .onehalfsmall {
   padding-top: 50px;
   }
   .explain h1{
   font-size: 19px;
   }
  }

  /* Tablet Portrait size to standard 960 (devices and browsers) */
  @media only screen and (min-width: 768px) and (max-width: 959px) {
   #agentlogo {
   max-width: 85px;
   }
  }

  /* Mobile Landscape Size to Tablet Portrait (devices and browsers) */
  @media only screen and (min-width: 550px) and (max-width: 767px) {
   #slidewrap {
   display:none;
   }
   #slidepics {
   display:inline;
   }
   #leftwrap {
   font-size: 16px;
   line-height: 18px;
   width: 65%;
   }
   #header h1 {
   font-size: 34px;
   }
   #topcontent {
   padding-top: 20px;
   }
   .explain {
   font-size: 13px;
   }
   .arrow {
   font-size: 19px;
   }
   #banner {
   font-size: 1.5em;
   }
   .onehalfbig {
   float: none;
   width: 100%;
   padding-top: 0px;
   }
   .onehalfsmall {
   margin: 0 auto;
   float: none;
   width: 80%;
   padding-top: 10px;
   text-align: center;
   }
   #agentinfo {
   float: none;
   width: 95%;
   height: 120px;
   }
   #buttonwrapper {
   float: none;
   width: 95%;
   }
  }

  /* Mobile Portrait Size to Mobile Landscape Size (devices and browsers) */
  @media only screen and (min-width: 420px) and (max-width: 549px) {
   #leftwrap {
   display: none;
   }
   #rightwrap {
   margin: 0 auto;
   float: none;
   width: 100%;
   text-align: center;
   background-image: url('http://www.topproducer.com/campus/images/external/ms-landing-pages/images/scroll-dark.png');
   background-position: right top;
   background-repeat: repeat-y;
   }
   #topcontent {
   padding-top: 20px;
   }

   #header h1 {
   font-size: 28px;
   text-align: center;
   }
   #header h2 {
   font-size: 19px;
   text-align: center;
   }
   #banner {
   font-size: 1.2em;
   }
   .onehalfbig {
   float: none;
   width: 100%;
   padding-top: 0px;
   }
   .onehalfsmall {
   margin: 0 auto;
   float: none;
   width: 80%;
   padding-top: 10px;
   text-align: center;
   }
   #agentinfo {
   float: none;
   width: 95%;
   height: 120px;
   }
   #buttonwrapper {
   float: none;
   width: 95%;
   }
   .ribbon {
   display:none;
   }
  }
/* Mobile Portrait Size to Mobile Landscape Size (devices and browsers) */
@media only screen and (max-width: 419px) {
   #topcontent {
   padding: 15px;
   }
   #leftwrap {
   display: none;
   }
   #rightwrap {
   margin: 0 auto;
   float: none;
   width: 100%;
   text-align: center;
   padding: 0px;
   background-image: url('http://www.topproducer.com/campus/images/external/ms-landing-pages/images/scroll-dark.png');
   background-position: center;
   background-repeat: repeat-x;
   }

   #header h1 {
   font-size: 19px;
   text-align: center;
   }
   #header h2 {
   font-size: 15px;
   text-align: center;
   }
   #banner {
   font-size: 1.4em;
   }
   .onehalfbig {
   float: none;
   width: 100%;
   padding-top: 0px;
   }
   .onehalfsmall {
   margin: 0 auto;
   float: none;
   width: 80%;
   padding-top: 10px;
   text-align: center;
   }
   .explain h1{
   font-size: 16px;
   }
   #agentinfo {
   float: none;
   width: 95%;
   min-height: 120px;
   }
   #agentlogo img {
   display: none;
   }
   #buttonwrapper {
   float: none;
   width: 95%;
   }
   .ribbon {
   display:none;
   }
  }

  </style>
 <link href="http://www.topproducer.com/campus/images/external/ms-landing-pages/responsiveslides.css" rel="stylesheet">
    <link href="http://www.topproducer.com/campus/images/external/ms-landing-pages/themes/themes.css" rel="stylesheet">
  <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
  <script src="http://www.topproducer.com/campus/images/external/ms-landing-pages/responsiveslides.min.js"></script>
  <script>
    // You can also use "$(window).load(function() {"
    $(function () {
      // Slideshow 1
      $("#slider1").responsiveSlides({
        maxwidth: 620,
        speed: 500,
  timeout: 4000,
  namespace: "centered-btns",
        nav: true
      });
    });
  </script>

  </head>

<body>

 <img class="ribbon" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/ribbon.png" style="border: none; padding: 0; position: absolute; right: 0; top: 0;" />

 <!-- WRAPPER START -->
    <div id="wrapper">

 <!-- CONTENT START -->
 <div id="content">

 <!-- HEADER START -->
 <div id="headerwrapper">
 <div id="header">
 <h1>
Sign up for a FREE Market Report</h1>
<h2>
Latest Market Conditions sent to your email</h2>
</div>
</div>
<!-- HEADER ENDS -->


<!-- TOP CONTENT START -->
 <div id="topcontent">

  <!-- LEFT WRAPPER START -->
   <div id="leftwrap">
   <!-- Slideshow 1 -->
   <div id="slidewrap">
   <!-- Slideshow 1 -->
   <ul class="rslides" id="slider1">
<li><img class="page" alt="market snapshot features" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/slide1.png" /></li>
<li><img class="page" alt="market snapshot features" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/slide2.png" /></li>
<li><img class="page" alt="market snapshot features" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/slide3.png" /></li>
<li><img class="page" alt="market snapshot features" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/slide4.png" /></li>
</ul>
</div>
<div id="slidepics">
   <img class="page" alt="market snapshot features" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/slidepic.png" />
   </div>
</div>
<!-- LEFT WRAPPER ENDS -->

   <!-- RIGHT WRAPPER START -->
   <div id="rightwrap">
    <!-- iFRAME DIV -->
    <div>
    <!-- iFRAME -->
     <iframe allowtransparency="true" frameborder="0" id="iframeWidget" scrolling="no" src="http://www.homeinsight.com/Widget/default.asp?SJ441XV2BBJW" style="height: 380px; width: 175px;"></iframe>    </div>
<!-- iFRAME DIV ENDS -->
   </div>
<!-- RIGHT WRAPPER ENDS -->
  <div style="clear: both;">
</div>
</div>
<!-- TOP CONTENT ENDS -->


  <!-- BANNER START -->
  <div id="banner">
  Become a market insider! Sign up is absolutely FREE.<br />

  </div>
<!-- BANNER ENDS -->

  <!-- MS EXPLAINATION #1 -->
  <div class="onehalfsmall">
   <img class="page" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/onscreen.png" />
  </div>
<div class="onehalfbig">
   <div class="explain">
   <h1>
What am I signing up for?</h1>
Market Snapshot will enable you to view all the active and recently sold listings and compare all aspects of the listings enabling you to make a more educated and informed decision.<br />

   </div>
</div>
<div style="clear: both;">
</div>
<!-- MS EXPLAINATION #2 -->
  <div class="onehalfbig">
   <div class="explain">
   <h1>
View your reports anywhere!</h1>
You can now get all that information to any of your devices. View real time market statistics on the go!<br />

   </div>
</div>
<div class="onehalfsmall">
<img class="page" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/devices.png" /></div>
<div style="clear: both;">
</div>
<!-- MS EXPLAINATION #3 -->
  <div class="single">
  <img class="page" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/msscreenshot1.png" />
  </div>
<div class="explain">
   <h1>
Full statistics and community info</h1>
Get the latest trends for your neigborhood for sold homes, properties for sale, inventory counts, and even "day-on-market". You can also view information regarding schools and community.<br />

   </div>
<!-- MS EXPLAINATION #4 -->
  <div class="single">
  <img class="page" src="http://www.topproducer.com/campus/images/external/ms-landing-pages/images/msscreenshot2.png" />
  </div>
<div class="explain">
   <h1>
Get detailed info about every property</h1>
View all the detailed information around your area with the listing view or the map view. The report shows you all the information you will need to make any Real Estate decision.<br />

   </div>
<div style="clear: both;">
</div>
<!--AGENT INFO START-->

<div id="agentinfo">
<div id="agentphoto">
<img src="http://i842.photobucket.com/albums/zz344/VyralMarketing/Greg-Head-shot_zps844776e8.png" /></div>
<div id="agentcontact">
<span id="agentname">Greg Ismay</span><span id="agentcomapny">Ismay Realty Group</span><span id="agentdirectphone">(919) 882-6005</span><span id="agentofficephone"></span><span id="agentemail"><a href="mailto:greg@gregismay.com">greg@gregismay.com</a></span><span id="agentwebsite"><a href="http://www.searchhomesinraleigh.com/" target="blank">http://www.searchhomesinraleigh.com/</a></span><span id="agentadditional"></span></div>
</div>
<div id="buttonwrapper">
<ul id="btncontainer">
<li><a class="button red" href="http://www.marketsnapshot.info/reports?cnsmr=False&amp;Sample=1" target="_blank">Sample Report</a></li>
<li><a class="button green" href="/snapshot/">Sign up NOW</a></li>
</ul>
</div>
<!--BUTTONS ENDS-->

  <div style="clear: both;">
</div>
<br />
  <div align="center" id="myft" style="font-family: Verdana,Arial; font-size: 10px;">
</div>
<!-- BANNER START -->
  <div id="banner">
  It's Easy! Get Real Estate insights to your email today.<br />

  </div>
<!-- BANNER ENDS -->

 </div>
<!-- CONTENT ENDS -->

 </div>
<!-- WRAPPER ENDS -->
 <div id="highlight">
</div>
</body>
</html>
