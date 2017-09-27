---
title: Strawberry
date: 2017-08-15 09:12:00 Z
categories:
- jekyll
header: <font color="#ff99ff"> Собираю, продаю... </font>
description:
- Этим летом я помогал маме с ее сельскохозяйственным бизнесом. <br />
- Моя задача состояла в собирании и продавании клубники :) <br />
- Хочешь узнать подробнее? ЗАХОДИ! ОЧЕНЬ ИНТЕРЕСНО!!! <br />
- "<br />"
layout: post
---

<center> <h1> mmmm... КЛУБНИЧКА!!!! </h1> </center>
<br />
<center><img src="images/strawberry.jpg" style="width:50%;height:50%;"></center>
<br />
Этим летом я помогал маме. Я ХОРОШИЙ СЫН.<br />
Рано утром я вставал, чтобы собирать клубнику. Собирая по пронципу "три в ведерко, одну в рот" за первую неделю
я так ее наелся, что больше не мог смотреть. После сбора я содился в машину и вез все на рынок. Продавая клубнику, я познакомился с местными
арбузодилерами. Хорошие ребята. Каждое утро наслаждались с ними наилучшили синглами типа: "Я дурууг, ты дурууг, МЫ КРИМИНАЛЬНЫЙ КРУУУГ...".

<p ><audio controls> <source src="uploads/durug.mp3" controls></audio> </p>

<br /><br />
<img src="images/wtmln.jpg" style="width:33%;height:33%; float: left;">
<img src="images/wtmln.gif" style="width:33%;height:33%; float: center;">
<img src="images/wtmln.jpg" style="width:33%;height:33%; float: right;">
<br /><br /><br /><br />



<head>
<script type="text/javascript"><!--
    /* Значение этой цифры определяет скорость печати.
     Чем меньше цифра, тем выше скорость и наоборот. */
    var speed = 90;

    /* Эта цифра указывает задержку перехода к
     другой строке в миллисекундах. Чем больше
     цифра, тем дольше будет отображаться строка
     до перехода к другой строке */
    var pause = 1000;

    var timerID = null;
    var wireRunning = false;
    var cc = [];

    /* Ниже впишите то, что будет печататься в
     окошечке. Как это делать, вы видите. */

    cc[0] = "Хорошая формочка для экономии места!";
    cc[1] = "Здесь можно расположить любую информацию.";
    cc[2] = "Ограничений для информации - нет!";
    cc[3] = "Сколько напишите, столько и будет отображено!";
    cc[4] = "Размер окошечка можно менять!";
    cc[5] = "Расположить это окно, можно где угодно!";
    cc[6] = "То, что надо поместить в <body>...<body>";
    cc[7] = "Указано в скобках комментария в коде.";
    cc[8] = "Скобки комментария выглядят вот так:";
    cc[9] = "<!--Эти слова находятся в скобках коммент.-->";
    cc[10] = "Сам скрипт надо поместить между тэгами:";
    cc[11] = " <head>.....</head> ";
    cc[12] = "Надеемся, вы всё поняли и у вас всё плучится!";
    cc[13] = " Всего Вам доброго и Удачи!";
    cc[14] = " Создавайте! Творите! Наслаждайтесь!";
    cc[15] = "Сейчас будет пустая строка, а затем повтор.";
    cc[16] = " ";
    cc[17] = "";
    cc[18] = "";
    cc[19] = "";
    cc[20] = "";

    var currentMessage = 0;
    var offset = 0;
    function stopWire() { if (wireRunning)
        clearTimeout(timerID);
        wireRunning = false
    }
    function startWire() {
        stopWire();
        showWire() }
    function showWire() {
        var text = cc[currentMessage];
        if (offset < text.length) { if (text.charAt(offset) == " ")
            offset++;
            var partialMessage = text.substring(0, offset + 1);
            document.wireForm.wireField.value = partialMessage;
            offset++;
            timerID = setTimeout("showWire()", speed);
            wireRunning = true }
        else {
            offset = 0;
            currentMessage++;
            if (currentMessage == cc.length)
                currentMessage = 0;
            timerID = setTimeout("showWire()", pause);
            wireRunning = true
        }
    }
</script>

<!-- Таблица стилей CSS -->
<style type="text/css"><!--
    /* Размер, цвет и гарнитура шрифта в форме.
     Толщина и цвет бордюра окантовки.
     Отступ слева внутрь формы. */
    .it { font-size:20px; color:#FF0080;border:#FF80C0 1px solid; padding:5px;margin: 5px }
    -->
</style>
</head>

<form name="wireForm">
    <!-- Ваш текст в формочке перед началом печатания -->
    <input class="it" type="text" value=" Здесь надо кликнуть мышкой." size="50"
           onfocus="if(!wireRunning)startWire()">
</form><!-- Закончилось все, что касается скрипта! -->
