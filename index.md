<html>
 <head>
 <script>
    //WOOPRA SNIPPET:
    //initialize tracker object on page and create queues for funciton calls
    //and async load tracker.
    !function(){var a,b,c,d=window,e=document,f=arguments,g="script",h=["config","track","trackForm","trackClick","identify","visit","push","call"],i=function(){var a,b=this,c=function(a){b[a]=function(){return b._e.push([a].concat(Array.prototype.slice.call(arguments,0))),b}};for(b._e=[],a=0;a<h.length;a++)c(h[a])};for(d.__woo=d.__woo||{},a=0;a<f.length;a++)d.__woo[f[a]]=d[f[a]]=d[f[a]]||new i;b=e.createElement(g),b.async=1,b.src="//static.woopra.com/js/w.js",c=e.getElementsByTagName(g)[0],c.parentNode.insertBefore(b,c)}("woopra"); /*This function is invoked with the tracker object name.  You can change this if you like. See below*/

    //WOOPRA TRACKER:
    // configure tracker
    //There are many options you can pass here to configure the tracker.
    //All options have sane defaults.
    //The only REQUIERD option to set is your 
    //  project name in the "domain" property
    woopra.config({
     domain: "niveditashinde.github.io" //This is the minimum required config
    });

    // track pageview
    woopra.track(); //With no arguments, the track funciton will track a default pageview event. See docs for woopra.track() function
  </script>

  </head>
  <body>
 <h1> Hello world</h1>
 </body>
 </html>
