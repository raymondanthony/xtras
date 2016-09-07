[xtras](notes.md)

===

Notes, scratch, and import clips from now bloated [gist version](https://gist.github.com/rayantony/3b78ccac3b63496328f214a6676e5d91/)...


[make gh page](https://github.com/raymondanthony/xtras/generated_pages/new#)


comparison of xtrasnew,original(themeless),and medinject (left to right) as appplied to rayantony blog gh pages site.
![[](3facesofray.png "comparison of xtrasnew,original(themeless),and medinject (left to right) as appplied to rayantony blog gh pages site.")](3facesofray.png "comparison of xtrasnew,original(themeless),and medinject (left to right) as appplied to rayantony blog gh pages site.")

original line from [rayantony blog](rayantony.github.io/public/xtras.js)
```css
p,footer,header,a,article,soundmanager,video,input,post,h1,hr,h3{ animation-delay:1.5s; animation:fly-in-from-right 0.93s 1s ease both; transform-origin:top right; } top-panels,h4,h5,img,.bottom-panels,.list-group-item,list-item,list,li,ol,shop-button,shop-item,cart,ad,dl,dt,dd,figure {animation-delay:1.8s; animation:fly-in-from-left 2.93s 1.2s ease both; -webkit-animation-delay:1.8s; -webkit-animation:fly-in-from-left 2.93s 1.5s ease both; transform-origin:top left; } @keyframes fly-in-from-top { from { transform:translateX(12rem) rotate(90deg); opacity:0; } } @keyframes fly-in-from-left { from { transform:translateY(12rem) rotate(180deg); opacity:0; } } @keyframes fly-in-from-right { from { transform:translateY(12rem) rotate(-360deg); opacity:0; } }'+ 'frame,iframe,section{ animation-delay:2s; animation:fly-in-from-left 2s 2s ease both; transform-origin:top left; } body { font-size: 1.3em; line-height: 1.5; font-weight: 400; font-family: "Raleway", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif; -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol"; color: #222; background-color: #fff;} * { box-sizing: border-box; } script { display: none; }
```

additions
```css
html{
font-family: sans-serif;
margin: 0;
/* overflow: hidden; *enable and disable lower 2 to disable scroll  */ 
overflow-x: hidden;
overflow-y: scroll;
}

body{
color: rgba(0, 0, 0, 0.8);
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-size: 18px;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
line-height: 25.2px;
margin-bottom: 0px;
margin-left: 0px;
margin-right: 0px;
margin-top: 0px;
overflow-x: hidden;
text-rendering: optimizelegibility;
-moz-font-feature-settings: "liga";
}

div{
background-color: transparent;
color: rgba(0, 0, 0, 0.68);
cursor: pointer;
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
line-height: 22.4px;
list-style-image: none;
list-style-position: outside;
list-style-type: none;
text-align: left;
text-decoration: none;
text-rendering: optimizelegibility;
visibility: visible;
white-space: nowrap;
-moz-font-feature-settings: "liga";
-moz-text-decoration-color: rgba(0, 0, 0, 0.44);
-moz-text-decoration-line: none;
-moz-text-decoration-style: solid;
}

a,a:before,a.gb1,a.gb2,a.gb3,.link,a:link,.w,#prs,#prs a:active,.q:active,.q:visited,.kl:active,.tbotu{
background-color: transparent;
color:  rgb(38, 139, 210);
cursor: pointer;
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-size: 14px;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
line-height: 16.8px;
list-style-image: none;
list-style-position: outside;
list-style-type: none;
text-decoration: none;
text-rendering: optimizelegibility;
visibility: visible;
white-space: nowrap;
-moz-font-feature-settings: "liga";
-webkit-text-decoration-color:  rgb(38, 139, 210);
-moz-text-decoration-line: none;
-moz-text-decoration-style: solid;
color:rgb(38, 139, 210);
-moz-text-decoration-color: rgb(38, 139, 210);
text-decoration: none;
}
a:visited{
-moz-text-decoration-color:rgba(38, 139, 210, 0.44);
color:rgba(38, 139, 210, 0.44); /* rgba(0, 0, 0, 0.44); */
}
a:hover{
text-decoration: underline;
}
.butterBar,.gbar,.gBar,.toolbar,.menubar,#menubar{
color: rgba(0, 0, 0, 0.8);
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-size: 18px;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
line-height: 25.2px;
margin-left: 423.35px;
max-width: 640px;
opacity: 0;
pointer-events: none;
position: fixed;
text-align: center;
text-rendering: optimizelegibility;
transform: matrix(1, 0, 0, 1, 0, -100);
transition-delay: 0s, 0.7s, 0s;
transition-duration: 0.7s, 0s, 0.7s;
transition-property: transform, visibility, opacity;
transition-timing-function: cubic-bezier(0.25, 0.1, 0.25, 1), cubic-bezier(0, 0, 1, 1), cubic-bezier(0.25, 0.1, 0.25, 1);
visibility: hidden;
width: 640px;
z-index: 800;
-moz-font-feature-settings: "liga";
}
/*   */
```

additions minus font sizing
```css
html{
font-family: sans-serif;
margin: 0;
/* overflow: hidden; *enable and disable lower 2 to disable scroll  */ 
overflow-x: hidden;
overflow-y: scroll;
}

body{
color: rgba(0, 0, 0, 0.8);
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
margin-bottom: 0px;
margin-left: 0px;
margin-right: 0px;
margin-top: 0px;
overflow-x: hidden;
text-rendering: optimizelegibility;
-moz-font-feature-settings: "liga";
}

div .li{
background-color: transparent;
color: rgba(0, 0, 0, 0.68);
cursor: pointer;
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
list-style-image: none;
list-style-position: outside;
list-style-type: none;
text-align: left;
text-decoration: none;
text-rendering: optimizelegibility;
visibility: visible;
white-space: nowrap;
-moz-font-feature-settings: "liga";
-moz-text-decoration-color: rgba(0, 0, 0, 0.44);
-moz-text-decoration-line: none;
-moz-text-decoration-style: solid;
}

a,a:before,a.gb1,a.gb2,a.gb3,.link,a:link,.w,#prs,#prs a:active,.q:active,.q:visited,.kl:active,.tbotu{
background-color: transparent;
color:  rgb(38, 139, 210);
cursor: pointer;
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
list-style-image: none;
list-style-position: outside;
list-style-type: none;
text-decoration: none;
text-rendering: optimizelegibility;
visibility: visible;
white-space: nowrap;
-moz-font-feature-settings: "liga";
-webkit-text-decoration-color:  rgb(38, 139, 210);
-moz-text-decoration-line: none;
-moz-text-decoration-style: solid;
color:rgb(38, 139, 210);
-moz-text-decoration-color: rgb(38, 139, 210);
text-decoration: none;
}
a:visited{
-webkit-text-decoration-color:rgba(38, 139, 210, 0.44);
-moz-text-decoration-color:rgba(38, 139, 210, 0.44);
color:rgba(38, 139, 210, 0.44); /* rgba(0, 0, 0, 0.44); */
}
a:hover{
text-decoration: underline;
}
.butterBar,.gbar,.gBar,.toolbar,.menubar,#menubar{
color: rgba(0, 0, 0, 0.8);
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;
font-size: 18px;
font-style: normal;
font-weight: 400;
letter-spacing: 0px;
line-height: 25.2px;
margin-left: 423.35px;
max-width: 640px;
opacity: 0;
pointer-events: none;
position: fixed;
text-align: center;
text-rendering: optimizelegibility;
transform: matrix(1, 0, 0, 1, 0, -100);
transition-delay: 0s, 0.7s, 0s;
transition-duration: 0.7s, 0s, 0.7s;
transition-property: transform, visibility, opacity;
transition-timing-function: cubic-bezier(0.25, 0.1, 0.25, 1), cubic-bezier(0, 0, 1, 1), cubic-bezier(0.25, 0.1, 0.25, 1);
visibility: hidden;
width: 640px;
z-index: 800;
-moz-font-feature-settings: "liga";
}
```
additions no font size plus original, minified
```css
body,html{overflow-x:hidden;margin:0}a,article,footer,h1,h3,header,hr,input,p,post,soundmanager,video{animation:fly-in-from-right .93s 1s ease both;transform-origin:top right}.bottom-panels,.list-group-item,ad,cart,dd,dl,dt,figure,h4,h5,img,li,list,list-item,ol,shop-button,shop-item,top-panels{animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0}}frame,iframe,section{animation:fly-in-from-left 2s 2s ease both;transform-origin:top left}*{box-sizing:border-box}script{display:none}html{font-family:sans-serif;overflow-y:scroll}body{font-size:1.3em;line-height:1.5;color:#222;background-color:#fff;color:rgba(0,0,0,.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga"}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link,div .li{background-color:transparent;cursor:pointer;visibility:visible;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga"}div .li{color:rgba(0,0,0,.68);text-align:left;-moz-text-decoration-color:rgba(0,0,0,.44)}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2}a:visited{-webkit-text-decoration-color:rgba(38,139,210,.44);-moz-text-decoration-color:rgba(38,139,210,.44);color:rgba(38,139,210,.44)}a:hover{text-decoration:underline}#menubar,.butterBar,.gBar,.gbar,.menubar,.toolbar{color:rgba(0,0,0,.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-size:18px;font-style:normal;font-weight:400;letter-spacing:0;line-height:25.2px;margin-left:423.35px;max-width:640px;opacity:0;pointer-events:none;position:fixed;text-align:center;text-rendering:optimizelegibility;transform:matrix(1,0,0,1,0,-100);transition-delay:0s,.7s,0s;transition-duration:.7s,0s,.7s;transition-property:transform,visibility,opacity;transition-timing-function:cubic-bezier(.25,.1,.25,1),cubic-bezier(0,0,1,1),cubic-bezier(.25,.1,.25,1);visibility:hidden;width:640px;z-index:800;-moz-font-feature-settings:"liga"}
```
additions no font size plus original, minified in minified js injection container
```js
(function(){var style=document.createElement('style'),styleContent=document.createTextNode('body,html{overflow-x:hidden;margin:0}a,article,footer,h1,h3,header,hr,input,p,post,soundmanager,video{animation:fly-in-from-right .93s 1s ease both;transform-origin:top right}.bottom-panels,.list-group-item,ad,cart,dd,dl,dt,figure,h4,h5,img,li,list,list-item,ol,shop-button,shop-item,top-panels{animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0}}frame,iframe,section{animation:fly-in-from-left 2s 2s ease both;transform-origin:top left}*{box-sizing:border-box}script{display:none}html{font-family:sans-serif;overflow-y:scroll}body{font-size:1.3em;line-height:1.5;color:#222;background-color:#fff;color:rgba(0,0,0,.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga"}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link,div .li{background-color:transparent;cursor:pointer;visibility:visible;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga"}div .li{color:rgba(0,0,0,.68);text-align:left;-moz-text-decoration-color:rgba(0,0,0,.44)}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2}a:visited{-webkit-text-decoration-color:rgba(38,139,210,.44);-moz-text-decoration-color:rgba(38,139,210,.44);color:rgba(38,139,210,.44)}a:hover{text-decoration:underline}#menubar,.butterBar,.gBar,.gbar,.menubar,.toolbar{color:rgba(0,0,0,.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-size:18px;font-style:normal;font-weight:400;letter-spacing:0;line-height:25.2px;margin-left:423.35px;max-width:640px;opacity:0;pointer-events:none;position:fixed;text-align:center;text-rendering:optimizelegibility;transform:matrix(1,0,0,1,0,-100);transition-delay:0s,.7s,0s;transition-duration:.7s,0s,.7s;transition-property:transform,visibility,opacity;transition-timing-function:cubic-bezier(.25,.1,.25,1),cubic-bezier(0,0,1,1),cubic-bezier(.25,.1,.25,1);visibility:hidden;width:640px;z-index:800;-moz-font-feature-settings:"liga"}');style.appendChild(styleContent);var mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```
bookmarklet ver additions no font size plus original, minified in minified js injection container
```js
javascript:(function(){var style=document.createElement('style'),styleContent=document.createTextNode('body,html{overflow-x:hidden;margin:0}a,article,footer,h1,h3,header,hr,input,p,post,soundmanager,video{animation:fly-in-from-right .93s 1s ease both;transform-origin:top right}.bottom-panels,.list-group-item,ad,cart,dd,dl,dt,figure,h4,h5,img,li,list,list-item,ol,shop-button,shop-item,top-panels{animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0}}frame,iframe,section{animation:fly-in-from-left 2s 2s ease both;transform-origin:top left}*{box-sizing:border-box}script{display:none}html{font-family:sans-serif;overflow-y:scroll}body{font-size:1.3em;line-height:1.5;color:#222;background-color:#fff;color:rgba(0,0,0,.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga"}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link,div .li{background-color:transparent;cursor:pointer;visibility:visible;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga"}div .li{color:rgba(0,0,0,.68);text-align:left;-moz-text-decoration-color:rgba(0,0,0,.44)}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2}a:visited{-webkit-text-decoration-color:rgba(38,139,210,.44);-moz-text-decoration-color:rgba(38,139,210,.44);color:rgba(38,139,210,.44)}a:hover{text-decoration:underline}#menubar,.butterBar,.gBar,.gbar,.menubar,.toolbar{color:rgba(0,0,0,.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-size:18px;font-style:normal;font-weight:400;letter-spacing:0;line-height:25.2px;margin-left:423.35px;max-width:640px;opacity:0;pointer-events:none;position:fixed;text-align:center;text-rendering:optimizelegibility;transform:matrix(1,0,0,1,0,-100);transition-delay:0s,.7s,0s;transition-duration:.7s,0s,.7s;transition-property:transform,visibility,opacity;transition-timing-function:cubic-bezier(.25,.1,.25,1),cubic-bezier(0,0,1,1),cubic-bezier(.25,.1,.25,1);visibility:hidden;width:640px;z-index:800;-moz-font-feature-settings:"liga"}');style.appendChild(styleContent);var mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```

new minified version of latest css
>blue, original animations,margins,font and sizing
```css
p,footer,header,a,article,soundmanager,video,input,post,h1,hr,h3{animation-delay:1.5s;animation:fly-in-from-right 0.93s 1s ease both;transform-origin:top right;}top-panels,h4,h5,img,.bottom-panels,.list-group-item,list-item,list,li,ol,shop-button,shop-item,cart,ad,dl,dt,dd,figure{animation-delay:1.8s;animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation-delay:1.8s;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left;}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0;}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0;}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0;}}'+ 'frame,iframe,section{animation-delay:2s;animation:fly-in-from-left 2s 2s ease both;transform-origin:top left;}body{font-size:1.3em;line-height:1.5;font-weight:400;font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";color:#222;background-color:#fff;}*{box-sizing:border-box;}script{display:none;}html{font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;overflow-x:hidden;overflow-y:scroll;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;-moz-box-sizing:border-box;color:rgba(0,0,0,0.88);}body{background-color:rgba(255,255,255,0.8);color:rgba(0,0,0,0.8);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;font-style:normal;font-weight:400;letter-spacing:0px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}.wrap{backface-visibility:hidden;color:rgb(88,88,88);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-weight:400;letter-spacing:0px;position:relative;text-rendering:optimizelegibility;transition-delay:0s;transition-duration:0.3s;transition-property:transform;transition-timing-function:cubic-bezier(0.42,0,0.58,1);-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}h1,h2,h3,h4{color:rgb(49,49,49);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;margin-bottom:10px;margin-top:30px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}h4,dl{color:122,122,122}ol,ul,dt{color:rgb(68,68,68);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}p{color:rgb(88,88,88);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;font-style:normal;letter-spacing:0px;}blockquote{color:rgb(122,122,122);}btn{opacity:0;-webkit-transition:opacity 0.1s ease-in-out;transition:opacity 0.1s ease-in-out;-webkit-transform:translateZ();}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{background-color:transparent;cursor:pointer;visibility:visible;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga";}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2;}a:visited{-moz-text-decoration-color:rgba(38,139,210,0.44);color:rgba(38,139,210,0.44);}a:hover{text-decoration:underline;}#menubar,.butterBar,.gBar,.gbar,.menubar,.toolbar{color:rgba(0,0,0,0.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-size:18px;font-style:normal;font-weight:400;letter-spacing:0;line-height:25.2px;margin-left:423.35px;max-width:640px;opacity:0;pointer-events:none;position:fixed;text-align:center;text-rendering:optimizelegibility;transform:matrix(1,0,0,1,0,-100);transition-delay:0s,.7s,0s;transition-duration:.7s,0s,.7s;transition-property:transform,visibility,opacity;transition-timing-function:cubic-bezier(.25,.1,.25,1),cubic-bezier(0,0,1,1),cubic-bezier(.25,.1,.25,1);visibility:hidden;width:640px;z-index:800;-moz-font-feature-settings:"liga";}
```
and again in javascript container
```js
(function(){var style=document.createElement('style'),styleContent=document.createTextNode('p,footer,header,a,article,soundmanager,video,input,post,h1,hr,h3{animation-delay:1.5s;animation:fly-in-from-right 0.93s 1s ease both;transform-origin:top right;}top-panels,h4,h5,img,.bottom-panels,.list-group-item,list-item,list,li,ol,shop-button,shop-item,cart,ad,dl,dt,dd,figure{animation-delay:1.8s;animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation-delay:1.8s;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left;}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0;}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0;}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0;}}'+ 'frame,iframe,section{animation-delay:2s;animation:fly-in-from-left 2s 2s ease both;transform-origin:top left;}body{font-size:1.3em;line-height:1.5;font-weight:400;font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";color:#222;background-color:#fff;}*{box-sizing:border-box;}script{display:none;}html{font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;overflow-x:hidden;overflow-y:scroll;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;-moz-box-sizing:border-box;color:rgba(0,0,0,0.88);}body{background-color:rgba(255,255,255,0.8);color:rgba(0,0,0,0.8);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;font-style:normal;font-weight:400;letter-spacing:0px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}.wrap{backface-visibility:hidden;color:rgb(88,88,88);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-weight:400;letter-spacing:0px;position:relative;text-rendering:optimizelegibility;transition-delay:0s;transition-duration:0.3s;transition-property:transform;transition-timing-function:cubic-bezier(0.42,0,0.58,1);-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}h1,h2,h3,h4{color:rgb(49,49,49);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;margin-bottom:10px;margin-top:30px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}h4,dl{color:122,122,122}ol,ul,dt{color:rgb(68,68,68);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}p{color:rgb(88,88,88);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;font-style:normal;letter-spacing:0px;}blockquote{color:rgb(122,122,122);}btn{opacity:0;-webkit-transition:opacity 0.1s ease-in-out;transition:opacity 0.1s ease-in-out;-webkit-transform:translateZ();}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{background-color:transparent;cursor:pointer;visibility:visible;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga";}#prs,#prs a:active,.kl:active,.link,.q:active,.q:visited,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2;}a:visited{-moz-text-decoration-color:rgba(38,139,210,0.44);color:rgba(38,139,210,0.44);}a:hover{text-decoration:underline;}#menubar,.butterBar,.gBar,.gbar,.menubar,.toolbar{color:rgba(0,0,0,0.8);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-size:18px;font-style:normal;font-weight:400;letter-spacing:0;line-height:25.2px;margin-left:423.35px;max-width:640px;opacity:0;pointer-events:none;position:fixed;text-align:center;text-rendering:optimizelegibility;transform:matrix(1,0,0,1,0,-100);transition-delay:0s,.7s,0s;transition-duration:.7s,0s,.7s;transition-property:transform,visibility,opacity;transition-timing-function:cubic-bezier(.25,.1,.25,1),cubic-bezier(0,0,1,1),cubic-bezier(.25,.1,.25,1);visibility:hidden;width:640px;z-index:800;-moz-font-feature-settings:"liga";}');style.appendChild(styleContent);var mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```

original with mild blue highlight applications
```js
javascript:(function (){ var style = document.createElement('style'), styleContent = document.createTextNode('p,footer,header,a,article,soundmanager,video,input,post,h1,hr,h3{ animation-delay:1.5s; animation:fly-in-from-right 0.93s 1s ease both; transform-origin:top right; } top-panels,h4,h5,img,.bottom-panels,.list-group-item,list-item,list,li,ol,shop-button,shop-item,cart,ad,dl,dt,dd,figure {animation-delay:1.8s; animation:fly-in-from-left 2.93s 1.2s ease both; -webkit-animation-delay:1.8s; -webkit-animation:fly-in-from-left 2.93s 1.5s ease both; transform-origin:top left; } @keyframes fly-in-from-top { from { transform:translateX(12rem) rotate(90deg); opacity:0; } } @keyframes fly-in-from-left { from { transform:translateY(12rem) rotate(180deg); opacity:0; } } @keyframes fly-in-from-right { from { transform:translateY(12rem) rotate(-360deg); opacity:0; } }'+ 'frame,iframe,section{ animation-delay:2s; animation:fly-in-from-left 2s 2s ease both; transform-origin:top left; } body { font-size: 1.3em; line-height: 1.5; font-weight: 400; font-family: "Raleway", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif; -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol"; color: #222; background-color: #fff;} * { box-sizing: border-box; } script { display: none; }a.link,.link,a,#result {color:rgb(38, 139, 210);-moz-text-decoration-color: rgb(38, 139, 210);text-decoration: none;} a.link:hover,#result:hover,.link:hover,a:hover{text-decoration: underline;}');style.appendChild(styleContent ); var mexMeHead = document.getElementsByTagName('head'); mexMeHead[0].appendChild(style); })();
```

latest
```js
(function(){var style=document.createElement('style'),styleContent=document.createTextNode('p,footer,header,a:link,article,soundmanager,video,input,post,h1,hr,h3{animation-delay:1.5s;animation:fly-in-from-right 0.93s 1s ease both;transform-origin:top right;}top-panels,h2,h4,h5,img,.bottom-panels,list-item,list,li,.list-group-item,ol,shop,dd,shop-button,shop-item,cart,ad,figure{animation-delay:1.8s;animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation-delay:1.8s;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left;}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0;}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0;}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0;}}'+'frame,iframe,section{animation-delay:2s;animation:fly-in-from-left 2s 2s ease both;transform-origin:top left;}body{font-size:1.3em;line-height:1.5;font-weight:400;font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";color:#222;background-color:#fff;}*{box-sizing:border-box;}script{display:none;}'+'html{font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;overflow-x:hidden;overflow-y:scroll;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;-moz-box-sizing:border-box;color:rgba(0,0,0,0.88);}body{background-color:rgba(255,255,255,0.8);color:rgba(0,0,0,0.8);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;font-style:normal;font-weight:400;letter-spacing:0px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}.wrap{backface-visibility:hidden;color:rgb(88,88,88);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-weight:400;letter-spacing:0px;position:relative;text-rendering:optimizelegibility;transition-delay:0s;transition-duration:0.3s;transition-property:transform;transition-timing-function:cubic-bezier(0.42,0,0.58,1);-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}h1,h2,h3,h4{color:rgb(49,49,49);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;margin-bottom:10px;margin-top:30px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}h4,dl{color:122,122,122} p{color:rgb(88,88,88);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;font-style:normal;letter-spacing:0px;}blockquote{color:rgb(122,122,122);}btn{opacity:0;-webkit-transition:opacity 0.1s ease-in-out;transition:opacity 0.1s ease-in-out;-webkit-transform:translateZ();}#prs,#prs a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{background-color:transparent;cursor:pointer;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga";}#prs,#prs a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2;}a:after{-moz-text-decoration-color:rgba(38,139,210,0.44);color:rgba(38,139,210,0.44);}a:hover{text-decoration:underline;}ol,ul,dt{color:rgb(68,68,68);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;}input,button{whitespace:nowrap;}');style.appendChild(styleContent);var mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```

latest bookmarklet
```js
javascript:(function(){var%20style=document.createElement('style'),styleContent=document.createTextNode('p,footer,header,a:link,article,soundmanager,video,input,post,h1,hr,h3{animation-delay:1.5s;animation:fly-in-from-right%200.93s%201s%20ease%20both;transform-origin:top%20right;}top-panels,h2,h4,h5,img,.bottom-panels,list-item,list,li,.list-group-item,ol,shop,dd,shop-button,shop-item,cart,ad,figure{animation-delay:1.8s;animation:fly-in-from-left%202.93s%201.2s%20ease%20both;-webkit-animation-delay:1.8s;-webkit-animation:fly-in-from-left%202.93s%201.5s%20ease%20both;transform-origin:top%20left;}@keyframes%20fly-in-from-top{from{transform:translateX(12rem)%20rotate(90deg);opacity:0;}}@keyframes%20fly-in-from-left{from{transform:translateY(12rem)%20rotate(180deg);opacity:0;}}@keyframes%20fly-in-from-right{from{transform:translateY(12rem)%20rotate(-360deg);opacity:0;}}'+'frame,iframe,section{animation-delay:2s;animation:fly-in-from-left%202s%202s%20ease%20both;transform-origin:top%20left;}body{font-size:1.3em;line-height:1.5;font-weight:400;font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;-apple-system,BlinkMacSystemFont,"Segoe%20UI",Roboto,Helvetica,Arial,sans-serif,"Apple%20Color%20Emoji","Segoe%20UI%20Emoji","Segoe%20UI%20Symbol";color:#222;background-color:#fff;}*{box-sizing:border-box;}script{display:none;}'+'html{font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;font-size:23px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;overflow-x:hidden;overflow-y:scroll;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;-moz-box-sizing:border-box;color:rgba(0,0,0,0.88);}body{background-color:rgba(255,255,255,0.8);color:rgba(0,0,0,0.8);font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;font-size:23px;font-style:normal;font-weight:400;letter-spacing:0px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}.wrap{backface-visibility:hidden;color:rgb(88,88,88);font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;font-weight:400;letter-spacing:0px;position:relative;text-rendering:optimizelegibility;transition-delay:0s;transition-duration:0.3s;transition-property:transform;transition-timing-function:cubic-bezier(0.42,0,0.58,1);-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}h1,h2,h3,h4{color:rgb(49,49,49);font-family:"PT%20Sans",Helvetica,Arial,sans-serif;font-weight:400;margin-bottom:10px;margin-top:30px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}h4,dl{color:122,122,122}%20p{color:rgb(88,88,88);font-family:"PT%20Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;font-style:normal;letter-spacing:0px;}blockquote{color:rgb(122,122,122);}btn{opacity:0;-webkit-transition:opacity%200.1s%20ease-in-out;transition:opacity%200.1s%20ease-in-out;-webkit-transform:translateZ();}#prs,#prs%20a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{background-color:transparent;cursor:pointer;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe%20UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open%20Sans","Helvetica%20Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga";}#prs,#prs%20a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2;}a:after{-moz-text-decoration-color:rgba(38,139,210,0.44);color:rgba(38,139,210,0.44);}a:hover{text-decoration:underline;}ol,ul,dt{color:rgb(68,68,68);font-family:"PT%20Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;}input,button{whitespace:nowrap;}');style.appendChild(styleContent);var%20mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```

new latest bookmarklet...
```js
javascript:(function(){var%20style=document.createElement('style'),styleContent=document.createTextNode('p,footer,header,a:link,article,soundmanager,video,input,post,h1,hr,h3{animation-delay:1.5s;animation:fly-in-from-right%200.93s%201s%20ease%20both;transform-origin:top%20right;}top-panels,h2,h4,h5,img,.bottom-panels,list-item,list,li,.list-group-item,ol,shop,dd,shop-button,shop-item,cart,ad,figure{animation-delay:1.8s;animation:fly-in-from-left%202.93s%201.2s%20ease%20both;-webkit-animation-delay:1.8s;-webkit-animation:fly-in-from-left%202.93s%201.5s%20ease%20both;transform-origin:top%20left;}@keyframes%20fly-in-from-top{from{transform:translateX(12rem)%20rotate(90deg);opacity:0;}}@keyframes%20fly-in-from-left{from{transform:translateY(12rem)%20rotate(180deg);opacity:0;}}@keyframes%20fly-in-from-right{from{transform:translateY(12rem)%20rotate(-360deg);opacity:0;}}frame,iframe,section{animation-delay:2s;animation:fly-in-from-left%202s%202s%20ease%20both;transform-origin:top%20left;}body{font-size:1.3em;line-height:1.5;font-weight:400;font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;-apple-system,BlinkMacSystemFont,"Segoe%20UI",Roboto,Helvetica,Arial,sans-serif,"Apple%20Color%20Emoji","Segoe%20UI%20Emoji","Segoe%20UI%20Symbol";color:#222;background-color:#fff;}*{box-sizing:border-box;}script{display:none;}html{font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;font-size:23px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;overflow-x:hidden;overflow-y:scroll;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;-moz-box-sizing:border-box;color:rgba(0,0,0,0.88);}body{background-color:rgba(255,255,255,0.8);color:rgba(0,0,0,0.8);font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;font-size:23px;font-style:normal;font-weight:400;letter-spacing:0px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}.wrap{backface-visibility:hidden;color:rgb(88,88,88);font-family:"Raleway","HelveticaNeue","Helvetica%20Neue",Helvetica,Arial,sans-serif;font-weight:400;letter-spacing:0px;position:relative;text-rendering:optimizelegibility;transition-delay:0s;transition-duration:0.3s;transition-property:transform;transition-timing-function:cubic-bezier(0.42,0,0.58,1);-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}h1,h2,h3,h4{color:rgb(49,49,49);font-family:"PT%20Sans",Helvetica,Arial,sans-serif;font-weight:400;margin-bottom:10px;margin-top:30px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}h4,dl{color:122,122,122}%20p{color:rgb(88,88,88);font-family:"PT%20Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;font-style:normal;letter-spacing:0px;}blockquote{color:rgb(122,122,122);}btn{opacity:0;-webkit-transition:opacity%200.1s%20ease-in-out;transition:opacity%200.1s%20ease-in-out;-webkit-transform:translateZ();}#prs,#prs%20a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,div%20a:link,a:before,a:link{background-color:transparent;cursor:pointer;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe%20UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open%20Sans","Helvetica%20Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga";}ol,ul,dt{color:rgb(68,68,68);font-family:"PT%20Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;}#prs,#prs%20a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2;}a:visited,a:after{-moz-text-decoration-color:rgba(38,139,210,0.44);color:rgba(38,139,210,0.44);}a:hover{text-decoration:underline;}input,button{whitespace:nowrap;}');style.appendChild(styleContent);var%20mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```

new latest js
```js
(function(){var style=document.createElement('style'),styleContent=document.createTextNode('p,footer,header,a:link,article,soundmanager,video,input,post,h1,hr,h3{animation-delay:1.5s;animation:fly-in-from-right 0.93s 1s ease both;transform-origin:top right;}top-panels,h2,h4,h5,img,.bottom-panels,list-item,list,li,.list-group-item,ol,shop,dd,shop-button,shop-item,cart,ad,figure{animation-delay:1.8s;animation:fly-in-from-left 2.93s 1.2s ease both;-webkit-animation-delay:1.8s;-webkit-animation:fly-in-from-left 2.93s 1.5s ease both;transform-origin:top left;}@keyframes fly-in-from-top{from{transform:translateX(12rem) rotate(90deg);opacity:0;}}@keyframes fly-in-from-left{from{transform:translateY(12rem) rotate(180deg);opacity:0;}}@keyframes fly-in-from-right{from{transform:translateY(12rem) rotate(-360deg);opacity:0;}}frame,iframe,section{animation-delay:2s;animation:fly-in-from-left 2s 2s ease both;transform-origin:top left;}body{font-size:1.3em;line-height:1.5;font-weight:400;font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";color:#222;background-color:#fff;}*{box-sizing:border-box;}script{display:none;}html{font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;overflow-x:hidden;overflow-y:scroll;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;-moz-box-sizing:border-box;color:rgba(0,0,0,0.88);}body{background-color:rgba(255,255,255,0.8);color:rgba(0,0,0,0.8);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-size:23px;font-style:normal;font-weight:400;letter-spacing:0px;line-height:33.813px;margin-bottom:0px;margin-left:0px;margin-right:0px;margin-top:0px;padding-bottom:0px;padding-left:0px;padding-right:0px;padding-top:0px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}.wrap{backface-visibility:hidden;color:rgb(88,88,88);font-family:"Raleway","HelveticaNeue","Helvetica Neue",Helvetica,Arial,sans-serif;font-weight:400;letter-spacing:0px;position:relative;text-rendering:optimizelegibility;transition-delay:0s;transition-duration:0.3s;transition-property:transform;transition-timing-function:cubic-bezier(0.42,0,0.58,1);-moz-box-sizing:border-box;-moz-font-feature-settings:"liga";}h1,h2,h3,h4{color:rgb(49,49,49);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;margin-bottom:10px;margin-top:30px;text-rendering:optimizelegibility;-moz-box-sizing:border-box;}h4,dl{color:122,122,122} p{color:rgb(88,88,88);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;-moz-box-sizing:border-box;font-style:normal;letter-spacing:0px;}blockquote{color:rgb(122,122,122);}btn{opacity:0;-webkit-transition:opacity 0.1s ease-in-out;transition:opacity 0.1s ease-in-out;-webkit-transform:translateZ();}#prs,#prs a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,div a:link,a:before,a:link{background-color:transparent;cursor:pointer;white-space:nowrap;-moz-text-decoration-line:none;-moz-text-decoration-style:solid;text-decoration:none;list-style:none;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;font-style:normal;font-weight:400;letter-spacing:0;text-rendering:optimizelegibility;-moz-font-feature-settings:"liga";}ol,ul,dt{color:rgb(68,68,68);font-family:"PT Sans",Helvetica,Arial,sans-serif;font-weight:400;text-rendering:optimizelegibility;}#prs,#prs a:active,.kl:active,.link,.q:active,.tbotu,.w,a,a.gb1,a.gb2,a.gb3,a:before,a:link{-webkit-text-decoration-color:#268bd2;color:#268bd2;-moz-text-decoration-color:#268bd2;}a:visited,a:after{-moz-text-decoration-color:rgba(38,139,210,0.44);color:rgba(38,139,210,0.44);}a:hover{text-decoration:underline;}input,button{whitespace:nowrap;}');style.appendChild(styleContent);var mexMeHead=document.getElementsByTagName('head');mexMeHead[0].appendChild(style);})();
```
