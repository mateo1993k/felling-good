<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Positive Communication Platform</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/R8aC1O4AOmiBCeGUliIx0ZowzAuFJ0Vcftg6" crossorigin="anonymous">
</head>
<body>
    <div class="container">
        <h1>Welcome to the Positive Communication Platform</h1>
        <form action="#" method="post" id="loginForm">
            <label for="gender">Select your gender:</label>
            <div class="gender-selection">
                <div class="gender-option" onclick="selectGender('male')">
                    <i class="fas fa-male"></i>
                    <p>Male</p>
                </div>
                <div class="gender-option" onclick="selectGender('female')">
                    <i class="fas fa-female"></i>
                    <p>Female</p>
                </div>
            </div>
            <button type="button" onclick="showSections()">
                Login <i class="fas fa-sign-in-alt"></i>
            </button>
        </form>
    </div>

    <div id="textSection" class="hidden">
        <div class="communication-box">
            <i class="fas fa-comment"></i>
            <h2>Text Communication Section</h2>
            <!-- Add your HTML code for text communication here -->
        </div>
    </div>

    <div id="voiceSection" class="hidden">
        <div class="communication-box">
            <i class="fas fa-microphone"></i>
            <h2>Voice Communication Section</h2>
            <!-- Add your HTML code for voice communication here -->
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #ff8c00, #ff0080, #8000ff, #0080ff, #00ff80);
    background-size: 500% 500%;
    animation: gradient 15s ease infinite;
}

@keyframes gradient {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}

.container {
    max-width: 800px;
    margin: 50px auto;
    text-align: center;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    color: #333;
}

form {
    margin-top: 20px;
}

.gender-selection {
    display: flex;
    justify-content: center;
}

.gender-option {
    cursor: pointer;
    margin: 0 15px;
    text-align: center;
    color: #333;
}

.gender-option p {
    margin: 5px 0;
}

select, button {
    padding: 10px;
    margin: 5px;
    font-size: 16px;
}

button {
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

.hidden {
    display: none;
}

.communication-box {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin-top: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    position: relative;
}

.communication-box i {
    font-size: 40px;
    color: #333;
    position: absolute;
    top: 10px;
    left: 10px;
}
# felling-good
how do you feel?
