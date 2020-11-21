# MemoryStreamExtensions Class
 

Contains custom extension methods to use with the MemoryStream type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.MemoryStream.MemoryStreamExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class MemoryStreamExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class MemoryStreamExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As MemoryStreamExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class MemoryStreamExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type MemoryStreamExtensions =  class end
```

The MemoryStreamExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadToEnd">ReadToEnd(MemoryStream)</a></td><td>
Reads all characters from the current position to the end of the MemoryStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadToEnd_1">ReadToEnd(MemoryStream, Int64)</a></td><td>
Reads all characters from the current position to the end of the MemoryStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadToEnd_2">ReadToEnd(MemoryStream, Encoding)</a></td><td>
Reads all characters from the current position to the end of the MemoryStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadToEnd_3">ReadToEnd(MemoryStream, Encoding, Int64)</a></td><td>
Reads all characters from the specified position to the end of the MemoryStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte">ReadUntilFirstNullByte(MemoryStream)</a></td><td>
Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte_1">ReadUntilFirstNullByte(MemoryStream, Int64)</a></td><td>
Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte_5">ReadUntilFirstNullByte(MemoryStream, Encoding)</a></td><td>
Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found; and then converts the bytes read to a string representation using the specified text encoding.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte_2">ReadUntilFirstNullByte(MemoryStream, Int64, Int64)</a></td><td>
Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte_4">ReadUntilFirstNullByte(MemoryStream, Int64, Encoding)</a></td><td>
Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found; and then converts the bytes read to a string representation using the specified text encoding.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ReadUntilFirstNullByte_3">ReadUntilFirstNullByte(MemoryStream, Int64, Int64, Encoding)</a></td><td>
Reads the bytes of the specified MemoryStream until the first null (zero) byte is found, or until the end, in case of a null byte is not found; and then converts the bytes read to a string representation using the specified text encoding.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_SeekToBegin">SeekToBegin</a></td><td>
Sets the position to the beginning of the source stream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_SeekToEnd">SeekToEnd</a></td><td>
Sets the position to the end of the source stream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_MemoryStream_MemoryStreamExtensions_ToStream">ToStream</a></td><td>
Converts a MemoryStream to a Stream.</td></tr></table>&nbsp;
<a href="#memorystreamextensions-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#memorystreamextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_MemoryStream">DevCase.Core.Extensions.MemoryStream Namespace</a><br />