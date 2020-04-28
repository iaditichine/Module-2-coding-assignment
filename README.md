<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Assignment Solution for Module 2</title>
    <link rel="stylesheet" href="css/style.css">
<style>
*{
box-sizing:border-box;
font-family:Helvetica
}
body{
background-color:#d6d6d6;
}
h1{
text-align:center;
color:black;
}
section {
    border: 1px solid black;
    background-color: #a9acbb;
    margin: 15px
    background-color: #b5c4d2;
    margin: 10px;
}
section>h2 {
    float: right;
    width: 235px;
    padding: 8px;
    text-align: center;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    font-family: Times;
    margin: 0;
    width: 230px;
    text-align: center;
    font-style: Times;
    font-size: 24px;
    font-weight: bold;
    height: 45px;
    padding-top: 10px;
}
section.chicken>h2 {
    background-color:pink;
}
section.beef>h2 {
    background-color:red;
}
section.sushi>h2 {
    color: #e2e2e2;
    background-color:orange
}

section>p {
    padding: 40px 15px 15px 15px;
}

.row {
    width: 100%;
}
</style>
</head>

<body>
<h1>Our Menu</h1>
<div class="row">
<div class="col-lg-4 col-md-6 col-sm-12">
<section class="chicken">
<h2>Chicken</h2>
<p>lorem ipsum dolor sit omlet,consectetur<br>
adipisicing elit,sed do eiusmod tempor incididunt ut labore<br>
et dolore magna aliqua.Ut<br>
enim ad mini veniam,quis nostrud exercitation<br>
ullamco laboris nisi ut aliquip ex ea commodo<br>
consequat

</p>
</section>
</div>
<div class="col-lg-4 col-md-6 col-sm-12">
<section class="beef">
<h2>Beef</h2>
<p>lorem ipsum dolor sit omlet,consectetur<br>
adipisicing elit,sed do eiusmod tempor incididunt ut labore<br>
et dolore magna aliqua.Ut<br>
enim ad mini veniam,quis nostrud exercitation<br>
ullamco laboris nisi ut aliquip ex ea commodo<br>
consequat

                </p>
            </section>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
            <section class="sushi">
                <h2>Sushi</h2>
                <p>lorem ipsum dolor sit omlet,consectetur<br>
                   adipisicing elit,sed do eiusmod tempor incididunt ut labore<br>
                   et dolore magna aliqua.Ut<br>
                   enim ad mini veniam,quis nostrud exercitation<br>
                   ullamco laboris nisi ut aliquip ex ea commodo<br>
                   consequat<br>

                </p>
            </section>
        </div>
    </div>
</body>

</html>
