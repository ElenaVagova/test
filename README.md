# test 
SELECT num, COUNT (*) as count FROM worker GROUP BY num HAVING count> 1 into Tabl
Scan All
?Tabl.num
EndScan
