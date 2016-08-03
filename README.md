<!--# JQuery-UI-issue-->
<!--can't get facebook <div> to become 'draggable'. Can't see why.-->

<!DOCTYPE html>

<html>
	<head>
		<meta charset="utf-8">
		<title>jQuery UI introduction</title>
        <style>
            .bluebox {
                background-color: #3A5795;
                color: white;
                height: 100px;
                width: auto;
                
            }
            .yellowbox {
                background-color: rgb(222, 224, 85);
                 height: 100px;
                width: auto;
            }
            .greenbox {
                background-color: #35b327;
                height: 100px;
                width: auto;
            }
            .great {
                background-color: #dd47f4;
            }
            
        </style>
        <link rel="stylesheet" href="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/themes/smoothness/jquery-ui.css">
<script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/jquery-ui.min.js"></script>
	</head>

<body>
        
<div class="bluebox ui-corner-all" id="facebook">
        <p>Facebook is <span id="great">great</span></p>
    </div>
        
<div class="yellowbox ui-corner-all sans-serif" id="apple">
        <p>Apple</p>
   </div>	
         
<div class="greenbox ui-corner-all" id="microsoft">
        <p>Microsoft</p>
    <p><a href="http://www.microsoft.com" id="mircosoftLink" title="microsoft">Microsoft Link.</a></p>
    
</div>

<div>
    <p class="ui-state-error" style="height:100px;margin-top:20px">
    Error Message.</p>
</div>
<script>
$(function(){
$("#facebook").draggable();
});
 
</script>    
</body>


</html>
