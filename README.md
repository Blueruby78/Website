#Website
<!DOCTYPE html>
<head>
    <title>
        CSS animation
    </title>
    <style> 
        #square{
position: relative;
	animation-name: testAnimation;
	animation-duration: 20s;
    height: 300px;
   width: 300px; 
   background-color:red;
   animation-timing-function: linear;}

   @keyframes testAnimation{
0%{background-color:red; top:0px; left:0px; }
25%{background-color:blue; top:0px ; left:1200px;border-radius:50%;
}
50%{background-color:pink; top: 300px; left: 1200px; height:100px; width:100px;}
75%{background-color:green; top : 300px;left:0px; border-radius:10%}
90%{height:500px;width:500px;}
100%{background-color:red; top:0px;left:0px;}}
</style>


    </head>
    <body>
        <div id="square"></div>
    </body>

    </html>












