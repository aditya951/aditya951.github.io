lorem10 +tab   //to get sentence of 10 words

position: fixed;
  An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:
An element with position: relative; is positioned relative to its normal position.
Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.
An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.
A fixed element does not leave a gap in the page where it would normally have been located.
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.
An element with position: sticky; is positioned based on the user's scroll position.
A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).
=========================================================================================================================================
height: 100vh;
VH
height: 100vh; means the height of this element is equal to 100% of the viewport height.

example: height: 50vh;
If your screen height is 1000px, your element height will be equal to 500px (50% of 1000px).
===============================================================================================================================
z-index: 100;
The z-index property specifies the stack order of an element.
An element with greater stack order is always in front of an element with a lower stack order.
============================================================================================================
transform: translateX(-100%);  translate element in -x axix fully
===========================================================================================================
  text-align: center;
The text-align property specifies the horizontal alignment of text in an element.
================================================================================================
max-width: 100%;
The max-width property defines the maximum width of an element.
If the content is larger than the maximum width, it will automatically change the height of the element.
==============================================================================================================
overflow: hidden
The overflow property specifies whether to clip the content or to add scrollbars when the content of an element is too big to fit in the specified area.
===================================================================================================
@keyframes modalopen
the @keyframes rule specifies the animation code.
The animation is created by gradually changing from one set of CSS styles to another.
During the animation, you can change the set of CSS styles many times.
Specify when the style change will happen in percent, or with the keywords "from" and "to", which is the same as 0% and 100%. 0% is the beginning of the animation, 100% is when the animation is complete.