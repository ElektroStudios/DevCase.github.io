# NativeMethods.LoadString Method 
 

Loads a string resource from the executable file associated with a specified module, copies the string into a buffer, and appends a terminating null character.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static int LoadString(
	IntPtr hInstance,
	uint resourceId,
	StringBuilder buffer,
	int bufferMax
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function LoadString ( 
	hInstance As IntPtr,
	resourceId As UInteger,
	buffer As StringBuilder,
	bufferMax As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hInstance As IntPtr
Dim resourceId As UInteger
Dim buffer As StringBuilder
Dim bufferMax As Integer
Dim returnValue As Integer

returnValue = NativeMethods.LoadString(hInstance, 
	resourceId, buffer, bufferMax)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static int LoadString(
	IntPtr hInstance, 
	unsigned int resourceId, 
	StringBuilder^ buffer, 
	int bufferMax
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member LoadString : 
        hInstance : IntPtr * 
        resourceId : uint32 * 
        buffer : StringBuilder * 
        bufferMax : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hInstance</dt><dd>Type: System.IntPtr<br />A handle to an instance of the module whose executable file contains the string resource. 

 To get the handle to the application itself, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a> function with a null reference (`Nothing` in Visual Basic).</dd><dt>resourceId</dt><dd>Type: System.UInt32<br />The identifier of the string to be loaded.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />The buffer is to receive the string. 

 Must be of sufficient length to hold a pointer (8 bytes).</dd><dt>bufferMax</dt><dd>Type: System.Int32<br />The size of the buffer, in characters. 

 The string is truncated and null-terminated if it is longer than the number of characters specified. 

 If this parameter is 0, then lpBuffer receives a read-only pointer to the resource itself.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the number of characters copied into the buffer, not including the terminating null character, or zero if the string resource does not exist. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647486%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647486%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />