-- KFGQPC Soosi Uthmanic Data
-- Version: 0.9
-- Date: 2020-12-27
-- Update: 1.0
-- Modifying in Aya(43) page(272) by removing Shadda on word (يوحى)
   Modifying in Aya(25) page(153) by replace shape of Emmala in word (التقوى)
   Adding non-breaking space before aya mark for aya_text column
   Adding non-breaking space after jozz/hizb symbol for aya_text column
   Adding Ayamark Symbol to HTML file to appear ayamark properly

It includes two folders:
1- Uthmanic Soosi Ver09 font
	- It contains font file and whole Qur'an data in MS document file
2- Uthmanic Soosi Ver09 data
	- It contains files for developers.

Columns:
--------
1-  id (int):	 			  Auto_increment Number
2-  jozz (int):		 		  Jozz Number
3-  page (varchar):			  Page Number (There are some Ayat in two pages we separated with – symbol)
4-  sura_no (int):			  Sura Number
5-  sura_name_en (varchar):	  Sura Name in English
6-  sura_name_ar (varchar):	  Sura Name in Arabic (UthmanicSoosi unicode)
7-  aya_no (int):			  Aya Number
8-  line_start (int):		  Start Line of Aya
9-  line_end (int):			  End Line of Aya
10- aya_text (text):		  Text of the Aya  in UthmanicSoosi unicode
