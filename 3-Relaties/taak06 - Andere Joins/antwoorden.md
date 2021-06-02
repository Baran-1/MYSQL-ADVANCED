# Antwoorden

1. Copy paste je gemaakte SQL query hieronder

SELECT name, platform FROM game, platform WHERE name LIKE 'Grand Theft Auto%'
   
2. Copy paste je gemaakte SQL query hieronder
   
SELECT * FROM game RIGHT JOIN platform ON platform.id = game.platform_id WHERE platform.platform = "SCD"
