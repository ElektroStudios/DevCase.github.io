# PrintDocumentBasic.Font Property 
 

Gets or sets the text font. 

 Default font is: [Font: Name=Arial, Size=10, Units=3, GdiCharSet=1, GdiVerticalFont=False]

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Font Font { get; set; }
```

**VB**<br />
``` VB
Public Property Font As Font
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PrintDocumentBasic
Dim value As Font

value = instance.Font

instance.Font = value
```

**C++**<br />
``` C++
public:
property Font^ Font {
	Font^ get ();
	void set (Font^ value);
}
```

**F#**<br />
``` F#
member Font : Font with get, set

```


#### Property Value
Type: Font<br />The text font.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_PrintDocumentBasic">PrintDocumentBasic Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />