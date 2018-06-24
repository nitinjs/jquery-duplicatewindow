# jquery-duplicatewindow
Not allow user to open website in multiple windows 

jQuery plugin to check if current window is duplicate window,<br/>
I createdd this plugin based on timkellypa's answer on stackoverflow<br/>
"Stop people having my website loaded on multiple tabs"<br/>
<a href="https://stackoverflow.com/a/45717724/223752">https://stackoverflow.com/a/45717724/223752</a><br/>
<br/>
This plugin works across all browsers IE, Firefox, Microsoft Edge & Google chrome<br/>
<br/>
It is basically checking GUID of the window against value in cookie<br/>

Sample usage:
```
    <script type="text/javascript">
        $(document).ready(function () {
            if (window.IsDuplicate()) {
                alert("this is duplicate window\n\n closing...");
                window.close();
            }
        });
    </script>
```
