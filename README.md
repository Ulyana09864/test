# test
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI test</title>
    <link rel="stylesheet" href="main.css">
</head>

<body>
    <div class="wrapper" id="wrapper">
        <div id="questions">
            <h2 id="title"></h2>
            <p id="question"></p>
            <p><input type="radio" name="year" id="y1"><span id="a1"></span></p>
            <p><input type="radio" name="year" id="y2"><span id="a2"></span></p>
            <p><input type="radio" name="year" id="y3"><span id="a3"></span></p>
            <p><input type="radio" name="year" id="y4"><span id="a4"></span></p>

            <button id="get_answer">Дать ответ</button>
            <div class="right_div hidden" id="right_div">
                <p class="right" id="right">Правильный ответ</p>
                <button id="next_question">Следующий вопрос</button>
            </div>
            <div class="wrong_div hidden" id="wrong_div">
                <p class="wrong" id="wrong">Неправильный ответ</p>
                <button id="view_answer">Посмотреть ответ</button>
            </div>

            <p id="answer" class="hidden"></p>
        </div>
        <div id="total_div">
            <p>Номер вопроса: <span id="n"></span></p>
            <p>Количество правильных ответов: <span id="n_right"></span> (с первого раза).</p>
        </div>
    </div>


    <input type="hidden" value="0" id="n_question">
    <script src="js.js"></script>
</body>

</html>
