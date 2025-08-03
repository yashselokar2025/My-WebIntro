# My-WebIntro
Here, I uplaod my website for my portfolio.

Here my link:

HTML-Css code through VS Code:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Project Presentation - Team Level_Up</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <h1>📊 Project Presentation</h1>
    
    <p class="subtitle"><strong>Team Level_Up</strong> | CAMPUS CONNECT</p>

    <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTPOufKmbhN_J-V3v2_Li3pFc0EKLPk3-EEX--Fs64OnLPIrfE0nsRvHVag_TiQ5GRb9EtbW2Nwt63h/pubembed?start=true&loop=true&delayms=2000" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true">
      
    </iframe>

    <p class="note">
      If the presentation doesn't load, make sure your browser supports embedded content. 
      <br>You can also 
      <a href="Red White Modern Group Project Presentation.pdf" download style="color: #b30000; text-decoration: underline;">
        download the presentation here
      </a>.
    </p>
  </div>

</body>
</html>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
  }
  .container {
    max-width: 960px;
    margin: auto;
    background: white;
    padding: 20px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  }
  h1 {
    color: #333;
    text-align: center;
  }
  .subtitle {
    text-align: center;
    color: #666;
    margin-bottom: 20px;
  }
  iframe {
    display: block;
    margin: auto;
    border-radius: 8px;
  }
  .note {
    text-align: center;
    color: #b30000;
    margin-top: 20px;
  }
  body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(-45deg, #e3f2fd, #bbdefb, #90caf9, #64b5f6);
  background-size: 400% 400%;
  animation: gradientShift 15s ease infinite;
  color: #333;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  padding: 60px 20px;
}

@keyframes gradientShift {
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
  max-width: 960px;
  width: 100%;
  background: rgba(255, 255, 255, 0.8);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  box-shadow: 0 12px 40px rgba(0, 0, 0, 0.2);
  border-radius: 16px;
  padding: 40px 30px;
  text-align: center;
  transition: all 0.3s ease;
}

h1 {
  font-size: 2.2em;
  color: #b30000;
  margin-bottom: 12px;
}

.subtitle {
  font-size: 1.1em;
  color: #444;
  margin-bottom: 30px;
}

iframe {
  border: 1px solid #ccc;
  border-radius: 10px;
}

.note {
  font-size: 0.9em;
  margin-top: 20px;
  color: #666;
}
    .note a {
        color: #b30000;
        text-decoration: none;
        font-weight: bold;
    }
    .note a:hover {
        text-decoration: underline;
    } 
