# NativeMethods.SetThreadUILanguage Method 
 

Sets the user interface language for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static uint SetThreadUILanguage(
	uint langId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetThreadUILanguage ( 
	langId As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim langId As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.SetThreadUILanguage(langId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned int SetThreadUILanguage(
	unsigned int langId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetThreadUILanguage : 
        langId : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>langId</dt><dd>Type: System.UInt32<br />Language identifier for the user interface language for the thread.</dd></dl>

#### Return Value
Type: UInt32<br />Returns the input language identifier if successful. 

 If the input identifier is nonzero, the function returns that value. 

 If the language identifier is 0, the function always succeeds and returns the identifier of the language that best supports the Windows console.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-setthreaduilanguage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-setthreaduilanguage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />