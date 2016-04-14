# ClassArtifact
JS/HTML
<br>
<br>//Get nodes and elements 
<br>document.getElementsByTagName(); document.getElementById(); 
<br>//Mouse click method and listen to the keyboard, pay attention to compatibility 
<br>click(),onclick(),focus()...document.onkeydown...
<br>//Compatibility Firefox can solve on keyboard monitor
<br>e = event ? event : (window.event ? window.event : null);
<br>//The text box can be selected, click on the assignment, etc., but not on the cursor inside the box, you also need to study.
<br>document.getElementById(textarea).focus();


