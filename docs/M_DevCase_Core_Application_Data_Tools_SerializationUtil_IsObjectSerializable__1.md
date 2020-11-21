# SerializationUtil.IsObjectSerializable(*T*) Method 
 

Determines whether the specified object can be serialized.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsObjectSerializable<T>(
	T obj,
	SerializationFormat format
)

```

**VB**<br />
``` VB
Public Shared Function IsObjectSerializable(Of T) ( 
	obj As T,
	format As SerializationFormat
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim obj As T
Dim format As SerializationFormat
Dim returnValue As Boolean

returnValue = SerializationUtil.IsObjectSerializable(obj, 
	format)
```

**C++**<br />
``` C++
public:
generic<typename T>
static bool IsObjectSerializable(
	T obj, 
	SerializationFormat format
)
```

**F#**<br />
``` F#
static member IsObjectSerializable : 
        obj : 'T * 
        format : SerializationFormat -> bool 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: *T*<br />The object to check.</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified object can be serialized; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim bmp As New Bitmap(256, 256)
Dim result As Boolean = IsObjectSerializable(bmp, SerializationFormat.Binary)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />