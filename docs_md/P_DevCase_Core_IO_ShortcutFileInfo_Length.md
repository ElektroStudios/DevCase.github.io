# ShortcutFileInfo.Length Property 
 

Gets the file size, in bytes, of the current shortcut file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[TypeConverterAttribute(typeof(FileSizeConverter))]
public long Length { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<TypeConverterAttribute(GetType(FileSizeConverter))>
Public ReadOnly Property Length As Long
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim value As Long

value = instance.Length

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[TypeConverterAttribute(typeof(FileSizeConverter))]
property long long Length {
	long long get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<TypeConverterAttribute(typeof(FileSizeConverter))>]
member Length : int64 with get

```


#### Property Value
Type: Int64<br />The file attributes.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />