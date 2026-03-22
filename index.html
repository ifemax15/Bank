<!DOCTYPE html>
<html>
<head>
<title>GreenVault</title>

<style>
body {margin:0; font-family:Arial; background:#0f172a; color:white;}
.header {background:#22c55e; padding:15px; text-align:center; font-size:20px;}
.container {padding:20px;}

.btn {
  padding:12px; border:none; border-radius:10px;
  background:#22c55e; color:white; cursor:pointer;
  width:100%; margin-top:10px;
}

input {
  width:100%; padding:12px; margin-top:10px;
  border:none; border-radius:10px;
}

.box {
  background:#1e293b; padding:15px;
  border-radius:15px; margin-top:15px;
}

.card {
  background:linear-gradient(135deg,#22c55e,#16a34a);
  padding:20px; border-radius:20px;
  width:300px; margin:auto; text-align:center;
  cursor:pointer;
}

.credit-card {
  background:linear-gradient(135deg,#111,#333);
  padding:20px; border-radius:15px;
  margin-top:15px;
  cursor:pointer;
}

.receipt, .popup {
  position:fixed; top:50%; left:50%;
  transform:translate(-50%,-50%);
  background:white; color:black; padding:20px;
  border-radius:12px; display:none;
  width:300px;
}
</style>
</head>

<body>

<div class="header">💳 GreenVault</div>

<!-- HOME -->
<div class="container" id="homePage">
  <h2>Welcome to GreenVault</h2>
  <p>Secure banking demo experience.</p>

  <button class="btn" onclick="goLogin()">Login</button>
</div>

<!-- LOGIN -->
<div class="container" id="loginBox" style="display:none;">
  <h2>Login</h2>
  <input id="email" placeholder="Email">
  <input type="password" id="password" placeholder="Password">
  <button class="btn" onclick="login()">Continue</button>
</div>

<!-- DASHBOARD -->
<div class="container" id="dashboard" style="display:none;">

  <!-- BALANCE CARD -->
  <div class="card" onclick="toggleBalance()">
    <h3>💳 Premium Account</h3>
    <p>Chase Rice</p>
    <h1 id="balanceText">$500000</h1>
    <small>Tap to hide/show</small>
  </div>

  <!-- CREDIT CARD -->
  <div class="credit-card" onclick="openCard()">
    <h3>💳 Credit Card</h3>
    <p>Chase Rice</p>
    <p>**** **** **** 3456</p>
    <small>Tap to view</small>
  </div>

  <!-- SEND (BLOCKED) -->
  <div class="box">
    <h3>Send Money</h3>
    <input placeholder="Receiver Name">
    <input placeholder="Account Number">
    <input type="number" placeholder="Amount">
    <button class="btn" onclick="blocked()">Send</button>
  </div>

  <!-- BILL -->
  <div class="box">
    <h3>Pay Bill</h3>
    <input id="billName" placeholder="Bill Name">
    <input id="billAmount" type="number" placeholder="Amount">
    <button class="btn" onclick="payBill()">Pay</button>
  </div>

  <!-- LOAN -->
  <div class="box">
    <h3>💰 Loan</h3>
    <input id="loanAmount" type="number" placeholder="Enter Loan Amount">
    <button class="btn" onclick="applyLoan()">Apply Loan</button>
  </div>

</div>

<!-- POPUPS -->
<div class="receipt" id="receiptBox"></div>
<div class="popup" id="cardPopup"></div>

<script>

let balance = 500000;
let hidden = false;

const correctEmail = "chaserice3563@gmali.com";
const correctPassword = "Chaserice4444";

function goLogin(){
  homePage.style.display="none";
  loginBox.style.display="block";
}

function login(){
  if(email.value === correctEmail && password.value === correctPassword){
    let otp = prompt("Enter OTP (1234)");
    if(otp === "1234"){
      loginBox.style.display="none";
      dashboard.style.display="block";
    } else {
      alert("Wrong OTP");
    }
  } else {
    alert("Wrong login");
  }
}

// 👁️ TOGGLE BALANCE
function toggleBalance(){
  let el = document.getElementById("balanceText");
  if(hidden){
    el.innerText = "$" + balance;
  } else {
    el.innerText = "******";
  }
  hidden = !hidden;
}

// 💳 OPEN CARD VIEW
function openCard(){
  cardPopup.innerHTML = `
    <h3>💳 GreenVault Card</h3>
    Name: Chase Rice<br><br>
    Number: 1234 5678 9012 3456<br>
    Expiry: 12/29<br>
    CVV: 123<br><br>
    <button onclick="cardPopup.style.display='none'">Close</button>
  `;
  cardPopup.style.display="block";
}

// 🚫 BLOCKED TRANSFER
function blocked(){
  alert("🚫 Transfers are blocked.\nPlease contact GreenVault support.");
}

// 💡 BILL PAYMENT
function payBill(){
  let amt = parseInt(billAmount.value);
  if(!billName.value || !amt) return alert("Fill all");

  if(amt > balance) return alert("Insufficient");

  balance -= amt;
  updateBalance();

  showReceipt(`
    <h3>Bill Paid</h3>
    Bill: ${billName.value}<br>
    Amount: $${amt}<br>
    Date: ${new Date().toLocaleString()}<br>
    Status: Successful
  `);
}

// 💰 LOAN
function applyLoan(){
  let amt = parseInt(loanAmount.value);
  if(!amt) return alert("Enter amount");

  balance += amt;
  updateBalance();

  showReceipt(`
    <h3>Loan Approved</h3>
    Amount: $${amt}<br>
    New Balance: $${balance}<br>
    Status: Approved
  `);
}

function updateBalance(){
  document.getElementById("balanceText").innerText = "$" + balance;
}

// RECEIPT
function showReceipt(content){
  receiptBox.innerHTML = content +
  "<br><button onclick='receiptBox.style.display=\"none\"'>Close</button>";
  receiptBox.style.display="block";
}

</script>

</body>
</html>
