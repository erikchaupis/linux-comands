1)	Print line  of file file.log.2014-03-30  that contains '2014-03-30 11:04:02,595' 
------------------------------------
grep -n '2014-03-30 11:04:02,595' file.log.2014-03-30

2)	Print from  678254 to 678874, lines of file file.log.2014-03-30
------------------------------------
sed -n '678254,678874p' file.log.2014-03-30
