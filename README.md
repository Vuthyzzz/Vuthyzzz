
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DevOps Engineer</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#0f172a,#1e293b,#334155);
    overflow:hidden;
}

.hero{
    text-align:center;
    color:white;
}

.hero h1{
    font-size:70px;
    font-weight:800;
    text-transform:uppercase;
    letter-spacing:4px;
    background:linear-gradient(
        90deg,
        #00f5ff,
        #00ff88,
        #00f5ff
    );
    background-size:300%;
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    animation:gradientMove 4s infinite linear,
               float 3s ease-in-out infinite;
}

.hero p{
    margin-top:20px;
    font-size:22px;
    color:#cbd5e1;
    animation:fadeIn 2s ease-in-out;
}

.glow{
    position:absolute;
    width:400px;
    height:400px;
    background:#00f5ff;
    border-radius:50%;
    filter:blur(150px);
    opacity:.2;
    animation:pulse 5s infinite;
}

@keyframes gradientMove{
    0%{
        background-position:0%;
    }
    100%{
        background-position:300%;
    }
}

@keyframes float{
    0%,100%{
        transform:translateY(0);
    }
    50%{
        transform:translateY(-15px);
    }
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@keyframes pulse{
    0%,100%{
        transform:scale(1);
    }
    50%{
        transform:scale(1.2);
    }
}
</style>

</head>
<body>

<div class="glow"></div>

<div class="hero">
    <h1>DevOps Engineer</h1>
    <p>
        Automating Infrastructure • CI/CD • Cloud Computing • Monitoring • Security
    </p>
</div>

</body>
</html>

