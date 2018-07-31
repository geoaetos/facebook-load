facebook-load
=============

facebook load
function downloadJSAtOnload()
{var element = document.createElement(&quot;script&quot;)
;element.src = &quot;//connect.facebook.net/en_US/all.js#xfbml=1&quot;;
document.body.appendChild(element);}if (window.addEventListener)
window.addEventListener(&quot;load&quot;, downloadJSAtOnload, false)
;else if (window.attachEvent)window.attachEvent(&quot;onload&quot;,
downloadJSAtOnload);
else window.onload = downloadJSAtOnload;
see live <a href="https://www.aetos-apokalypsis.com/" title="ΕΛΕΥΘΕΡΟΣ ΑΕΤΟΣ"  target="_blank">ΕΛΕΥΘΕΡΟΣ ΑΕΤΟΣ</a>  
