<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Student Registration Form</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <h2>Student Registration </h2>
    <form action="#" method="POST">
      <label for="Full Name">Full Name:</label>
      <input type="name" id="name" name="name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />

      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" pattern="[0-9]{10}" placeholder="1234567890" required />

      <label for="Age">Age:</label>
      <input type="Age" id="Age" name="Age" required />

      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required>
        <option value="" disabled selected>Select your gender</option>
        <option value="female">Female</option>
        <option value="male">Male</option>
        <option value="other">Other</option>
      </select>

      

      <button type="Register">Register</button>
    </form>
  </div>
</body>
</html>


body {
  font-family: Arial, sans-serif;
  background: #f2f2f2;
  padding: 20px;
}

.container {
  background: white;
  padding: 30px;
  max-width: 500px;
  margin: auto;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h2 {
  text-align: center;
  margin-bottom: 20px;
}

label {
  display: block;
  margin-top: 15px;
}

input, select {
  width: 100%;
  padding: 8px;
  margin-top: 6px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

button {
  margin-top: 20px;
  width: 100%;
  padding: 10px;
  background: #4CAF50;
  border: none;
  color: white;
  font-size: 16px;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background: #45a049;
}

