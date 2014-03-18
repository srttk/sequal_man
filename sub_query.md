### SQL  SubQuery
  SELECT  city.country,games.yr,(SELECT (count(games.yr) ) FROM games WHERE games.city=city.name)
  FROM city LEFT JOIN games
  ON (city.name = games.city)
       
       
 ##### http://sqlzoo.net/wiki/SELECT_.._JOIN
