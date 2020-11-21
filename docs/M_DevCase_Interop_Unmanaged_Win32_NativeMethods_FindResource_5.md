# NativeMethods.FindResource Method (IntPtr, IntPtr, String)
 

Determines the location of a resource with the specified type and name in the specified module. 

 To specify a language of the resource, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResourceEx">FindResourceEx(SafeModuleHandle, ResourceType, IntPtr, UInt16)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr FindResource(
	IntPtr hModule,
	IntPtr resourceId,
	string resourceType
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function FindResource ( 
	hModule As IntPtr,
	resourceId As IntPtr,
	resourceType As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim resourceId As IntPtr
Dim resourceType As String
Dim returnValue As IntPtr

returnValue = NativeMethods.FindResource(hModule, 
	resourceId, resourceType)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr FindResource(
	IntPtr hModule, 
	[InAttribute] IntPtr resourceId, 
	[InAttribute] String^ resourceType
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member FindResource : 
        hModule : IntPtr * 
        resourceId : IntPtr * 
        resourceType : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the module whose portable executable file or an accompanying MUI file contains the resource. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function searches the module used to create the current process.</dd><dt>resourceId</dt><dd>Type: System.IntPtr<br />The integer identifier of the resource.</dd><dt>resourceType</dt><dd>Type: System.String<br />The resource type.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the specified resource's information block. To obtain a handle to the resource, pass this handle to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadResource">LoadResource(SafeModuleHandle, IntPtr)</a> function. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648042(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648042(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResource">FindResource Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />