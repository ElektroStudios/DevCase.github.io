# SnesRom.Name Property 
 

Gets or sets the name of the ROM, typically in ASCII. 

 The name buffer consists in 21 characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Name { get; set; }
```

**VB**<br />
``` VB
Public Property Name As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
Dim value As String

value = instance.Name

instance.Name = value
```

**C++**<br />
``` C++
public:
property String^ Name {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Name : string with get, set

```


#### Property Value
Type: String<br />The name of the ROM.

## Remarks
<a href="http://romhack.wikia.com/wiki/SNES_header" target="_blank">http://romhack.wikia.com/wiki/SNES_header</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Gaming_SnesRom">SnesRom Class</a><br /><a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />