<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SUMO - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1>Welcome to SUMO</h1>
  
  <input type="text" id="postInput" placeholder="What's on your mind?">
  <button onclick="addPost()">Post</button>

  <div id="postArea"></div>

  <br><br>
  <a href="profile.html">Go to Profile</a> |
  <a href="login.html">Login</a> |
  <a href="register.html">Register</a>

  <script src="app.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  padding: 20px;
}

h1 {
  color: #333;
}

input, button {
  padding: 10px;
  margin: 5px;
}

#postArea div {
  background-color: white;
  padding: 10px;
  margin-top: 10px;
  border: 1px solid #ccc;
}
