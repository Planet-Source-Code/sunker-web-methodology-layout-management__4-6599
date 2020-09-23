<div align="center">

## Web Methodology \(Layout Management\)


</div>

### Description

<p>

When you are develop some system in web, you must construct the skeleton of your front end, especially the layout.

</p>

<p>

This methodology will decrease of your developing times. such as you made a house, you must had a blue print & define the skeleton first. after that you improve it.

</p>

<p>

This management's using XML + XSLT Technology, DHTML, HTML & ASP. <b><a href="#down">Going in depth</a></b>

</p>
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Sunker](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sunker.md)
**Level**          |Advanced
**User Rating**    |4.3 (47 globes from 11 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML, VbScript \(browser/client side\)

**Category**       |[ASP Server Object Model](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/asp-server-object-model__4-32.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sunker-web-methodology-layout-management__4-6599/archive/master.zip)





### Source Code

<a name="down"></a>
<pre>
&lt;%
'This is virtual LDAP
Dim HomeDomain,sLocation
HomeDomain = Virt_Root
'set your static XML files
'Writer: Sunker
function SearchXML(Svocab)
 sLocation = HomeDomain & "Template/"
 select case (Svocab)
 case "left"
	 SearchXML = sLocation & "left.xml"
	case "coding"
	 SearchXML = sLocation & "coding.xml"
	case "manager"
	 SearchXML = sLocation & "manager.xml"
 end select
end function
'set your static XSL files
'Writer: Sunker
function SearchXSL(Svocab)
 sLocation = HomeDomain & "Layout/"
 select case (Svocab)
 	case "general"
	 SearchXSL = sLocation & "general.xsl"
 end select
end function
%&gt;
</pre>
<p>
More info, please click link here:
<br>
<b><a target="blank_" href="http://www16.brinkster.com/iforum/">Web Methodology</a></b>
</p>

