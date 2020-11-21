# SerializationUtil.Serialize(*T*) Method (*T*, String, SerializationFormat)
 

Serializes the data of an Object to the specified file, using the specified serialization format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Serialize<T>(
	T obj,
	string filepath,
	SerializationFormat format
)

```

**VB**<br />
``` VB
Public Shared Sub Serialize(Of T) ( 
	obj As T,
	filepath As String,
	format As SerializationFormat
)
```

**VB Usage**<br />
``` VB Usage
Dim obj As T
Dim filepath As String
Dim format As SerializationFormatSerializationUtil.Serialize(obj, filepath, format)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void Serialize(
	T obj, 
	String^ filepath, 
	SerializationFormat format
)
```

**F#**<br />
``` F#
static member Serialize : 
        obj : 'T * 
        filepath : string * 
        format : SerializationFormat -> unit 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: *T*<br />The object to be serialized.</dd><dt>filepath</dt><dd>Type: System.String<br />The filepath where to save the serialized data.</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## Examples
This is a code example for Binary serialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.bin", SerializationFormat.Binary)
```


## Examples
This is a code example for Json serialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.json", SerializationFormat.Json)
```


## Examples
This is a code example for Xml serialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.xml", SerializationFormat.Xml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_SerializationUtil_Serialize">Serialize Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />