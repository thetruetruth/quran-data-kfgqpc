# Quran Data KFGQPC

Quran Data from King Fahd Glorious Quran Printing Complex <a href="https://qurancomplex.gov.sa/en/techquran/dev/" rel="noopener" target="_blank" title="Source">(https://qurancomplex.gov.sa/en/techquran/dev/)</a>. 

Repository contains folder for 8 different kinds of Al-Quran Qiraat (narrations/ way of reading) in Arabic language text and its font required to properly display on web or Windows. All text follows Arabic Unicode Uthmanic Font of the Quran and for each narration is available in CVS, HTML, JSON, SQL, XLSX and XML respectively. You may use this data by downloading from Github or serve over CDN (<a href="https://www.jsdelivr.com/" rel="noopener" target="_blank" title="Jsdelivr website">Jsdelivr</a>,<a href="https://raw.githack.com/" rel="noopener" target="_blank" title="raw.githack.com website">raw.githack.com</a> or <a href="https://statically.io/" rel="noopener" target="_blank" title="statically.io website">statically.io</a>)

## Available Arabic Unicode and Font

<details>
<summary>Summary about narrations available</summary>

**Hafs Narration for smart devices** : It is used to display verses in Ottoman graphic on smart devices, and it is not intended to display the entire page of the Qur’an identical to the Qur’an of the Prophet’s city, but it is used to display the Qur’anic text at the level of verses only. Such as displaying the text of verses in the search results, displaying the text of the verses in the book of interpretation or other books.

**Hafs Narration** : It is a computer font dedicated to displaying the Qur’an text in conformity with the Ottoman graphic. It was built in accordance with the Unicode universal coding, which is a global system that enables data to travel across different systems and devices without any fear of distorting display.

**Warsh Narration** : It is the way of read by the people of the Maghreb, West and Central Africa, and Western Europe (France and Spain). It is fully described using the regular keyboard, without the need to include any symbols that do not comply with the Unicode standard system. The entire text of the Holy Qur’an according to the Ottoman drawing corresponding to the Qur’an of the Prophet’s city for the mentioned narration.

**Shouba Narration** : Shu'bah narration on the authority of Asim al-Kufi: It is one of the narrations that specialists benefit from in the recitation of students of knowledge and others.

**Qaloon Narration** : The narration of Qaloun on Nafeh al-Madani: It is the narration that the people of Libya, Tunisia and some regions read in Mauritania.

**Doori Narration** : Al-Douri's narration on the authority of Abu Amr Al-Basri: It is the narration that the people of Sudan and East Africa read.

**Soosi Narration** : The Reading of Al-Sousi on the authority of Abu Amr Al-Basri: It is one of the narrations from which the specialists in recitation benefit from students of knowledge and others.


**Bazzi Narration** : The narration of Al-Bazzi on the authority of Abu Amr Al-Basri: It is one of the narrations from which the specialists in recitation benefit from students of knowledge and others.

**Qumbul Narration** : The narration of Qumbul on the authority of Abu Amr Al-Basri: It is one of the narrations from which the specialists in recitation benefit from students of knowledge and others.

</details>

### Latest Unicode Uthmanic Font Version and Format

| Narration | Version # | Format |
| --- | --- | --- |
| Hafs smart | 8 | ttf & woff2 |
| Hafs | 18 | ttf & woff2 |
| Warsh | 10 | ttf & woff2 |
| Shouba | 8 | ttf & woff2 |
| Qaloon | 10 | ttf & woff2 |
| Doori | 9 | ttf & woff2 |
| Soosi | 9 | ttf & woff2 |
| Bazzi | 7 | ttf & woff2 |
| Qumbul | 7 | ttf & woff2 |

### Usage 

Declaration on HTML file

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/css/kfgqpc.font.css" />
```

Declaration on CSS file

```css
/*Inside CSS file*/
.hafssmart{font-family: "hafssmart8"}
.hafs{font-family: "hafs18"}
.warsh{font-family: "warsh10"}
.shouba{font-family: "shouba8"}
.qaloon{font-family: "qaloon10"}
.doori{font-family: "doori9"}
.soosi{font-family: "soosi9"}
.bazzi{font-family: "bazzi7"}
.qumbul{font-family: "qumbul7"}
@font-face {font-family: "hafssmart8";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/hafs-smart/font/hafssmart.8.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/hafs-smart/font/hafssmart.8.ttf") format ("truetype");}
@font-face {font-family: "hafs18";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/hafs/font/hafs.18.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/hafs/font/hafs.18.ttf") format ("truetype");}
@font-face {font-family: "warsh10";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/warsh/font/warsh.10.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/warsh/font/warsh.10.ttf") format ("truetype");}
@font-face {font-family: "shouba8";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/shouba/font/shouba.8.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/shouba/font/shouba.8.ttf") format ("truetype");}
@font-face {font-family: "qaloon10";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/qaloon/font/qaloon.10.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/qaloon/font/qaloon.10.ttf") format ("truetype");}
@font-face {font-family: "doori9";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/doori/font/doori.9.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/doori/font/doori.9.ttf") format ("truetype");}
@font-face {font-family: "soosi9";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/soosi/font/soosi.9.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/soosi/font/soosi.9.ttf") format ("truetype");}
@font-face {font-family: "bazzi7";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/bazzi/font/bazzi.7.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/bazzi/font/bazzi.7.ttf") format ("truetype");}
@font-face {font-family: "qumbul7";src: url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/qumbul/font/qumbul.7.woff2") format ("woff2"),url("https://cdn.jsdelivr.net/gh/thetruetruth/quran-data-kfgqpc@main/qumbul/font/qumbul.7.ttf") format ("truetype");}
```