<!DOCTYPE html>
<html lang="en">
<head>
    <script src="http://code.jquery.com/jquery-2.1.4.min.js"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <script> 
    $(document).ready(function(){
        //a.click(function(){
            $("#btn1").click(function(){
            $('#test-ul').append('liyi01')
        });
    });
    </script>
</head>
<body>
    <ul id="test-ul">
    <li class="js">JavaScript</li>
    <li name="book">Java &amp; JavaScript</li>
    </ul>
    <input id="test-input" type="email" name="email" value="testliyi">
    <select id="test-select" name="city">
        <option value="BJ" selected>Beijing</option>
        <option value="SH">Shanghai</option>
        <option value="SZ">Shenzhen</option>
    </select><br />
    <textarea id="test-textarea">Hello</textarea>
    click<input id="test-radio" type="radio" name="test" checked=F value="1"><br />
    <p1>liyi is a good student!</p1> <br />
    <button id= "btn2" type="button" style="width:50px;height:20px" name="liyi" value="添加元素"><br />
    <button id="btn1">追加文本</button>
    <form id="test-form" action="#0" onsubmit="return false;">
            <p>Name: <input name="name"></p>
            <p><label>Email: <input name="email"></label></p>
            <p><label>Password: <input name="password" type="password"></label></p>
            <p>Gender: <label><input name="gender" type="radio" value="m" checked> Male</label> <label><input name="gender" type="radio" value="f"> Female</label></p>
            <p><label>City: <select name="city">
                <option value="BJ" selected>Beijing</option>
                <option value="SH">Shanghai</option>
                <option value="CD">Chengdu</option>
                <option value="XM">Xiamen</option>
            </select></label></p>
            <p><button type="submit">Submit</button></p>
        </form>
    <script>var len1=$('p1').length</script>
</body>
</html>
