Для Oracle



/ создание таблицы trip c автоинкрементом в первом столбце trip_id (Oracle 19c)



CREATE TABLE trip (

    trip_id number generated always as identity primary key,

    name VARCHAR (30),

    city VARCHAR (25),

    per_diem decimal (8,2),

    date_first date,

    date_last date

);



/ Добавление значений в таблицу trip (Oracle 19c)



INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Баранов П.Е.', 'Москва', 700, TO_DATE('2020-01-12','YYYY-MM-DD'), TO_DATE('2020-01-17','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Абрамова К.А.', 'Владивосток', 450, TO_DATE('2020-01-14','YYYY-MM-DD'), TO_DATE('2020-01-27','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Семенов И.В.', 'Москва', 700, TO_DATE('2020-01-23','YYYY-MM-DD'), TO_DATE('2020-01-31','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Ильиных Г.Р.', 'Владивосток', 450, TO_DATE('2020-01-12','YYYY-MM-DD'), TO_DATE('2020-02-02','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Колесов С.П.', 'Москва', 700, TO_DATE('2020-02-01','YYYY-MM-DD'), TO_DATE('2020-02-06','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Баранов П.Е.', 'Москва', 700, TO_DATE('2020-02-14','YYYY-MM-DD'), TO_DATE('2020-02-22','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Абрамова К.А.', 'Москва', 700, TO_DATE('2020-02-23','YYYY-MM-DD'), TO_DATE('2020-03-01','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Лебедев Т.К.', 'Москва', 700, TO_DATE('2020-03-03','YYYY-MM-DD'), TO_DATE('2020-03-06','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Колесов С.П.', 'Новосибирск', 450, TO_DATE('2020-02-27','YYYY-MM-DD'), TO_DATE('2020-03-12','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Семенов И.В.', 'Санкт-Петербург', 700, TO_DATE('2020-03-29','YYYY-MM-DD'), TO_DATE('2020-04-05','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Абрамова К.А.', 'Москва', 700, TO_DATE('2020-04-06','YYYY-MM-DD'), TO_DATE('2020-04-14','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Баранов П.Е.', 'Новосибирск', 450, TO_DATE('2020-04-18','YYYY-MM-DD'), TO_DATE('2020-05-04','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Лебедев Т.К.', 'Томск', 450, TO_DATE('2020-05-20','YYYY-MM-DD'), TO_DATE('2020-05-31','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Семенов И.В.', 'Санкт-Петербург', 700, TO_DATE('2020-06-01','YYYY-MM-DD'), TO_DATE('2020-06-03','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Абрамова К.А.', 'Санкт-Петербург', 700, TO_DATE('2020-05-28','YYYY-MM-DD'), TO_DATE('2020-06-04','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Федорова А.Ю.', 'Новосибирск', 450, TO_DATE('2020-05-25','YYYY-MM-DD'), TO_DATE('2020-06-04','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Колесов С.П.', 'Новосибирск', 450, TO_DATE('2020-06-03','YYYY-MM-DD'), TO_DATE('2020-06-12','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Федорова А.Ю.', 'Томск', 450, TO_DATE('2020-06-20','YYYY-MM-DD'), TO_DATE('2020-06-26','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Абрамова К.А.', 'Владивосток', 450, TO_DATE('2020-07-02','YYYY-MM-DD'), TO_DATE('2020-07-13','YYYY-MM-DD'));

INSERT INTO trip (name, city, per_diem, date_first, date_last)

VALUES ('Баранов П.Е.', 'Воронеж', 450, TO_DATE('2020-07-19','YYYY-MM-DD'), TO_DATE('2020-07-25','YYYY-MM-DD'));
