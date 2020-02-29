# StyleSlider
Control style properties with range input elements

<a href="https://diwsi.github.io/styleslider/index.html">Online demo here!</a>
<br><br><b>Usage</b><br>
Declare controller inputs using required properties. Mark target inputs with <b>StyleSlider</b> class.
<br>
<br>
&lt;input type="range" class="StyleSlider" min="0" max="1" step="0.1" 
data-target="img" value="1" data-style="opacity:#" /&gt;
<br>
<br>
Call   <b>StyleSlider.Init()</b> method to initialize sliders.
<br><br>
<b>Properties</b><br>
<b>data-target:</b> Sets target elements to manuplate. Can be any <b>querySelector</b> parameter like class,id or tag name.<br><i> eg: data-target=".className", data-target="#idName", data-target="img" </i><br> <br> 
<b>data-style:</b> Sets style template to control. "#" charecter will be replaced with the controllers value.<br> <i>eg: data-style="font-size:#pt" , data-style="opacity:#" </i> <br>
<b>data-event:</b>Controller event name to bind changes. "input" by default.<br>
<i>eg:input,change</i>
