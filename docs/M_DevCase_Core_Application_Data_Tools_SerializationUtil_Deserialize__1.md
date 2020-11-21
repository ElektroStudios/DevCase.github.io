# SerializationUtil.Deserialize(*T*) Method (FileInfo, SerializationFormat)
 

Deserializes the data of an Object from the specified file, using the specified serialization format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T Deserialize<T>(
	FileInfo file,
	SerializationFormat format
)

```

**VB**<br />
``` VB
Public Shared Function Deserialize(Of T) ( 
	file As FileInfo,
	format As SerializationFormat
) As T
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim format As SerializationFormat
Dim returnValue As T

returnValue = SerializationUtil.Deserialize(file, 
	format)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T Deserialize(
	FileInfo^ file, 
	SerializationFormat format
)
```

**F#**<br />
``` F#
static member Deserialize : 
        file : FileInfo * 
        format : SerializationFormat -> 'T 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />\[Missing <param name="file"/> documentation for "M:DevCase.Core.Application.Data.Tools.SerializationUtil.Deserialize``1(System.IO.FileInfo,DevCase.Core.Application.Data.SerializationFormat)"\]</dd><dt>format</dt><dd>Type: <a href="T_DevCase_Core_Application_Data_SerializationFormat">DevCase.Core.Application.Data.SerializationFormat</a><br />The serialization format.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />The resulting object.

## Examples
This is a code example for Binary deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.bin", SerializationFormat.Binary)

obj = Deserialize(Of String())(New FileInfo("C:\File.bin"), SerializationFormat.Binary)
```


## Examples
This is a code example for Json deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.json", SerializationFormat.Json)

obj = Deserialize(Of String())(New FileInfo("C:\File.json"), SerializationFormat.Json)
```


## Examples
This is a code example for Xml deserialization. 
**VB**<br />
``` VB
Dim obj As String() = {"Hello World!"}
Serialize(obj, "C:\File.xml", SerializationFormat.Xml)

obj = Deserialize(Of String())(New FileInfo("C:\File.xml"), SerializationFormat.Xml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_SerializationUtil">SerializationUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_SerializationUtil_Deserialize">Deserialize Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />