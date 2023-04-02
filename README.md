# Домашнее задание к занятию 12.6. «Репликация и масштабирование. Часть 1» - Пугач Евгений.


---

## `Задание 1`

### Ответ:

В конфигурации master-slave записывать и изменять данные можно только на master,  
slave предназначены только для чтения.  
В конфигурации master-master читать и записывать можно на любой из узлов.

---

## `Задание 2`

### Решение:

mysql001 - master
mysql002 - slave

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2023-04-02_23-17-07.png)

---

конфигурация master

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-19-52.png)

---

конфигурация slave

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-21-11.png)

---

статус master

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-00-23.png)

---

статус slave

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-02-13.png)

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-02-52.png)

---

проверка репликации

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-12-33.png)

![Скриншот 8](https://github.com/PugachEV72/Images/blob/master/2023-04-02_22-16-43.png)

---

