<h1 align="center">Software development of programming languages database</h1>

<h1 align="center">Разработка ПО БД языков программирования на Lazarus (Pascal) с выводом в Excel</h1>
<h2>В базе данных храняться следующие данные: :page_facing_up:</h2>
<ul>
<li>о языке программирования:
  <ul>
    <li>Название языка программирования;</li>
    <li>Дата создания;</li>
    <li>Популярные библиотеки и фреймворки;</li>
    <li>История.</li>
  </ul>
 </li>
 <li>о категориях:
  <ul>
    <li>Класс языка.</li>
  </ul>
 </li>
 <li>об областях применения:
   <ul>
     <li>Область применения.</li>
   </ul>
 </li>
 <li>хранение данных о  категориях определенного языка программирования:
   <ul>
     <li>Название языка программирования;</li>
     <li>Класс языка.</li>
   </ul>
 </li>
 <li>хранение данных об областях применения определенного языка программирования:
  <ul>
    <li>Название языка программирования;</li>
    <li>Область применения.</li>
  </ul>
</li>
</ul>
<br>
<h2>Организация защиты информации, хранящейся в базе данных :key: :lock:</h2>
<p>Защита информации хранящейся в базе данных организуется средствами MySQLServer. Доступ к базе данных может получить только 1 пользователь . Login – root, password – 090203. Кроме того, вход в программу под именем администратора производится с помощью логина-admin и пароля-090203.</p>
<br>
<h2>Модель структуры базы данных</h2> 
<img src="https://user-images.githubusercontent.com/37180024/40279344-8f639704-5c49-11e8-888c-388221fb741d.jpg">
<br>
<h2>Описание имеющегося функционала</h2>
  <ul>
    <li>Введение базы данных описания языков программирования с функциями добавления, удаления, редактирования данных и навигацией по базе данных;</li>
    <li>Введение базы данных категорий с функциями добавления, удаления, редактирования данных и навигацией по базе данных;</li>
    <li>Введение базы данных областей применения с функциями добавления, удаления, редактирования данных и навигацией по базе данных;</li>
    <li>Хранение данных о  категориях и областях применения для каждого из языков программирования;</li>
    <li>Выдача запросов  на сохранение записей перед закрытием формы, которые находятся в режиме редактирования;</li>
    <li>Проверка на наличие одинаковых записей;</li>
    <li>Поиск по введенному названию языка программирования;</li>
    <li>Вывод в Excel только тех таблиц, которые выберет сам пользователь;</li>
    <li>Вход в программу «под именем администратора/под обычным пользователем» и включающим различные привилегии в программе.</li>
  </ul> 
<img src="https://user-images.githubusercontent.com/37180024/40279965-fe8ebcde-5c54-11e8-82f4-8aece9f3211f.jpg">
<br>
<h2>Примечания :exclamation:</h2>
  <ul>
    <li>Предже чем запускать программу необходимо востановить резервную копию sql-запроса (путь до файла "all files\MySQL\programming_languages.sql", а также создать или изменить соединение следующим образом:
    <ul type="none">
      <li><img src="https://user-images.githubusercontent.com/37180024/40279781-491e8ea4-5c51-11e8-9448-ee612b29d8d3.jpg"></li>
      <li><b>Пароль:</b> 090203</li>
    </ul>
    </li>
    <li> Если при запуске программы появляется ошибка, необходимо файл "libmysql.dll", который находится в папке "all files", скопировать в папку, имеющий путь "C:\Program Files (x86)\MySQL\MySQL Server 5.7\lib\". Если это не помогло, необходимо скопировать этот же файл в основные системные папки Windows (System, System32, SysWOW64)</li>
  </ul>
<br>
<br>
<br>
<h1 align="center">Software development of the database of programming languages on Lazarus (Pascal) with output in Excel</h1>  
<h2>The following data is stored in the database: :page_facing_up:</h2>
<ul>
  <li>about the programming language:
    <ul>
      <li>The name of the programming language;</li>
      <li>Date created;</li>
      <li>Popular libraries and frameworks;</li>
      <li>History.</li>
    </ul>
  </li>
  <li>about categories:
    <ul>
      <li>Language class.</li>
    </ul>
  </li>
  <li>about the fields of application:
    <ul>
      <li>Scope of application.</li>
    </ul>
  </li>
  <li>storing data about categories of a particular programming language:
    <ul>
      <li>The name of the programming language;</li>
      <li>Language class.</li>
    </ul>
  </li>
  <li>storing data about the application areas of a particular programming language:
    <ul>
      <li>The name of the programming language;</li>
      <li>Scope of application.</li>
    </ul>
  </li>
</ul>
<br>
<h2>The organization of information protection stored in the database :key: :lock:</h2>
<p>The protection of information stored in the database is organized by means of MySQLServer. Only 1 user can access the database. Login-root, password-090203. In addition, the administrator is logged in using login-admin and password-090203</p>
<br>
<h2>Database Structure Model</h2>
<img src="https://user-images.githubusercontent.com/37180024/40279344-8f639704-5c49-11e8-888c-388221fb741d.jpg">
<br>
<h2>Description of the available functional</h2>
<ul>
  <li>Introduction of a description database for programming languages with the functions of adding, deleting, editing data and navigating through the database;</li>
  <li>Introduction of category database with functions for adding, deleting, editing data and navigating through the database;</li>
  <li>Introduction of a database of application areas with the functions of adding, deleting, editing data and navigating through the database;</li>
  <li>Storing data about categories and applications for each programming language;</li>
  <li>Issue requests to save records before closing the form, which are in edit mode;</li>
  <li>Check for duplicate records;</li>
  <li>Search for the entered name of the programming language;</li>
  <li>Output in Excel only those tables that the user chooses;</li>
  <li>Login to the program "under the administrator's name / under the normal user" and including various privileges in the program.</li> 
</ul>
<img src="https://user-images.githubusercontent.com/37180024/40279965-fe8ebcde-5c54-11e8-82f4-8aece9f3211f.jpg">
<br>
<h2>Notes :exclamation:</h2>
<ul>
  <li>Before starting the program, you need to restore the backup copy of the sql-request (the path to the file "all files\MySQL\programming_languages.sql", and also create or change the connection as follows:
    <ul type="none">
      <li><img src="https://user-images.githubusercontent.com/37180024/40279781-491e8ea4-5c51-11e8-9448-ee612b29d8d3.jpg"></li>
      <li><b>Password:</b> 090203</li>
    </ul>
  </li>
  <li>If you receive an error when you start the program, you need to copy the file "libmysql.dll", which is located in the "all files" folder, to a folder that has the path "C:\Program Files(x86)\MySQL\MySQL Server 5.7\lib\". If this did not work, you must copy the same file to the main Windows system folders (System, System32, SysWOW64)</li>
</ul>
