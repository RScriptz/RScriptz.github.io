<!DOCTYPE html>
<html>
<head>
    <title>Redirect to Roblox</title>
</head>
<body>
    <script type="text/javascript">
        var placeId = 'PLACE_ID';
        var gameInstanceId = 'JOB_ID';
        var robloxUrl = `roblox://experiences/start?placeId=${placeId}&gameInstanceId=${gameInstanceId}`;
        window.location.href = robloxUrl;
    </script>
    <p>If you are not redirected automatically, <a id="roblox-link" href="#">click here</a>.</p>
    <script type="text/javascript">
        document.getElementById('roblox-link').href = robloxUrl;
    </script>
</body>
</html>
