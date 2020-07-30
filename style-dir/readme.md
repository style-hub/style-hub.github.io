## Submitting your style ##

When submitting your style you need two files.

1. The style xml-file with all the styles you want to commit as a package.
2. A 800x600 PNG image that showcase the style(-s). Only one image for each style.

it is also needed to add a 

```
<tr>
	<td><img src="style-dir/bildnamn.png"></td>
	<td>
	<table id="item"><tr>
	<td>Stilnamn<br><div id="name">Made by: Name Namesson</div></td>
	<td>Style description and information usefull for the use of the style/styles.</td>
	<td><a href="style-dir/stylefile.xml">Download</a></td>
	</tr></table>
	</td> 
</tr>
```

All files must have identical basename and the extensions -xml and -png.

All files committed must be releasable as public domain CC-0

### JSON ###

__The code below should be copied to an empty text document and edited with your information.__

```
{
	"styleName": "Name of your style package",
	"creator": "Your Name",
	"keywords": ["list", "with", "keywords"],
	"styleDescription": "Here you put a short description of the style and if there's any specifics on how to apply it."
}
```
