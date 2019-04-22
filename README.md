# jquery-duplicatewindow
Not allow user to open website in multiple windows 

jQuery plugin to check if current window is duplicate window,<br/>
<br/>
This plugin works across all browsers IE, Firefox, Microsoft Edge & Google chrome<br/>
<br/>
It is checking GUID of the window against value in cookie<br/>

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


[click here to donate if you find this project helpful](https://paypal.me/nitinsa1?locale.x=en_GB)
