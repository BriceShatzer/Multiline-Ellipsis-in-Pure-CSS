##CSS Ellipsis: How to Manage Multi-Line Ellipsis in Pure CSS

A completely CSS solution for properly cutting off multi-line text, turning a situation 

<div style="float:left">like this:
    <div style="width:200px;height:255px;overflow:hidden;border:2px solid #878787;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque sagittis mi in leo malesuada, ut bibendum ipsum semper. Cras sollicitudin, sem vitae consequat scelerisque, dolor nulla finibus ipsum, eu volutpat dolor ipsum vestibulum neque. Phasellus imperdiet diam ante, vel blandit justo malesuada a. Ut id euismod quam. Nunc facilisis ut orci id sagittis. Etiam nisi odio, consectetur sit amet vestibulum nec, varius volutpat tellus. Nunc neque elit, laoreet et rutrum vitae, fringilla vehicula urna. Morbi vehicula ipsum vitae erat pellentesque maximus vel id libero. Suspendisse id luctus quam. Suspendisse ut nibh non nulla posuere mattis quis eget augue. Pellentesque varius convallis tincidunt. Fusce semper massa quis porta venenatis. Pellentesque consequat metus vitae dapibus blandit. Aenean ullamcorper quis lacus non elementum.
    </div>
</div>

<div style="float:left; margin-left:20px;">into this:

    <div style="width:200px;height:255px;border:2px solid #878787;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque sagittis mi in leo malesuada, ut bibendum ipsum semper. Cras sollicitudin, sem vitae consequat scelerisque, dolor nulla finibus ipsum, eu volutpat dolor ipsum vestibulum neque. Phasellus imperdiet diam ante, vel blandit justo malesuada a. Ut id...
    </div>
</div>

<div style="clear:both">&nbsp;</div>
The example files were originally posted on the [Mobify Developer Blog](http://www.mobify.com/blog/), and have been reproduced here for the sake of posterity. 

Please [check out the original post](http://www.mobify.com/blog/multiline-ellipsis-in-pure-css/) to see the full explanation and view the examples in context.


