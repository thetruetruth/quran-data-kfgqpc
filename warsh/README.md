-- KFGQPC Warsh Uthmanic Data
-- Version: 0.10
-- Date: 2021-08-05
-- Update: 4.0
-- Adding non-breaking space before aya mark for aya_text column
   Adding non-breaking space after jozz/hizb symbol for aya_text column
   Adding Ayamark Symbol to HTML file to appear ayamark properly
   Adding space at sura (An-Naḥl) aya (123) between the aya number and last word of it
   Adding sign of hizb at sura (Al-‘Ankabūt) aya (7)
   Adding/Removing Waqqf sign at different places
   Adding/Removing Sajjda sign at different places
   Modify at Sura Al-Anfāl in line 11 to contain 9 words instead of 11 words
   Modifying Encoding of "warshData_v9.csv" file from UTF-8 to UTF-8-BOM
   Removing Sajda mark from some Sura's(22,53,84,96)

It includes two folders:
1- Uthmanic Warsh Ver09 font
	- It contains font file and whole Qur'an data in MS document file
2- Uthmanic Warsh Ver09 data
	- It contains files for developers.

Columns:
--------
1-  id (int):	 			  Auto_increment Number
2-  jozz (int):		 		  Jozz Number
3-  page (varchar):			  Page Number (There are some Ayat in two pages we separated with – symbol)
4-  sura_no (int):			  Sura Number
5-  sura_name_en (varchar):	  Sura Name in English
6-  sura_name_ar (varchar):	  Sura Name in Arabic (UthmanicWarsh ttf font file)
7-  aya_no (int):			  Aya Number
8-  line_start (int):		  Start Line of Aya
9-  line_end (int):			  End Line of Aya
10- aya_text (text):		  Text of the Aya  in UthmanicWarsh ttf font file


