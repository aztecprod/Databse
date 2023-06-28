# База данных - Александр Шевцов
![image](https://github.com/aztecprod/Databse/assets/25949605/717afa94-1c2c-41ff-b0f3-dda3ec1ae0e5)

Сотрудник{

Идентификатор, первичный ключ, serial

Фамилия, varchar

Имя, varchar

Отчество, varchar

Идентификатор оклада, внешний ключ, int 

Идентификатор должности, внешний ключ, int 

Идентификатор назначенного проекта, внешний ключ, int

Идентификатор даты найма, внешний ключ, int

}

Оклад {

Идентификатор, первичный ключ, serial

Значение зп, numeric

}

Должность {

Идентификатор, первичный ключ, serial

Значение_должности, varchar
}

Тип подразделения {

Идентификатор, первичный ключ, serial

Значение_типа_подразделения, varchar
}

Структурное подразделение {

Идентификатор, первичный ключ, serial

Значение_структурного_подразделения, varchar

Идентификатор типа подразделения, внешний ключ, int

}

Дата найма {

Идентификатор, первичный ключ, serial

Значение_даты_найма, mediumint

}

Адрес филиала {

Идентификатор, первичный ключ, serial

Регион, varchar

Город, varchar

Улица,дом,varchar

Идентификатор структурного подразделения, внешний ключ, int

}

Проект {  

Идентификатор, первичный ключ, serial

Значение проекта , varchar

}

