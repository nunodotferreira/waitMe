waitMe
======

jquery plugin for easy creating loading css3 animations

<i>For work required only jQuery, other libraries are not required.</i>
<i>Plugin use css3 animation, and works on all browsers and IE10+.</i>
<br>

<a href="http://vadimsva.github.io/waitMe/" target="_blank"><b>DEMO</b></a>


<h4>Direct links to libs</h4>
<a href="http://vadimsva.github.io/waitMe/waitMe.js" target="_blank"><b>waitMe.js</b></a> [4.9Kb]<br>
<a href="http://vadimsva.github.io/waitMe/waitMe.min.js" target="_blank"><b>waitMe.min.js</b></a> [2.2Kb]<br>
<a href="http://vadimsva.github.io/waitMe/waitMe.css" target="_blank"><b>waitMe.css</b></a> [16Kb]<br>
<a href="http://vadimsva.github.io/waitMe/waitMe.min.css" target="_blank"><b>waitMe.min.css</b></a> [14.2Kb]

<br><br>

<p><i>$(container).waitMe({param1 : value1, param2 : value2, ...});</i></p>

<h5>Parameters</h5>
<code>effect</code> - animation effect (string).<br>
Use: <code>'bounce'</code> - default, <code>none</code>, <code>rotateplane</code>, <code>stretch</code>, <code>orbit</code>, <code>roundBounce</code>, <code>win8</code>, <code>win8_linear</code>, <code>ios</code>, <code>facebook</code>, <code>rotation</code>.<br>
<br>
<code>text</code> - place text under the effect (string).<br>
Use: <code>'text'</code>.<br>
<br>
<code>bg</code> - background for container (string).<br>
Use: <code>'rgba(255,255,255,0.7)'</code>. You can use color and image.<br>
<br>
<code>color</code> - color for background animation and text (string).<br>
Use: <code>'#000'</code><br>
<br>
<code>sizeW</code> - change width for elem animation (string).<br>
Use: <code>'40px'</code>. By default, use empty string.<br>
<br>
<code>sizeH</code> - change height for elem animation (string).<br>
Use: <code>'40px'</code>. By default, use empty string.<br>
<br>

<h5>Methods</h5>
<code>hide</code> - for close waitMe.<br>
Use: <code>$(container).waitMe("hide");</code><br>
<br>

<h5>Notes</h5>
For <code>sizeW</code> and <code>sizeH</code>, default sizes is:<br>
<code>bounce</code> - <code>sizeW: '20px'</code>, <code>sizeH: '20px'</code><br>
<code>rotateplane</code> - <code>sizeW: '30px'</code>, <code>sizeH: '30px'</code><br>
<code>stretch</code> - <code>sizeW: '8px'</code>, <code>sizeH: '60px'</code><br>
<code>orbit</code> - <code>sizeW: '40px'</code>, <code>sizeH: '40px'</code><br>
<code>roundBounce</code> - <code>sizeW: '60px'</code>, <code>sizeH: '60px'</code><br>
<code>win8</code> - <code>sizeW: '40px'</code>, <code>sizeH: '40px'</code><br>
<code>win8_linear</code> - <code>sizeW: '150px'</code>, <code>sizeH: '6px'</code><br>
<code>ios</code> - <code>sizeW: '40px'</code>, <code>sizeH: '40px'</code><br>
<code>facebook</code> - <code>sizeW: '6px'</code>, <code>sizeH: '25px'</code><br>
<code>rotation</code> - <code>sizeW: '60px'</code>, <code>sizeH: '60px'</code><br>
