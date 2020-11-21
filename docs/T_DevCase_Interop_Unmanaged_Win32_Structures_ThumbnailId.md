# ThumbnailId Structure
 

Contains a unique identifier for a thumbnail in the system thumbnail cache.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[StructLayoutAttribute(LayoutKind.Sequential, Size = 16, CharSet = CharSet.Ansi)]
public struct ThumbnailId
```

**VB**<br />
``` VB
<SerializableAttribute>
<StructLayoutAttribute(LayoutKind.Sequential, Size := 16, CharSet := CharSet.Ansi)>
Public Structure ThumbnailId
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThumbnailId
```

**C++**<br />
``` C++
[SerializableAttribute]
[StructLayoutAttribute(LayoutKind::Sequential, Size = 16, CharSet = CharSet::Ansi)]
public value class ThumbnailId
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<StructLayoutAttribute(LayoutKind.Sequential, Size = 16, CharSet = CharSet.Ansi)>]
type ThumbnailId =  struct end
```

The ThumbnailId type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ThumbnailId_RgbKey">RgbKey</a></td><td>
An array of 16 bytes that make up a unique identifier for a thumbnail in the system thumbnail cache.</td></tr></table>&nbsp;
<a href="#thumbnailid-structure">Back to Top</a>

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
<a href="#thumbnailid-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/ns-thumbcache-wts_thumbnailid" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/ns-thumbcache-wts_thumbnailid</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />