# simonova-cib-intern
Приложение развернуто на Heroku по адресу https://simonova-cib-intern.herokuapp.com

Схема базы данных находится в файле database_socks.png

 Таблица socks заполнена:<br>
 <table>
  <tr>
    <td>id</td><td>color</td><td>cotton_part</td><td>quantity</td>
  </tr>
  <tr>
  <td>1</td><td>red</td><td>50</td><td>5</td>
  </tr>
  <tr>
    <td>3</td><td>green</td><td>10</td><td>10</td>
  </tr>
  <tr>
    <td>2</td><td>green</td><td>100</td><td>23</td>
  </tr>
    <tr>
    <td>4</td><td>red</td><td>23</td><td>6</td>
  </tr>
  </table>
  
 Пример GET запроса
 
 https://simonova-cib-intern.herokuapp.com/api/socks?color=red&operation=moreThan&cottonPart=49
