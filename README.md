# Lab-work
Для Беляева Игоря Сергеевича
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
  <title>Калькулятор</title>
  <link rel="stylesheet" href="style.css"> 
  <body backgroundcolor="#FA15C4"></body>
</head>
<body align="center">
  <div align="center">
    <div id="result" class="result">
      0
    </div>
    <div>
      <div>  
        <button id="btn_op_clear" class="my-btn secondary">C</button>
        <button id="btn_op_sign" class="my-btn secondary">+/-</button>
        <button id="btn_op_percent" class="my-btn secondary">%</button>
        <button id="btn_op_div" class="my-btn secondary">/</button>
      </div>
      <div>
        <button id="btn_digit_7" class="my-btn">7</button>
        <button id="btn_digit_8" class="my-btn">8</button>
        <button id="btn_digit_9" class="my-btn">9</button>
        <button id="btn_op_mult" class="my-btn primary">x</button>
      </div>
      <div>
        <button id="btn_digit_4" class="my-btn">4</button>
        <button id="btn_digit_5" class="my-btn">5</button>
        <button id="btn_digit_6" class="my-btn">6</button>
        <button id="btn_op_minus" class="my-btn primary">-</button>
      </div>
      <div>
        <button id="btn_digit_1" class="my-btn">1</button>
        <button id="btn_digit_2" class="my-btn">2</button>
        <button id="btn_digit_3" class="my-btn">3</button>
        <button id="btn_op_plus" class="my-btn primary">+</button>
      </div>
      <div>
        <button id="btn_digit_0" class="my-btn">0</button>
        <button id="btn_digit_dot" class="my-btn">.</button>
        <button id="btn_op_equal" class="my-btn primary execute">=</button>
      </div>
    </div>
  </div>
</body>
<H1 align="right">  ЛР выполнена Костюковом Кириллом Евгеньивичем</H1>
<button id="theme-toggle">Сменить тему (не работает)</button>
<label>
    <input type="checkbox" onchange="changeTheme(this.checked)">
    Включить темную тему (Работает)
  </label>
  <script>
    function changeTheme(isChecked) {
      if (isChecked) {
        document.body.setAttribute('dark', '');
      } else {
        document.body.removeAttribute('dark');
      }
    }
  </script>
  <img src="1.jpg" align="right" />
  <form action="https://github.com/dashboard" target="_blank">
    <button>Переход с ссылкой на GitHub</button>
    <div class="demo">
        <input type="checkbox" id="hd-1" class="hide"/>
        <label for="hd-1" >Cворачивающиеся и разворачивающиеся подробности</label>
        <div>
            Костюков Кирилл Евгеньивич => без группы (только я и интернет)
        </div>
        <br/>
    <br/>
</html>
