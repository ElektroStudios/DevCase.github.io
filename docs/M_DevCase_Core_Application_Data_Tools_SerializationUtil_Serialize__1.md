# SerializationUtil.Serialize(*T*) Method (*T*, SerializationFormat, Encoding)
 

Serializes the data of an Object to a String representation using the specified serialization format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Serialize<T>(
	T obj,
	SerializationFormat format,
	Encoding enc = null
)

```

**VB**<br />
``` VB
Public Shared Function Serialize(Of T) ( 
	obj As T,
	format As SerializationFormat,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim obj As T
Dim format As SerializationFormat
Dim enc As Encoding
Dim returnValue As String

returnValue = SerializationUtil.Serialize(obj, 
	format, enc)
```

**C++**<br />
``` C++
public:
generic<typename T>
static String^ Serialize(
	T obj, 
	SerializationFormat format, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Serialize : 
        obj : 'T * 
        format : SerializationFormat * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: *T*<br />The object to be serialized.</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The Encoding to use for writing the.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: String<br />The resulting String representation of the serialized Object.

## Examples
This is a code example for Binary serialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Dim result As String = Serialize(obj, SerializationFormat.Binary)
Console.WriteLine(result)
```


## Examples
This is a code example for Json serialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Dim result As String = Serialize(obj, SerializationFormat.Json)
Console.WriteLine(result)
```


## Examples
This is a code example for Xml serialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Dim result As String = Serialize(obj, SerializationFormat.Xml)
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_SerializationUtil_Serialize">Serialize Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />