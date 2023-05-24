1#SORU - city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

1#CEVAP - SELECT city, country FROM city
INNER JOIN country ON city.country_id = country.country_id

1#<img width="960" alt="1" src="https://github.com/ugurcnsft/Patika-SQL-Odev-9/assets/129968939/67630828-512b-40bd-aebd-cbe674dc8c7a">

2#SORU - customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

2#CEVAP - SELECT payment_id, first_name, last_name FROM customer
INNER JOIN payment ON payment.customer_id = customer.customer_id

2#<img width="960" alt="2" src="https://github.com/ugurcnsft/Patika-SQL-Odev-9/assets/129968939/af2faab8-f11d-4715-be45-46c5ae9a0261">

3#SORU - customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

3#CEVAP - SELECT rental_id, first_name, last_name FROM customer
INNER JOIN rental ON rental.customer_id = customer.customer_id

3#<img width="960" alt="3" src="https://github.com/ugurcnsft/Patika-SQL-Odev-9/assets/129968939/fd205ca2-7982-43ff-96cb-314930d4daff">

