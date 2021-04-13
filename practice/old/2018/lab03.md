# Задание на лабораторную работу №3
## Распознавание изображений с использованием OpenCV

В среде ROS (Robotic Operating System) необходимо разработать программу для робота и проверить ее работоспособность во встроенном эмуляторе Gazebo на примере робота TurtleBot.
Робот должен по заранее заданным координатам подсчитать количество объектов на поле, заданных вариантом задания. При этом количество объектов, отличных от целевых, должно быть минимум в 2 раза больше.
Выбор среды эмуляции (манифест) и вид робота остается на усмотрение студента.
При запуске программы должна появляться среда эмуляции с роботом, в которой робот должен автоматически выполнить задание. 

### Последовательность выполнения лабораторной работы:
1.	Подготовить файл .world с объектом, заданным вариантом, и "лишними" объектами.
2.	Изменить в папке файл ~/catkin_ws/src/fist_robotics_labs/src/lab3.py для выполнения задания по варианту.

### Варианты заданий:
1.	Красный шар
2.	Зеленый куб
3.	Синий куб
4.	Желтый куб
5.	Зеленый шар
6.	Синий цилиндр
7.	Фиолетовый шар
8.	Красный куб
9.	Желтая пирамида
10.	Желтый цилиндр
11.	Синий шар
12.	Зеленый цилиндр


### Отчет по выполненной работе
1.	Титульный лист.
2.	Описание задания по варианту.
3.	Описания запускаемых команд
4.	Скриншот программы Gazebo, RViz и описание программы и всех функциональных блоков.
5.	[ Листинг программы с комментариями и описание работы программы].
6.	Выводы по лабораторной работе: что удалось сделать, с какими трудностями столкнулись, в чем видите пользу от используемых в лабораторной работе технологиях.

### Библиографический список
1.	М.Шахинпур. Курс робототехники.
2.	Юревич Е.И. Основы робототехники.
3.	http://ros.org
4.	http://learn.turtlebot.com/
5.	http://gazebosim.org/
6.	https://geektimes.ru/post/281760/ - описание установки ROS в среде Ubuntu на русском языке
7.	http://wiki.ros.org/turtlesim
8.	http://ros.org
9. Morgan Quigley, Brian Gerkey & William D. Smart. Programming robots with ROS. Автоматные модели: глава 13, State machines
10. Использование текстур в мире Gazebo: [1](http://answers.gazebosim.org/question/4761/how-to-build-a-world-with-real-image-as-ground-plane/) [2](http://answers.gazebosim.org/question/7922/ground-plane-texture-image/)
11. [Turtlebot docs](http://learn.turtlebot.com/)