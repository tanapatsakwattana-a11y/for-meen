# for-meen
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ถึง...มีน ❤️</title>

<style>
body{
    margin:0;
    font-family:sans-serif;
    background:#ffd9e8;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}
.box{
    width:90%;
    max-width:420px;
    background:#fff;
    border-radius:25px;
    padding:30px;
    text-align:center;
    box-shadow:0 0 20px rgba(0,0,0,.15);
}
h1{
    color:#ff4f8b;
}
p{
    font-size:20px;
    line-height:1.8;
}
button{
    border:none;
    padding:15px 30px;
    margin:10px;
    border-radius:50px;
    font-size:18px;
    cursor:pointer;
}
#yes{
    background:#ff4f8b;
    color:white;
}
#no{
    background:#ddd;
}
</style>
</head>

<body>

<div class="box">
<h1>ถึง...มีน ❤️</h1>

<p>
ตั้งแต่วันที่เราได้รู้จักกัน
ทุกช่วงเวลาที่มีเธออยู่
ทำให้ทุกวันของเรามีความหมาย
เราอาจไม่ได้เป็นคนที่ดีที่สุด
แต่จะพยายามดูแลเธอให้ดีที่สุดเสมอ

<br><br>

มีน...เป็นแฟนกับเราได้ไหม ❤️
</p>

<button id="yes" onclick="yes()">ตกลง ❤️</button>
<button id="no" onmouseover="run()">ไม่ 😝</button>

</div>

<script>
function yes(){
alert("เย้! จากนี้ขอดูแลมีนนะ ❤️");
}

function run(){
let b=document.getElementById("no");
b.style.position="absolute";
b.style.left=Math.random()*80+"%";
b.style.top=Math.random()*80+"%";
}
</script>

</body>
</html>
