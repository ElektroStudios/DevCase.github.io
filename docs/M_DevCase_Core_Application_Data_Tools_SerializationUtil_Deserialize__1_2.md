# SerializationUtil.Deserialize(*T*) Method (*T*, String, SerializationFormat)
 

Deserializes the data of an Object from the specified file, using the specified serialization format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Deserialize<T>(
	ref T refObj,
	string filepath,
	SerializationFormat format
)

```

**VB**<br />
``` VB
Public Shared Sub Deserialize(Of T) ( 
	ByRef refObj As T,
	filepath As String,
	format As SerializationFormat
)
```

**VB Usage**<br />
``` VB Usage
Dim refObj As T
Dim filepath As String
Dim format As SerializationFormatSerializationUtil.Deserialize(refObj, filepath, 
	format)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void Deserialize(
	T% refObj, 
	String^ filepath, 
	SerializationFormat format
)
```

**F#**<br />
``` F#
static member Deserialize : 
        refObj : 'T byref * 
        filepath : string * 
        format : SerializationFormat -> unit 

```


#### Parameters
&nbsp;<dl><dt>refObj</dt><dd>Type: *T*<br />The by-reference object.</dd><dt>filepath</dt><dd>Type: System.String<br />The filepath where from deserialize the serialized data.</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## Examples
This is a code example for Binary deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.bin", SerializationFormat.Binary)
Deserialize(obj, "C:\File.bin", SerializationFormat.Binary)
```


## Examples
This is a code example for Json deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.json", SerializationFormat.Json)
Deserialize(obj, "C:\File.json", SerializationFormat.Json)
```


## Examples
This is a code example for Xml deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.xml", SerializationFormat.Xml)
Deserialize(obj, "C:\File.xml", SerializationFormat.Xml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_SerializationUtil_Deserialize">Deserialize Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />