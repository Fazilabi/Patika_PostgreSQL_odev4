# Patika_PostgreSQL_odev4
## [Patika.dev](www.patika.dev)

###  1. film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız. <br>
`SELECT DISTINCT replacement_cost FROM film`

###  2. film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?<br>
`SELECT COUNT  (DISTINCT replacement_cost) FROM film`

###  3. film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?<br>
`SELECT COUNT (title) FROM film` <br>
`WHERE title LIKE ('T%') AND  rating = 'G';`
###  4. country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?<br>
`SELECT COUNT(country) FROM country` <br>
`WHERE length(country) = 5;`

###  5. city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?<br>
`SELECT COUNT(city) FROM city`<br>
`WHERE city ILIKE '%r';`
