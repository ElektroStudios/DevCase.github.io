# IPersistFile Interface
 

Enables an object to be loaded from or saved to a disk file, rather than a storage object or stream. 

 Because the information needed to open a file varies greatly from one application to another, the implementation of <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Load">Load(String, UInt32)</a> on the object must also open its disk file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("0000010b-0000-0000-C000-000000000046")]
public interface IPersistFile : IPersist
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("0000010b-0000-0000-C000-000000000046")>
Public Interface IPersistFile
	Inherits IPersist
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersistFile
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"0000010b-0000-0000-C000-000000000046")]
public interface class IPersistFile : IPersist
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("0000010b-0000-0000-C000-000000000046")>]
type IPersistFile =  
    interface
        interface IPersist
    end
```

The IPersistFile type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_GetClassID">GetClassID</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_GetCurFile">GetCurFile</a></td><td>
Retrieves the current name of the file associated with the object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_IsDirty">IsDirty</a></td><td>
Determines whether an object has changed since it was last saved to its current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Load">Load</a></td><td>
Opens the specified file and initializes an object from the file contents.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Save">Save</a></td><td>
Saves a copy of the object to the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_SaveCompleted">SaveCompleted</a></td><td>
Notifies the object that it can write to its file. 

 It does this by notifying the object that it can revert from `NoScribble` mode (in which it must not write to its file), to `Normal` mode (in which it can). 

 The component enters `NoScribble` mode when it receives an <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Save">Save(String, Boolean)</a> call.</td></tr></table>&nbsp;
<a href="#ipersistfile-interface">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms687223%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms687223%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />