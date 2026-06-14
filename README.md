# My-website
Company website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Website</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

header{
    background:linear-gradient(135deg,#4f46e5,#7c3aed);
    color:white;
    text-align:center;
    padding:100px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:10px;
}

header p{
    font-size:1.2rem;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 24px;
    background:white;
    color:#4f46e5;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

section{
    max-width:1000px;
    margin:auto;
    padding:60px 20px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 15px rgba(0,0,0,0.1);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head
