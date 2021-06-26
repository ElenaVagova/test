# test 
SELECT num, COUNT (*) as count FROM worker GROUP BY num HAVING count> 1 into Tabl
Scan All
?Tabl.num
EndScan

ИЛИ ДОПОЛНИТЕЛЬНО:

fl=fals
For i=1 to n+1
   For j=i+1 to n
   If a(i)= a(j) then
      Print a(i)
      fl=true
      exit
   Endif
   Next
   if  fl=true then
     exit 
   endif
Next
if !fl then 
print "-1" 
endif
