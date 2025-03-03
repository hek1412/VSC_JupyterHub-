# VSC_JupyterHub
Порядок подключения из VSC к блокноту на хабе

Устанавливаем расширение в VSC

![image](https://github.com/user-attachments/assets/3b02f051-4afa-48dd-bc9f-ba34bf5bad14)

Открываем любую папку

![image](https://github.com/user-attachments/assets/f3869031-57cd-4905-acae-4c0a900ec30c)

Откройте или создайте файл блокнота, открыв палитру команд ( Ctrl+Shift+P) и выбрав Jupyter: Create New Jupyter Notebook.

![image](https://github.com/user-attachments/assets/85b11db6-0e29-4380-afd3-2f3af7f86ed0)

Откройте средство выбора ядра, щелкнув по нему в правом верхнем углу блокнота или вызвав Notebook: Select Notebook Kernel команду
Выберите вариант Existing JupyterHub Server...

![image](https://github.com/user-attachments/assets/121fcc01-f2cb-4917-8e06-eab5c271ce65)
![image](https://github.com/user-attachments/assets/666cb95e-0968-4f28-bedd-72d1a1f76552)

Теперь заходим на https://jupiter45.skayfaks.keenetic.pro/hub/
логинимся и нажимаем на вкладку токен
![image](https://github.com/user-attachments/assets/3498c99f-0c68-4cba-83e4-9e4a3cc8d8e4)

В новом окне пишем имя токену, создаем сам токен и сохраняем его

![image](https://github.com/user-attachments/assets/72f9707d-e94c-4511-bd34-8d862108e699)

Теперь возвращаемся в VSC и вводим URL-адрес сервера JupyterHub, имя пользователя и полученный токен API 

https://jupiter45.skayfaks.keenetic.pro/?token=662c345346346356363684c2cc0 (токен нужно вставить свой)

![image](https://github.com/user-attachments/assets/d8412ccc-175f-4c99-919e-f333cc4115d9)

После выбираем ядро (это собственно запуск кода на хабе в своем блокноте)

![image](https://github.com/user-attachments/assets/0b09e782-e1fa-4194-be47-250a46b2c3f5)

Проверяем доступ к GPU

![image](https://github.com/user-attachments/assets/f96d371f-7adc-435b-a483-a6c084f15029)

Теперь можно работать с файлами на своем компьютере, но запуская их на сервере, после сохранения кода, он остается только локально, не забываем делать push в GitHub
