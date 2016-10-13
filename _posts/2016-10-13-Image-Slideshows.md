---
title: Image Slideshows
layout: post
author: alex.walker
permalink: /image-slideshows/
source-id: 1HpwFpgBzhezbHq76gp9Q_iB1S4s7HTU2EfuawowWQFs
published: true
---

<table>
  <tr>
    <td>Title:  </td>
    <td>Creating and Embedding Image Slideshows</td>
    <td> Date:  </td>
    <td>13/10/16</td>
  </tr>
</table>

<table><td><p>I went on to Google and searched how do you make a image slideshow. I read through the results and I found the webpage <a href="http://www.starplugins.com/killercarousel/tutorials/image-carousel">that</a> solved the puzzle.</p>

<p> I copied and pasted in the code and edited some of the images. I was aiming for a sports theme. If the slideshow goes to plan I would like these images put in it.</p>
<ul>
<li> Wayne Rooney Bicycle Kick</li>
<li> AB De Villiers "Fastest ODI Hundred"</li>
<li> Andy Murray Winning Wimbledon</li>
<li> Middlesex winning the County Championship 2016</li>
<li> England winning The Six Nations</li>
<li> Europe winning the Ryder Cup </li>
<li> England Winning the World Cup in 1966</li>
<li> Stokes' Double Hundred</li>
<li> Leicester win the Premier League </li>
<li> DCGS winning the Vase</li>
</ul>
<p> This is my first attempt at itand I shall leave it like this whatever happens.</p></td></table>
<table>
<td>  
    <head>
        <title>Killer Carousel Image Carousel</title>

        <!-- Include jQuery. -->
        <script src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
        
        <!-- Include KillerCarousel CSS. -->
        <link href="killercarousel.css" type="text/css" rel="stylesheet" />
        
        <!-- Include KillerCarousel JavaScript. -->
        <script type="text/javascript" src="killercarousel.js"></script>
       
        <!-- Style for the carousel items. -->
        <style type = "text/css">

            /* CSS for images inside item wrapper */
            .kc-item img {
                position:absolute;
                pointer-events: none;   /* Make images non-selectable. */
                width:100%;             /* Make images expand to wrapper size (used in 2d modes). */
            }
        </style>

        <script type = "text/javascript">
		
            // Create the carousel.
            $(function() {
                $('.kc-wrap').KillerCarousel({
                    // Default natural width of carousel.
                    width: 800,
                    // Item spacing in 3d (has CSS3 3d) mode.
                    spacing3d: 120,
                    // Item spacing in 2d (no CSS3 3d) mode. 
                    spacing2d: 120,
                    showShadow: true,
                    showReflection: true                    
                });
            });
        </script>        
        </head>

        <!-- The carousel wrapper. -->
        <div class = "kc-wrap">

            <!-- Carousel items follow -->
            <div class="kc-item">
                <img src="http://images.theage.com.au/2011/02/13/2182537/svROONEY-420x0.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://st1.criclife.com/wp-content/uploads/2015/01/de-villiers-hundred.jpg" alt = "" >
            </div> 
            <div class="kc-item">
                <img src="http://images.radiotimes.com/namedimage/Can_Andy_Murray_win_Wimbledon_.jpg?quality=85&mode=crop&width=620&height=374&404=tv&url=/uploads/images/original/33239.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://i3.getwestlondon.co.uk/incoming/article11931166.ece/ALTERNATES/s1200/GettyImages-609946994.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://cdn.greenandgoldrugby.com/804F73/gagr/wp-content/uploads/2016/03/England-Grand-Slam-celebration-2016.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://cdn.images.express.co.uk/img/dynamic/1/590x/Europe-win-Ryder-Cup-516467.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://i.dailymail.co.uk/i/pix/2010/05/15/article-1278635-009D9B0F00000259-673_468x578.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://i.dailymail.co.uk/i/pix/2016/01/03/10/2FC2453700000578-3382643-image-a-91_1451817146080.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://level10living.co.uk/wp-content/uploads/2016/05/Leicester-City-Win-Premier-League.jpg" alt = "" >
            </div>
            <div class="kc-item">
                <img src="http://i.telegraph.co.uk/multimedia/archive/03595/DrC1_3595679b.jpg" alt = "" >
            </div>

        </div>
                  
    
</td>
</table>
<table>
<td>
<p>I was wondering, "How do I embed this Google Sheet onto my Github blog?"</p>
</td>
</table>
<table>
<td>
<img src="https://imagizer.imageshack.us/v2/1366x352q90/924/7opDcc.png">
</td>
</table>
<table>
<td>
So I did and voilaaaaaa, this is what I got!
</td>
</table>
<table>
<td>
<center>
<iframe src="https://docs.google.com/spreadsheets/d/1Kdv6faxP1GgXb0eQf-W2uClGqUEVXkrym98WAmdV0MQ/pubhtml?widget=true&amp;headers=false"></iframe>
</center>
</td>
</table>

