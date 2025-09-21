Proje Hakkında

Bu proje, Python + SQLite kullanarak basit bir öğrenci-kurs veritabanı uygulamasıdır.
Amaç, veritabanı yönetimini öğrenmek isteyenler için temel SQL sorguları, CRUD işlemleri ve aggregate fonksiyonlarını örneklerle göstermektir.

🛠 Kullanılan Teknolojiler

Python (sqlite3, os)

SQLite (lokal veritabanı)

Özellikler

Öğrenci ve kurs tabloları oluşturma

Örnek veri ekleme (INSERT)

Temel sorgular (SELECT, WHERE, ORDER BY)

CRUD işlemleri (Insert, Update, Delete)

Aggregate fonksiyonları (COUNT, AVG, MAX, MIN)

Örnek SQL alıştırmaları (WHERE, LIKE, IN, NOT, ORDER BY)
Tablolar

Students
id (INTEGER, Primary Key)
name (TEXT)
age (INTEGER)
email (TEXT, UNIQUE)
city (TEXT)

Courses
id (INTEGER, Primary Key)
course_name (TEXT)
instructor (TEXT)
credits (INTEGER)

Örnek Sorgular
-- 21 yaşındaki öğrenciler
SELECT * FROM Students WHERE age = 21;

-- 'A' harfi ile başlayan öğrenciler
SELECT * FROM Students WHERE name LIKE 'A%';

-- 3 ve üzeri kredi olan dersler
SELECT * FROM Courses WHERE credits >= 3;

-- New York veya Chicago'da yaşayan öğrenciler
SELECT name, city FROM Students WHERE city IN ('New York', 'Chicago');


🎯 Öğrenim Katkısı

Bu proje ile:

SQL sorgularına giriş yapılabilir

Python üzerinden SQLite kullanımına pratik kazanılabilir

CRUD + Aggregate fonksiyonları öğrenilebilir
