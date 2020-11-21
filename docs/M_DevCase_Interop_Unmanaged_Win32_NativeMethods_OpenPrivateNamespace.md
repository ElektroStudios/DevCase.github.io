# NativeMethods.OpenPrivateNamespace Method 
 

Opens a private namespace.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr OpenPrivateNamespace(
	IntPtr boundaryDescriptor,
	string aliasPrefix
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function OpenPrivateNamespace ( 
	boundaryDescriptor As IntPtr,
	aliasPrefix As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim boundaryDescriptor As IntPtr
Dim aliasPrefix As String
Dim returnValue As IntPtr

returnValue = NativeMethods.OpenPrivateNamespace(boundaryDescriptor, 
	aliasPrefix)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr OpenPrivateNamespace(
	[InAttribute] IntPtr boundaryDescriptor, 
	[InAttribute] String^ aliasPrefix
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member OpenPrivateNamespace : 
        boundaryDescriptor : IntPtr * 
        aliasPrefix : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>boundaryDescriptor</dt><dd>Type: System.IntPtr<br />A descriptor that defines how the namespace is to be isolated. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateBoundaryDescriptor">CreateBoundaryDescriptor(String, UInt32)</a> function creates a boundary descriptor..</dd><dt>aliasPrefix</dt><dd>Type: System.String<br />The prefix for the namespace. To create an object in this namespace, specify the object name as prefix<i>objectname.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the existing namespace>. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-openprivatenamespacea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-openprivatenamespacea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />