<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:0cm;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	color:black;}
h1
	{mso-style-link:"Heading 1 Char";
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:.5pt;
	text-indent:-.5pt;
	line-height:107%;
	page-break-after:avoid;
	font-size:16.0pt;
	font-family:"Calibri",sans-serif;
	color:black;
	font-weight:normal;}
span.Heading1Char
	{mso-style-name:"Heading 1 Char";
	mso-style-link:"Heading 1";
	font-family:"Calibri",sans-serif;
	color:black;}
.MsoPapDefault
	{margin-bottom:8.0pt;
	line-height:107%;}
@page WordSection1
	{size:595.3pt 841.9pt;
	margin:72.0pt 35.15pt 72.0pt 72.0pt;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>


<div class=WordSection1>

<h1 style='margin-left:-.25pt'>Relevant Paper:-�� </h1>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:15.85pt;
margin-left:-.25pt;text-indent:-.5pt;line-height:107%'><span style='font-size:
12.0pt;line-height:107%'>JUIndoorLoc: A Ubiquitous Framework for
Smartphone-Based Indoor Localization Subject to Context and Device
Heterogeneity [1] </span></p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;
margin-left:-.25pt;text-indent:-.5pt'><span style='font-size:16.0pt;line-height:
107%'>Authors:- </span></p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:15.85pt;
margin-left:-.25pt;text-indent:-.5pt;line-height:107%'><span style='font-size:
12.0pt;line-height:107%'>Priya Roy, Chandreyee Chowdhury, Dip Ghosh,
Sanghamitra Bandyopadhyay. </span></p>

<h1 style='margin-left:-.25pt'>Dataset Information:- </h1>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:1.2pt;
margin-left:35.25pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-18.0pt;line-height:111%'><span style='font-family:Wingdings'>&#10146;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span><span dir=LTR></span>The
data has been captured from 3<sup>rd</sup>, 4<sup>th</sup> and 5<sup>th</sup>
floors of a five-storied building at Jadavpur University.� </p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:1.2pt;
margin-left:35.25pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-18.0pt;line-height:111%'><span style='font-family:Wingdings'>&#10146;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span><span dir=LTR></span>JUIndoorLoc
dataset, containing 25,364 samples,� is divided into two datasets:� </p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:1.2pt;
margin-left:72.0pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-18.0pt;line-height:111%'>a)<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span dir=LTR></span>Training (23,904 samples) and </p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:1.2pt;
margin-left:72.0pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-18.0pt;line-height:111%'>b)<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span dir=LTR></span>Testing (1,460 samples) </p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:1.2pt;
margin-left:35.25pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-18.0pt;line-height:111%'><span style='font-family:Wingdings'>&#10146;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span><span dir=LTR></span>Each
sample of the two datasets consists of 177 attributes. These attributes contain
RSSI values of 172 wireless access points (AP) along with the corresponding
location point (cell) identifier, time, device identifier and contextual
changes (open/closed room and presence/absence of the user in the vicinity). </p>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:16.3pt;
margin-left:35.25pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-18.0pt;line-height:111%'><span style='font-family:Wingdings'>&#10146;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span><span dir=LTR></span>The
RSSI values are represented as negative integer values ranging -11dBm to
-100dBm (extremely weak signal). A negative value -110 is used to denote when
an AP was not detected.� </p>

<h1 style='margin-left:-.25pt'>Attributes Information of JUIndoorLoc dataset:- </h1>

<p class=MsoNormal style='margin-bottom:3.45pt'><span style='font-size:4.0pt;
line-height:107%'>�</span></p>

<table class=TableGrid border=0 cellspacing=0 cellpadding=0 width=652
 style='width:488.85pt;margin-left:-5.4pt;border-collapse:collapse'>
 <tr style='height:14.4pt'>
  <td width=75 valign=top style='width:56.4pt;border:solid #999999 1.0pt;
  border-bottom:solid #666666 1.5pt;padding:2.4pt 2.9pt .3pt 5.4pt;height:14.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b><i>Attribute </i></b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:solid #999999 1.0pt;
  border-left:none;border-bottom:solid #666666 1.5pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:14.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b><i>MySQL data type </i></b></p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:solid #999999 1.0pt;
  border-left:none;border-bottom:solid #666666 1.5pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:14.4pt'>
  <p class=MsoNormal align=center style='margin-top:0cm;margin-right:2.5pt;
  margin-bottom:0cm;margin-left:0cm;text-align:center'><b><i>Description </i></b></p>
  </td>
 </tr>
 <tr style='height:54.7pt'>
  <td width=75 valign=top style='width:56.4pt;border:solid #999999 1.0pt;
  border-top:none;padding:2.4pt 2.9pt .3pt 5.4pt;height:54.7pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b>C</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>id</span></i> </b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:54.7pt'>
  <p class=MsoNormal style='margin-bottom:0cm'>VARCHAR(15) </p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:54.7pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:2.45pt;margin-bottom:
  0cm;margin-left:0cm;text-align:justify;text-justify:inter-ideograph'>A unique
  number to identify the indoor region where the capture is taken. Each cell
  number has two part, the first part is floor number and the second part is
  the position of a cell on the two-dimensional building map. </p>
  </td>
 </tr>
 <tr style='height:44.4pt'>
  <td width=75 valign=bottom style='width:56.4pt;border:solid #999999 1.0pt;
  border-top:none;padding:2.4pt 2.9pt .3pt 5.4pt;height:44.4pt'>
  <p class=MsoNormal style='margin-bottom:8.7pt'><b>AP</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>001</span></i>-</b></p>
  <p class=MsoNormal style='margin-bottom:0cm'><b>AP</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>172</span></i> </b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:44.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm'>INT(4) </p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:44.4pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:2.25pt;margin-bottom:
  0cm;margin-left:0cm;text-align:justify;text-justify:inter-ideograph'>Received
  signal strength value of 172 APs. Negative integer values from 11dBm to
  -100dBm and -110 used to identify the APs which are not detected in scan
  duration. </p>
  </td>
 </tr>
 <tr style='height:27.35pt'>
  <td width=75 style='width:56.4pt;border:solid #999999 1.0pt;border-top:none;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b>R</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>s</span></i> </b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm'>BOOL </p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;text-justify:
  inter-ideograph'>Represents status of the room, the value is either 1 or 0. 1
  and 0 represent open and closed room respectively. </p>
  </td>
 </tr>
 <tr style='height:27.35pt'>
  <td width=75 style='width:56.4pt;border:solid #999999 1.0pt;border-top:none;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b>H</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>pr</span></i> </b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm'>BOOL </p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;text-justify:
  inter-ideograph'>Represents the presence or absence of human, the value is
  either 1 or 0. 1 and 0 represent the presence and absence of human
  respectively. </p>
  </td>
 </tr>
 <tr style='height:85.95pt'>
  <td width=75 valign=top style='width:56.4pt;border:solid #999999 1.0pt;
  border-top:none;padding:2.4pt 2.9pt .3pt 5.4pt;height:85.95pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b>D</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>id</span></i> </b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:85.95pt'>
  <p class=MsoNormal style='margin-bottom:0cm'>VARCHAR(10) </p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:85.95pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:2.55pt;margin-bottom:
  1.55pt;margin-left:0cm;text-align:justify;text-justify:inter-ideograph;
  line-height:104%'>A unique identifier is assigned to each Android device,
  which is used to capture data. These device Identifiers are given below : D<sub>1</sub>
  : Samsung Galaxy Tab 2, Android version 4.1.1 </p>
  <p class=MsoNormal style='margin-bottom:1.0pt'>D<sub>2</sub> ���������� :
  Samsung Galaxy Tab E, Android version 5.0 </p>
  <p class=MsoNormal style='margin-bottom:1.0pt'>D<sub>3</sub> ��������� :
  Samsung Galaxy Tab 10, Android version 4.0 </p>
  <p class=MsoNormal style='margin-bottom:0cm'>D<sub>4</sub> ��������� :
  Motorola Moto E 2nd Generation, Android version 5.1� </p>
  </td>
 </tr>
 <tr style='height:27.5pt'>
  <td width=75 style='width:56.4pt;border:solid #999999 1.0pt;border-top:none;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm'><b>T</b><b><i><span
  style='font-size:11.5pt;line-height:107%'>s</span></i> </b></p>
  </td>
  <td width=123 valign=top style='width:92.2pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm'>BIGINT(8) </p>
  </td>
  <td width=454 valign=top style='width:340.25pt;border-top:none;border-left:
  none;border-bottom:solid #999999 1.0pt;border-right:solid #999999 1.0pt;
  padding:2.4pt 2.9pt .3pt 5.4pt;height:27.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;text-justify:
  inter-ideograph'>13-digit integer value used to record time when the capture
  is taken following library of java.util package. </p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;
margin-left:.5pt;text-align:justify;text-justify:inter-ideograph;text-indent:
-.5pt;line-height:111%'><u><span style='font-size:16.0pt;line-height:111%'>Disclaimer</span></u><span
style='font-size:16.0pt;line-height:111%'>:- </span>This dataset can only be
used for academic purpose. </p>

<p class=MsoNormal style='margin-bottom:12.1pt'>�</p>

<p class=MsoNormal style='margin-bottom:.7pt;line-height:normal'><span
style='color:#222222'>[1] Roy P, Chowdhury C, Ghosh D, Bandyopadhyay S.
JUIndoorLoc: A Ubiquitous Framework for SmartphoneBased Indoor Localization
Subject to Context and Device Heterogeneity. Wireless Personal Communications. </span></p>

<p class=MsoNormal style='margin-bottom:0cm'><span style='color:#222222'>2019:1-24,
</span><span style='font-size:10.0pt;line-height:107%;color:blue'>doi:10.1007/s11277-019-06188-2</span><span
style='font-size:10.0pt;line-height:107%'>, URL </span><span style='font-size:
10.0pt;line-height:107%;color:blue'>https://doi.org/10.1007/s11277-019-06188-2.</span><span
style='font-size:10.0pt;line-height:107%'> </span></p>

</div>
