# NativeUtil.WindowsGuidToManagedGuid Method 
 

Translates a GUID that is defined in a Windows C++ header file using the `DEFINE_GUID` macro, to a managed Guid.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Guid WindowsGuidToManagedGuid(
	string clikeGuid
)
```

**VB**<br />
``` VB
Public Shared Function WindowsGuidToManagedGuid ( 
	clikeGuid As String
) As Guid
```

**VB Usage**<br />
``` VB Usage
Dim clikeGuid As String
Dim returnValue As Guid

returnValue = NativeUtil.WindowsGuidToManagedGuid(clikeGuid)
```

**C++**<br />
``` C++
public:
static Guid WindowsGuidToManagedGuid(
	String^ clikeGuid
)
```

**F#**<br />
``` F#
static member WindowsGuidToManagedGuid : 
        clikeGuid : string -> Guid 

```


#### Parameters
&nbsp;<dl><dt>clikeGuid</dt><dd>Type: System.String<br />A string containing the values of the GUID array format, like for example: 

 "`0x450D8FBA,0xAD25,0x11D0,0x98,0xA8,0x08,0x00,0x36,0x1B,0x11,0x03`"</dd></dl>

#### Return Value
Type: Guid<br />The resulting Guid.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>clikeGuid;Wrong GUID format supplied.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim IID_IShellFolder As String = "0x000214E6L,0,0,0xC0,0,0,0,0,0,0,0x46" ' 000214E6-0000-0000-C000-000000000046
Dim guid As Guid = WindowsGuidToManagedGuid(IID_IShellFolder)
Console.WriteLine(guid.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />