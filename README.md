<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <title>양파월드</title>
    <link rel="stylesheet" href="main.css">
</head>

<body>
    <div class="alert-box" id="alert">
        <p>Alert 박스</p>
        <button onclick="document.getElementBsyId('alert').style.display='none';">양파닫기</button>
    </div>
    <button onclick="document.getElementById('alert').style.display = 'block';">양파열기</button>
    


    <h2 id="hello"> 양파월드에 오신 걸 환영합니다</h2>

    <script>
    document.getElementById('hello').style.fontSize = '30px';
    </script>            


    </div>
</body>

</html>
