# NativeMethods.UpdateResource Method (IntPtr, ResourceType, String, UInt16, IntPtr, UInt32)
 

Adds, deletes, or replaces a resource in a portable executable (PE) file. 

 There are some restrictions on resource updates in files that contain Resource Configuration (RC Config) data: language-neutral (LN) files and language-specific resource (.mui) files.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool UpdateResource(
	IntPtr hUpdate,
	ResourceType resourceType,
	string resourceName,
	ushort languageId,
	IntPtr data,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function UpdateResource ( 
	hUpdate As IntPtr,
	resourceType As ResourceType,
	resourceName As String,
	languageId As UShort,
	data As IntPtr,
	size As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hUpdate As IntPtr
Dim resourceType As ResourceType
Dim resourceName As String
Dim languageId As UShort
Dim data As IntPtr
Dim size As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.UpdateResource(hUpdate, 
	resourceType, resourceName, languageId, 
	data, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool UpdateResource(
	IntPtr hUpdate, 
	[InAttribute] ResourceType resourceType, 
	[InAttribute] String^ resourceName, 
	unsigned short languageId, 
	IntPtr data, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member UpdateResource : 
        hUpdate : IntPtr * 
        resourceType : ResourceType * 
        resourceName : string * 
        languageId : uint16 * 
        data : IntPtr * 
        size : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hUpdate</dt><dd>Type: System.IntPtr<br />A module handle returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginUpdateResource">BeginUpdateResource(String, Boolean)</a> function, referencing the file to be updated.</dd><dt>resourceType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ResourceType">DevCase.Interop.Unmanaged.Win32.Enums.ResourceType</a><br />The resource type to be updated.</dd><dt>resourceName</dt><dd>Type: System.String<br />The name of the resource to be updated.</dd><dt>languageId</dt><dd>Type: System.UInt16<br />The language identifier of the resource to be updated.</dd><dt>data</dt><dd>Type: System.IntPtr<br />The resource data to be inserted into the file indicated by *hUpdate* parameter. 

 If the resource is one of the predefined types, the data must be valid and properly aligned. 

 Note that this is the raw binary data to be stored in the file indicated by *hUpdate* parameter, not the data provided by LoadIcon, LoadString, or other resource-specific load functions. 

 All data containing strings or text must be in Unicode format. *data* parameter must not point to ANSI data. 

 If *data* parameter is Zero and *size* parameter is 0, the specified resource is deleted from the file indicated by *hUpdate* parameter.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size, in bytes, of the resource data at *data* parameter.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the function succeeds; `false` (`False` in Visual Basic) otherwise. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648049(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648049(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />