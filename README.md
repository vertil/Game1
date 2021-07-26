# testgame
In progress
Цель игры - разместить объекты в определенных местах и выйти с локации.

На локации находятся боты 2ух видов: обычные и боссы. Обычные боты - патрулируют локацию и в случае обнаружения игрока, направляются к боссу(который закреплен за этим обычным ботом), чтобы передать информацию, где он увидел игрока.

Модели гаражей сделаны собственноручно в Blender.

Логика ботов построена через blueprint класса AIController, а не через behavior tree.

Blueprint обычного бота:
[MyAi](https://blueprintue.com/blueprint/j3esf2yz/)

AIController обычного бота:
[MyAiController](https://blueprintue.com/blueprint/rfqcts5x/)

Blueprint босса бота:
[MyBoss](https://blueprintue.com/blueprint/t2wl3sla/)

AIController босса бота:
[MyBossController](https://blueprintue.com/blueprint/m076vkkw/)

Логика уровня:
[Level blueprint](https://blueprintue.com/blueprint/481ynb4o/)

Gameplay demo:

[![Gameplay](http://img.youtube.com/vi/qlWDU-fsoro/0.jpg)](https://youtu.be/qlWDU-fsoro)



Screenshoots:
![](https://github.com/vertil/Game1/blob/main/screenshoots/ScreenShot00001.png)
![](https://github.com/vertil/Game1/blob/main/screenshoots/ScreenShot00002.png)
![](https://github.com/vertil/Game1/blob/main/screenshoots/ScreenShot00003.png)
![](https://github.com/vertil/Game1/blob/main/screenshoots/ScreenShot00004.png)
![](https://github.com/vertil/Game1/blob/main/screenshoots/ScreenShot00005.png)
![](https://github.com/vertil/Game1/blob/main/screenshoots/ScreenShot00006.png)
