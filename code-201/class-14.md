# CSS TRANSFORMS: <br>
- <br>
- <br>
- <br>
- <br>
- <br>
- background<br>
colorbackground<br>
positionborder<br>
colorborder<br>
widthborder<br>
spacingbottom<br>
clipcolor<br>
cropfont<br>
sizefont<br>
weightheight<br>
leftletter<br>
spacingline<br>
heightmarginmax<br>
heightmax<br>
widthmin<br>
heightmin<br>
widthopacity<br>
outline<br>
coloroutline<br>
offsetoutline<br>
widthpaddingrighttext<br>
indenttext<br>
shadowtopvertical<br>
alignvisibilitywidth<br>
word-spacing<br>
z-index<br>
syntax for transform property:<br>
div {<br>
  -webkit-transform: scale(1.5); <br>
     -moz-transform: scale(1.5); <br>
       -o-transform: scale(1.5);<br>
          transform: scale(1.5);<br>

Fade in<br>
Change color<br>
.color:hover<br>
{<br>
        background:#53a7ea;<br>
}<br>


Grow & Shrink<br>
.grow:hover<br>
{<br>
        -webkit-transform: scale(1.3);<br>
        -ms-transform: scale(1.3);<br>
        transform: scale(1.3);<br>
}<br>

.shrink:hover<br>
{<br>
        -webkit-transform: scale(0.8);<br>
        -ms-transform: scale(0.8);<br>
        transform: scale(0.8);<br>
}<br>

Rotate elements<br>
.rotate:hover<br>
{<br>
        -webkit-transform: rotateZ(-30deg);<br>
        -ms-transform: rotateZ(-30deg);<br>
        transform: rotateZ(-30deg);<br>
}<br>
Square to circle<br>
.circle:hover<br>
{<br>
        border-radius:50%;<br>
}<br>


3D shadow<br>
{<br>
        box-shadow:<br>
                1px 1px #53a7ea,<br>
                2px 2px #53a7ea,<br>
                3px 3px #53a7ea;<br>
        -webkit-transform: translateX(-3px);<br>
        transform: translateX(-3px);<br>
}<br>


Swing<br>
{<br>
    15%<br>
    {<br>
        -webkit-transform: translateX(5px);<br>
        transform: translateX(5px);<br>
    }<br>
    30%<br>
    {<br>
        -webkit-transform: translateX(-5px);<br>
       transform: translateX(-5px);<br>
    } <br>
    50%<br>
    {<br>
        -webkit-transform: translateX(3px);<br>
        transform: translateX(3px);<br>
    }<br>
    65%<br>
    {<br>
        -webkit-transform: translateX(-3px);<br>
        transform: translateX(-3px);<br>
    }<br>
    80%<br>
    {<br>
        -webkit-transform: translateX(2px);<br>
        transform: translateX(2px);<br>
    }<br>
    100%<br>
    {<br>
        -webkit-transform: translateX(0);<br>
        transform: translateX(0);<br>
    }<br>
}<br>
@keyframes swing<br>
{<br>
    15%<br>
    {<br>
        -webkit-transform: translateX(5px);<br>
        transform: translateX(5px);<br>
    }<br>
    30%<br>
    {<br>
        -webkit-transform: translateX(-5px);<br>
        transform: translateX(-5px);<br>
    }<br>
    50%<br>
    {<br>
        -webkit-transform: translateX(3px);<br>
        transform: translateX(3px);<br>
    }<br>
    65%<br>
    {<br>
        -webkit-transform: translateX(-3px);<br>
        transform: translateX(-3px);<br>
    }<br>
    80%<br>
    {<br>
        -webkit-transform: translateX(2px);<br>
        transform: translateX(2px);<br>
    }<br>
    100%<br>
    {<br>
        -webkit-transform: translateX(0);<br>
        transform: translateX(0);<br>
    }<br>
}<br>

*Inset border<br>
.border:hover<br>
{<br>
        box-shadow: inset 0 0 0 25px #53a7ea;<br>
}<br>
