# SerializationUtil.Deserialize(*T*) Method (String, SerializationFormat, Encoding)
 

Deserializes the data of an Object from the specified String representation, using the specified serialization format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T Deserialize<T>(
	string obj,
	SerializationFormat format,
	Encoding enc = null
)

```

**VB**<br />
``` VB
Public Shared Function Deserialize(Of T) ( 
	obj As String,
	format As SerializationFormat,
	Optional enc As Encoding = Nothing
) As T
```

**VB Usage**<br />
``` VB Usage
Dim obj As String
Dim format As SerializationFormat
Dim enc As Encoding
Dim returnValue As T

returnValue = SerializationUtil.Deserialize(obj, 
	format, enc)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T Deserialize(
	String^ obj, 
	SerializationFormat format, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Deserialize : 
        obj : string * 
        format : SerializationFormat * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> 'T 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.String<br />A String representation of a serialized Object.</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />\[Missing <param name="enc"/> documentation for "M:DevCase.Core.Application.Data.Tools.SerializationUtil.Deserialize``1(System.String,DevCase.Core.Application.Data.SerializationFormat,System.Text.Encoding)"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />The resulting deserialized Object.

## Examples
This is a code example for Binary deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello", "World!"}
Dim serialized As String = Serialize(obj, SerializationFormat.Binary)
Dim deserialized As String() = Deserialize(Of String())(serialized, SerializationFormat.Binary)
Console.WriteLine(String.Join(", ", deserialized))
```


## Examples
This is a code example for Json deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello", "World!"}
Dim serialized As String = Serialize(obj, SerializationFormat.Json)
Dim deserialized As String() = Deserialize(Of String())(serialized, SerializationFormat.Json)
Console.WriteLine(String.Join(", ", deserialized))
```


## Examples
This is a code example for Xml deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello", "World!"}
Dim serialized As String = Serialize(obj, SerializationFormat.Xml)
Dim deserialized As String() = Deserialize(Of String())(serialized, SerializationFormat.Xml)
Console.WriteLine(String.Join(", ", deserialized))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_SerializationUtil_Deserialize">Deserialize Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />