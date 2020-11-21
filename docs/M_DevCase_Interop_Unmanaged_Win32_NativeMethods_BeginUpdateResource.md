# NativeMethods.BeginUpdateResource Method 
 

Retrieves a handle that can be used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a> function to add, delete, or replace resources in a binary module.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr BeginUpdateResource(
	string fileName,
	bool deleteExistingResources
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function BeginUpdateResource ( 
	fileName As String,
	deleteExistingResources As Boolean
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim fileName As String
Dim deleteExistingResources As Boolean
Dim returnValue As IntPtr

returnValue = NativeMethods.BeginUpdateResource(fileName, 
	deleteExistingResources)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr BeginUpdateResource(
	[InAttribute] String^ fileName, 
	bool deleteExistingResources
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member BeginUpdateResource : 
        fileName : string * 
        deleteExistingResources : bool -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The binary file in which to update resources. 

 An application must be able to obtain write-access to this file; the file referenced by pFileName cannot be currently executing. 

 If *fileName* does not specify a full path, the system searches for the file in the current directory.</dd><dt>deleteExistingResources</dt><dd>Type: System.Boolean<br />Indicates whether to delete the *fileName* parameter's existing resources. 

 If this parameter is `true` (`True` in Visual Basic), existing resources are deleted and the updated file includes only resources added with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a> function. 

 If this parameter is `false` (`False` in Visual Basic), the updated file includes existing resources unless they are explicitly deleted or replaced by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a> function.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle that can be used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EndUpdateResource">EndUpdateResource(SafeModuleHandle, Boolean)</a> functions. 

 The return value is Zero if the specified file is not a PE (Portable-Executable), the file does not exist, or the file cannot be opened for writing. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648030(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648030(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />