-- KFGQPC Qaloon Uthmanic Data
-- Version: 0.10
-- Date: 2021-08-08
-- Update: 3.0
-- Adding non-breaking space before aya mark for aya_text column
   Adding non-breaking space after jozz/hizb symbol for aya_text column
   Adding Ayamark Symbol to HTML file to appear ayamark properly
   Modifying Encoding of "QaloonData_v9.csv" file from UTF-8 to UTF-8-BOM
   Replacing Letter Alef Maksura with its position ​in unicode standard instead of Letter Yeh
   
It includes two folders:
1- Uthmanic Qaloon Ver10 font
	- It contains font file and whole Qur'an data in MS document file
2- Uthmanic Qaloon Ver10 data
	- It contains files for developers.

Columns:
--------
1-  id (int):	 			  Auto_increment Number
2-  jozz (int):		 		  Jozz Number
3-  page (varchar):			  Page Number (There are some Ayat in two pages we separated with – symbol)
4-  sura_no (int):			  Sura Number
5-  sura_name_en (varchar):	  Sura Name in English
6-  sura_name_ar (varchar):	  Sura Name in Arabic (UthmanicQaloon unicode font)
7-  line_start (int):		  Start Line of Aya
8-  line_end (int):			  End Line of Aya
9-  aya_no (int):			  Aya Number
10- aya_text (text):		  Text of the Aya  in UthmanicQaloon unicode font


