# split-and-settlee
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Split & Settle</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f4f7fc;
}

header{
    background:#4CAF50;
    color:white;
    text-align:center;
    padding:20px;
}

.container{
    width:80%;
    margin:auto;
    padding:20px;
}

.card{
    background:white;
    padding:20px;
    margin:20px 0;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

input{
    width:100%;
    padding:10px;
    margin:10px 0;
}

button{
    background:#4CAF50;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:5px;
    cursor:pointer;
}

button:hover{
    background:#388E3C;
}

footer{
    text-align:center;
    background:#222;
    color:white;
    padding:10px;
    margin-top:30px;
}
</style>

</head>

<body>

<header>
<h1>Split & Settle</h1>
<p>Informal Group Expense Manager</p>
</header>

<div class="container">

<div class="card">
<h2>Add Participant</h2>

<input type="text" placeholder="Enter Name">
<button>Add Participant</button>

</div>

<div class="card">
<h2>Add Expense</h2>

<input type="text" placeholder="Who Paid?">

<input type="number" placeholder="Amount">

<input type="text" placeholder="Expense Description">

<button>Add Expense</button>

</div>

<div class="card">

<h2>Expense Summary</h2>

<p>Total Expense : ₹0</p>

<p>Each Person Share : ₹0</p>

</div>

<div class="card">

<h2>Settlement Result</h2>

<p>No expenses added yet.</p>

<button>Split & Settle</button>

</div>

</div>

<footer>

© 2026 Split & Settle | Built for Hackathon

</footer>

</body>
</html>
