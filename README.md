<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login to Deriv</title>
</head>
<body style="text-align: center; font-family: sans-serif; margin-top: 100px;">
  <h1>Login or Sign Up to Deriv</h1>
  <a id="login-btn" href="#">Click to Continue</a>

  <script>
    const app_id = '76613'; // Replace with your Deriv App ID
    const redirect_uri = window.location.href;
    const login_url = `https://oauth.deriv.com/oauth2/authorize?app_id=${app_id}&l=EN&redirect_uri=${redirect_uri}`;

    document.getElementById("login-btn").href = login_url;
  </script>
</body>
</html>
