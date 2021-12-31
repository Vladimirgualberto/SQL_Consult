# SQL_Consult
SQL search for Interval date based in current date - CONCAT, DATE_ADD

SELECT * FROM database.instance  WHERE calldate >= CONCAT(YEAR(CURRENT_DATE()),'-',MONTH(DATE_ADD(CURRENT_DATE(), INTERVAL - 2 MONTH)), '-01');

The result of this search in database is last 3 month data.

Function CONCAT - used to agroup name string, for instance CONCAT("JOHN","KARTER") result in JOHNKARTER
Function DATE_ADD - adds a time/date interval to a date and then returns the date
Function CURRENT_DATE - get the current date




Vladimir Gualberto
