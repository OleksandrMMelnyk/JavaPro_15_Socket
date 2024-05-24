# JavaPro_15_Socket
## Створення ServerSocket додатку
Мета:  
Розробити серверне додаток, яке використовує `ServerSocket` для з'єднання з клієнтом і обміну повідомленнями.  
Деталі завдання:  
1. При старті вашого додатка, він повинен слухати порт `8081` і очікувати підключення лише одного клієнта.  
2. Після того, як клієнт підключився до сервера, обидві сторони повинні обмінятися привітаннями. Наприклад: з англійської "hello" перекладається як "привіт" на українську.  
3. Якщо у привітанні клієнта є російські букви, яких немає в українській мові, ваш сервіс повинен надіслати запитання: "що таке паляниця?".  
4. Якщо клієнт відповість правильно на це питання, сервер повинен відправити поточну дату та час, а потім попрощатися з клієнтом. Якщо відповідь буде неправильною, клієнт повинен бути відключений.  

Підказка:  
Для отримання поточної дати та часу використовуйте стандартний Java API, наприклад, класи `LocalDate` та `LocalTime`.  

Додатково:  
Можна додати обробку помилок, логування та додаткові функції, якщо бажаєте.
