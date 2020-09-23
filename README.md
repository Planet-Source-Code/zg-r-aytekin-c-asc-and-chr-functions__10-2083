<div align="center">

## C\# \- Asc and Chr functions


</div>

### Description

C# - Asc and Chr functions
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Özgür Aytekin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/zg-r-aytekin.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C\#
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__10-26.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/zg-r-aytekin-c-asc-and-chr-functions__10-2083/archive/master.zip)





### Source Code

```
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none" align="center">
<font size="2"><b><span style="font-family: Verdana">www.dotnetcracks.com</span></b></font></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
&nbsp;</p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<b style="mso-bidi-font-weight: normal">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: Verdana; mso-bidi-font-family: 'Courier New'">
C# - Asc and Chr functions<?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /?><o:p></o:p></span></b></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; COLOR: blue; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; COLOR: blue; FONT-FAMILY: 'Courier New'">using</span><span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
System;<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; COLOR: blue; FONT-FAMILY: 'Courier New'">namespace</span><span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
ConsoleApplication2<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>
<span style="COLOR: blue">class</span> Class1<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>[STAThread]<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">static</span> <span style="COLOR: blue">void</span>
<?xml:namespace prefix = st1 ns = "urn:schemas-microsoft-com:office:smarttags" /?><st1:place w:st="on">
Main</st1:place>(<span style="COLOR: blue">string</span>[] args)<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>Console.WriteLine(&quot;ASCII Code for A is<span style="mso-spacerun: yes">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>:&quot; + Asc(&quot;A&quot;));<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>Console.WriteLine(&quot;Character for ASCII Code 65 is:&quot; + Chr(65).ToString());<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>Console.ReadLine();<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">private</span> <span style="COLOR: blue">static</span>
<span style="COLOR: blue">int</span> Asc(<span style="COLOR: blue">string</span>
character)<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">if</span> (character.Length == 1)<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>System.Text.ASCIIEncoding asciiEncoding = <span style="COLOR: blue">new</span>
System.Text.ASCIIEncoding();<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">int</span> intAsciiCode = (<span style="COLOR: blue">int</span>)asciiEncoding.GetBytes(character)[0];<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">return</span> (intAsciiCode);<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">else<o:p></o:p></span></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">throw</span> <span style="COLOR: blue">new</span>
ApplicationException(&quot;Character is not valid.&quot;);<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">private</span> <span style="COLOR: blue">static</span>
<span style="COLOR: blue">string</span> Chr(<span style="COLOR: blue">int</span>
asciiCode)<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">if</span> (asciiCode &gt;= 0 &amp;&amp; asciiCode &lt;= 255)<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>System.Text.ASCIIEncoding asciiEncoding = <span style="COLOR: blue">new</span>
System.Text.ASCIIEncoding();<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">byte</span>[] byteArray =
<span style="COLOR: blue">new</span> <span style="COLOR: blue">byte</span>[]{(<span style="COLOR: blue">byte</span>)asciiCode};<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">string</span> strCharacter = asciiEncoding.GetString(byteArray);<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">return</span> (strCharacter);<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">else<o:p></o:p></span></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>{<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="COLOR: blue">throw</span> <span style="COLOR: blue">new</span>
ApplicationException(&quot;ASCII Code is not valid.&quot;);<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">
<span style="mso-tab-count: 1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'">}<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; mso-layout-grid-align: none">
<span style="FONT-SIZE: 10pt; FONT-FAMILY: Verdana; mso-bidi-font-family: 'Courier New'"><o:p>&nbsp;</o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; TEXT-ALIGN: right" align="right"><st1:personname w:st="on">
<span style="FONT-SIZE: 10pt; COLOR: black; FONT-FAMILY: Verdana">Özgür Aytekin
(MCSD .NET, MCDBA)<o:p></o:p></span></p>
<p class="MsoNormal" style="MARGIN: 0in 0in 0pt; TEXT-ALIGN: right" align="right">
<span style="FONT-SIZE: 10pt; COLOR: black; FONT-FAMILY: Verdana">
<u><font color="#0000ff">oezguer.aytekin
at dotnetcracks dot com</font></u></span><span style="FONT-SIZE: 10pt; FONT-FAMILY: Verdana"><o:p></o:p></span></p>
```

