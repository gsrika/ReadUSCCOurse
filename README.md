#This is to obtain data from USC course wesite and uses USC api and simple python script 
CREATE TABLE `suggest_course` (
  `pid` varchar(500) DEFAULT NULL,
  `dept` varchar(500) DEFAULT NULL,
  `cname` varchar(500) DEFAULT NULL,
  `cprefix` varchar(500) DEFAULT NULL,
  `ccode` varchar(500) DEFAULT NULL,
  `cinst` varchar(500) DEFAULT NULL,
  `cterm` varchar(500) DEFAULT NULL,
  `cyear` int(10) DEFAULT NULL,
  `cintro` varchar(1000) DEFAULT NULL
) 
