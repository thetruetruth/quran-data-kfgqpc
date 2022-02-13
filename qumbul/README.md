-- KFGQPC Qumbul Uthmanic Data
-- Version: 0.7
-- Date: 2021-08-08
-- Update: 3.0
-- Modifying by adding two dots at word (إبراهيم) in whole Mushaf
   Adding non-breaking space before aya mark for aya_text column
   Adding non-breaking space after jozz/hizb symbol for aya_text column
   Adding Ayamark Symbol to HTML file to appear ayamark properly
   Modifying Encoding of "QumbulData_v07.csv" file from UTF-8 to UTF-8-BOM
   Modifying Sura(84) Aya(12) and Sura(96) Aya(7)

It includes two folders:
1- Uthmanic Qumbul Ver07 font
	- It contains font file and whole Qur'an data in MS document file
2- Uthmanic Qumbul Ver07 data
	- It contains files for developers.

Columns:
--------
1-  id (int):	 			  Auto_increment Number
2-  jozz (int):		 		  Jozz Number
3-  page (varchar):			  Page Number (There are some Ayat in two pages we separated with – symbol)
4-  sura_no (int):			  Sura Number
5-  sura_name_en (varchar):	  Sura Name in English
6-  sura_name_ar (varchar):	  Sura Name in Arabic (UthmanicQumbul unicode font)
7-  line_start (int):		  Start Line of Aya
8-  line_end (int):			  End Line of Aya
9-  aya_no (int):			  Aya Number
10- aya_text (text):		  Text of the Aya  in UthmanicQumbul unicode font
