# testgame
В процессе разработки
Цель игры - разместить объекты в определенных местах и выйти с локации.

На локации находятся боты 2ух видов: обычные и боссы. Обычные боты - патрулируют локацию и в случае обнаружения игрока, направляются к боссу(который закреплен за этим обычным ботом), чтобы передать информацию, где он увидел игрока.


Логика ботов построена через blueprint класса player controller, а не через behavior tree.

Blueprint обычного бота:
[MyAi](https://blueprintue.com/blueprint/j3esf2yz/)

Controller обычного бота:
[MyAiController](https://blueprintue.com/blueprint/rfqcts5x/)

Blueprint босса бота:
[MyBoss](https://blueprintue.com/blueprint/t2wl3sla/)

Controller босса бота:
[MyBossController](https://blueprintue.com/blueprint/m076vkkw/)

Логика уровня:
[Level blueprint](https://blueprintue.com/blueprint/481ynb4o/)

Скриншоты локации:
![s](https://drive.google.com/file/d/1eQk_cdY9NLBNlR6jr8TTNR84qKuB30Un/view?usp=sharing)