# Change Log

## 2.3-beta.1 (2018-07-26)
Upgrade to PostgreSQL 11 (Beta 2).  
See https://www.postgresql.org/about/news/1867/ 

## 2.2 (2017-10-06)
Upgrade to PostgreSQL 10.  
See https://www.postgresql.org/about/news/1786/ 

## 2.1.1 (2017-10-05)
Simplify Dockerfile (no need for zipped SQL scripts)

## 2.1 (2016-06-22)
Add _country_fk_ (city.country_code -> country.code)

## 2.0 (2016-05-17)
Upgrade to PostgreSQL 9.6.  
Normalization : change table and columns names to [snake case](https://en.wikipedia.org/wiki/Snake_case).  
See also this question on SO : [PostgreSQL naming conventions](http://stackoverflow.com/questions/2878248/postgresql-naming-conventions). 

## 1.0 (2016-05-16)
Initial release.  
Based on PostgreSQL 9.5.  
Source : [world-1.0](http://pgfoundry.org/frs/shownotes.php?release_id=366) database (2005-12-02).
