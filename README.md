# PZ-2_Devops_2026_Svyrydenko_Eva_TSK-31
 **<h3>ПЗ-2 Свириденко Єва ЦК-31<h3>**
___
***Написання скриптiв мовою Bash***
___


***Скриншоти виконаного завдання***
___
<img width="1071" height="220" alt="image" src="https://github.com/user-attachments/assets/88dd5e85-6f10-45e3-87b2-ec0730293452" />
<img width="1074" height="605" alt="image" src="https://github.com/user-attachments/assets/078c7e00-97fd-4f2c-883a-ff9067c12e9b" />
<img width="1072" height="596" alt="image" src="https://github.com/user-attachments/assets/1ea7c1c8-4797-4f76-b362-994ba40055a0" />
<img width="1060" height="596" alt="image" src="https://github.com/user-attachments/assets/5372b2a7-be86-47bb-9550-85aa19190b00" />
<img width="1076" height="557" alt="image" src="https://github.com/user-attachments/assets/61600fae-151a-4b13-b4cf-5ea9d347cb9a" />




Контрольні питання та відповіді


--- 
№1. Призначення Bash, структура скрипта на Bash

Bash — це оболонка Linux/Unix для виконання команд та скриптів.

Структура скрипта:

Шебанг #!/bin/bash

Коментарі #

Змінні

Логіка: умови, цикли, команди

Вивід та завершення




--- 

№2. Змінні в Bash

Оголошення: VAR=value (без пробілів навколо =)

Використання: $VAR

Типи: рядки та числа

Приклад:

NAME="Ivan"
echo "Hello, $NAME"




--- 

№3. Команди для введення з клавіатури і виведення в консоль

Вивід: echo, printf

Введення: read

Приклад:

read -p "Введіть ім'я: " USER_NAME
echo "Привіт, $USER_NAME"



--- 

№4. Умови в Bash

Конструкція: if [ умова ]; then ... else ... fi

Перевірка файлів: -f, порівняння чисел: -eq, -ne, -lt, -gt, рядків: =, !=

Приклад:

if [ -f "file.txt" ]; then
    echo "Файл існує"
else
    echo "Файл не знайдено"
fi




--- 

№5. Цикли, які використовуються в Bash

for:

for i in 1 2 3; do
    echo $i
done

while:

count=0
while [ $count -lt 5 ]; do
    echo $count
    ((count++))
done

until:

count=0
until [ $count -eq 5 ]; do
    echo $count
    ((count++))
done




--- 
№6. Написання скриптів на Bash

Створити файл, наприклад script.sh

Додати шебанг: #!/bin/bash

Написати логіку: змінні, команди, умови, цикли

Зробити виконуваним: chmod +x script.sh

Запустити: ./script.sh або bash script.sh




--- 
