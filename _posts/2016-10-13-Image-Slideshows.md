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
    <div id="slideshow">
   <div>
     <img src="http://images.theage.com.au/2011/02/13/2182537/svROONEY-420x0.jpg">
   </div>
   <div>
     <img src="http://st1.criclife.com/wp-content/uploads/2015/01/de-villiers-hundred.jpg">
   </div>
   <div>
     <img src="http://images.radiotimes.com/namedimage/Can_Andy_Murray_win_Wimbledon_.jpg?quality=85&mode=crop&width=620&height=374&404=tv&url=/uploads/images/original/33239.jpg">
   </div>
</div>
  $("#slideshow > div:gt(0)").hide();

setInterval(function() { 
  $('#slideshow > div:first')
    .fadeOut(1000)
    .next()
    .fadeIn(1000)
    .end()
    .appendTo('#slideshow');
},  3000);                
    
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

