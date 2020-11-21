# IPersist Interface
 

Provides the CLSID of an object that can be stored persistently in the system. 

 Allows the object to specify which object handler to use in the client process, as it is used in the default implementation of marshaling.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("0000010c-0000-0000-c000-000000000046")]
public interface IPersist
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("0000010c-0000-0000-c000-000000000046")>
Public Interface IPersist
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersist
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"0000010c-0000-0000-c000-000000000046")]
public interface class IPersist
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("0000010c-0000-0000-c000-000000000046")>]
type IPersist =  interface end
```

The IPersist type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersist_GetClassID">GetClassID</a></td><td>
Retrieves the class identifier (CLSID) of the object.</td></tr></table>&nbsp;
<a href="#ipersist-interface">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms688695%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms688695%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />