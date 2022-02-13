-- KFGQPC Hafs Uthmanic Data
-- Version: 0.18
-- Date: 2021-10-25 
-- Update: 10.0
-- Modify word (كلا) with (Alif Madd) to display properly at most software and devices
   Adding non-breaking space before aya mark for aya_text column
   Adding non-breaking space after jozz/hizb symbol for aya_text column
   Adding Ayamark Symbol to HTML file to appear ayamark properly
   Fix Shapes with final (ي) not rendering properly with Adobe products, such as Sura Al-Baqarah(2), Aya(18)
   Modify some Jozz numbers in data files such as Sura An-Naml(27) Aya(56-59) from (19) to (20)
   Modifying Encoding of "hafsData_v17.csv" file from UTF-8 to UTF-8-BOM
   Modifying Word (فادارأتم) sura Al-Baqarah(2) aya(72) to display properly on different platforms
   Removing Kashida from different places in aya_text_emlaey column
   Modifying Aya(285) in Sura Al-Baqarah(2) in aya_text column at hafsData_v18.html file
   

It includes two folders:
1- Uthmanic Hafs Ver18 font
	- It contains font file and whole Qur'an data in MS document file
2- Uthmanic Hafs Ver18 data
	- It contains files for developers.
	
Columns:
--------
1-  id (int):	 			  Auto_increment Number
2-  jozz (int):		 		  Jozz Number
3-  sora_no (int):			  Sora Number
4-  sora_name_en (varchar):	  Sora Name in English
5-  sora_name_ar (varchar):	  Sora Name in Arabic (UthmanicHafs ttf font file)
6-  page (int):				  Page Number
7-  line_start (int):		  Start Line of Aya
8-  line_end (int):			  End Line of Aya
9-  aya_no (int):			  Aya Number
10- aya_text (text):		  Text of the Aya  in UthmanicHafs ttf font file
11- aya_text_emlaey (text):	  Emlaey Text of the Aya used for search purpose
