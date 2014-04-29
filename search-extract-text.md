
1)	Print line  of file verizon.log.2014-03-30  that contains '2014-03-30 11:04:02,595' 
grep -n '2014-03-30 11:04:02,595' verizon.log.2014-03-30

2)	Print from  678254 to 678874, lines of file verizon.log.2014-03-30
sed -n '678254,678874p' verizon.log.2014-03-30
