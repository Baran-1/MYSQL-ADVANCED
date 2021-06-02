# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
   
   SELECT game.name, platform.platform, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE game.name LIKE "B%"
   
2. Copy paste je gemaakte SQL query hieronder

SELECT game.name, platform.platform, publisher.publisher, game.year FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN publisher ON publisher_id and game.year= 2013



3. Copy paste je gemaakte SQL query hieronder

SELECT game.name, game.year,game.global_sales,genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON genre.id=5 and game.year >=2000 and genre.id




4. Copy paste je gemaakte SQL query hieronder

SELECT game.name, game.year, platform.platform, genre.genre, publisher, game.jp_sales FROM game LEFT JOIN publisher ON publisher_id LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE game.name LIKE "MARIO


5. Copy paste je gemaakte SQL query hieronder
   
