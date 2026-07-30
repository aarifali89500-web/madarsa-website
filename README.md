*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Arial,sans-serif;
background:#f5f7f5;
color:#222;
line-height:1.6;
}

header{
background:#0B6B3A;
color:#fff;
padding:20px;
text-align:center;
}

nav{
background:#064D2A;
display:flex;
justify-content:center;
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
padding:15px 20px;
font-weight:bold;
}

nav a:hover{
background:#FFD700;
color:black;
}

.hero{
background:linear-gradient(rgba(0,80,40,.7),rgba(0,80,40,.7));
padding:80px 20px;
text-align:center;
color:white;
}

.section{
max-width:1100px;
margin:25px auto;
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 3px 10px rgba(0,0,0,.1);
}

.btn{
display:inline-block;
padding:12px 24px;
background:#FFD700;
color:black;
text-decoration:none;
border-radius:8px;
font-weight:bold;
margin-top:15px;
}

.btn:hover{
background:#FFC107;
}

footer{
background:#064D2A;
color:white;
text-align:center;
padding:25px;
margin-top:30px;
}

img{
max-width:100%;
border-radius:10px;
}

table{
width:100%;
border-collapse:collapse;
}

table th,
table td{
border:1px solid #ddd;
padding:10px;
}

table th{
background:#0B6B3A;
color:white;
}

@media(max-width:768px){

nav{
flex-direction:column;
}

.hero{
padding:50px 15px;
}

.section{
margin:15px;
}

}
