# NativeMethods.FindResourceEx Method (SafeModuleHandle, String, String, UInt16)
 

Determines the location of the resource with the specified type, name, and language in the specified module.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr FindResourceEx(
	SafeModuleHandle hModule,
	string resourceType,
	string resourceName,
	ushort languageId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function FindResourceEx ( 
	hModule As SafeModuleHandle,
	resourceType As String,
	resourceName As String,
	languageId As UShort
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hModule As SafeModuleHandle
Dim resourceType As String
Dim resourceName As String
Dim languageId As UShort
Dim returnValue As IntPtr

returnValue = NativeMethods.FindResourceEx(hModule, 
	resourceType, resourceName, languageId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr FindResourceEx(
	SafeModuleHandle^ hModule, 
	[InAttribute] String^ resourceType, 
	[InAttribute] String^ resourceName, 
	unsigned short languageId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member FindResourceEx : 
        hModule : SafeModuleHandle * 
        resourceType : string * 
        resourceName : string * 
        languageId : uint16 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeModuleHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeModuleHandle</a><br />A handle to the module whose portable executable file or an accompanying MUI file contains the resource. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function searches the module used to create the current process.</dd><dt>resourceType</dt><dd>Type: System.String<br />The resource type.</dd><dt>resourceName</dt><dd>Type: System.String<br />The name of the resource.</dd><dt>languageId</dt><dd>Type: System.UInt16<br />The language identifier of the resource.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the specified resource's information block. To obtain a handle to the resource, pass this handle to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadResource">LoadResource(SafeModuleHandle, IntPtr)</a> function. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648043(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648043(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FindResourceEx">FindResourceEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />