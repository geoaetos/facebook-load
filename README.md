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
