# ObjectAttributes Structure
 

Define an object name and other attributes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ObjectAttributes : IDisposable
```

**VB**<br />
``` VB
Public Structure ObjectAttributes
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ObjectAttributes
```

**C++**<br />
``` C++
public value class ObjectAttributes : IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ObjectAttributes =  
    struct
        interface IDisposable
    end
```

The ObjectAttributes type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes__ctor">ObjectAttributes</a></td><td>
Initializes a new instance of the ObjectAttributes struct.</td></tr></table>&nbsp;
<a href="#objectattributes-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a></td><td>
Gets or sets a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UnicodeString">UnicodeString</a> that contains the name of the object for which a handle is to be opened. 

 This must either be a fully qualified object name, or a relative path name to the directory specified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> member.</td></tr></table>&nbsp;
<a href="#objectattributes-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_Dispose">Dispose</a></td><td>
Frees any unmanaged resources used by this instance.</td></tr></table>&nbsp;
<a href="#objectattributes-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_Attributes">Attributes</a></td><td>
Flags that specifies object handle attributes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a></td><td>
Optional handle to the root object directory for the path name specified by the ObjectName member. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> is Zero, <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> must point to a fully qualified object name that includes the full path to the target object. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> is not Zero, <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> specifies an object name relative to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> directory. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> handle can refer to a file system directory or an object directory in the object manager namespace.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_SecurityDescriptor">SecurityDescriptor</a></td><td>
Specifies a security descriptor for the object when the object is created. 

 If this member is Zero, the object will receive default security settings.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_SecurityQualityOfService">SecurityQualityOfService</a></td><td>
Optional quality of service to be applied to the object when it is created. Used to indicate the security impersonation level and context tracking mode (dynamic or static). 

 Currently, the InitializeObjectAttributes macro sets this member to Zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of ObjectAttributes)` before calling any function. 

 The InitializeObjectAttributes macro sets this member to `Marshal.SizeOf(Of ObjectAttributes)`.</td></tr></table>&nbsp;
<a href="#objectattributes-structure">Back to Top</a>

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
<a href="#objectattributes-structure">Back to Top</a>

## Remarks
<a href="https://technet.microsoft.com/es-es/ff557749(v=vs.71)" target="_blank">https://technet.microsoft.com/es-es/ff557749(v=vs.71)</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />