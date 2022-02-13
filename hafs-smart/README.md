دليل الاستخدام
يستخدم لعرض الآيات بالرسم العثماني على الأجهزة الذكية، وهو ليس معداً لعرض كامل صفحة المصحف مطابقة لمصحف المدينة النبوية، ولكنه يستخدم لعرض النص القرآني على مستوى الآيات فقط.. مثل عرض نص الآيات في نتائج البحث، عرض نص الآيات في كتاب التفسير أوالكتب الأخرى.
/************************
=========================
************************/

-- KFGQPC Hafs Uthmanic Data for Smart Phone
-- Version: 0.8
-- Updated Date: 2021-08-04 
-- Updated: 5.0
  - Correct some words by remove spaces between them in 43 places. i.e: sura:2, page:12, aya:77  	
  – Modifying Encoding of “hafs_smart_v8.csv” file from UTF-8 to UTF-8-BOM
  - Modify some Jozz numbers in data files such as Sura An-Naml(27) Aya(56-59) from (19) to (20)
  - Removing Kashida from different places in aya_text_emlaey column
  - Adding line_start column and line_end column in data table
   

It includes two folders:
1- Uthmanic Hafs Smart Ver8 font
	- It contains font file and whole Qur'an data in MS document file
2- Uthmanic Hafs Smart Ver8 data
	- It contains files for developers.
	
Columns:
--------
1-  id (int):	 			  Auto_increment Number
2-  jozz (int):		 		  Jozz Number
3-  sora_no (int):			  Sora Number
4-  sora_name_en (varchar):	  Sora Name in English
5-  sora_name_ar (varchar):	  Sora Name in Arabic
6-  page (int):				  Page Number
7-  line_start (int):		  Start Line of Aya
8-  line_end (int):			  End Line of Aya
9-  aya_no (int):			  Aya Number
10- aya_text (text):		  Text of the Aya in UthmanicHafs Smart unicode
11- aya_text_emlaey (text):	  Emlaey Text of the Aya used for search purpose
