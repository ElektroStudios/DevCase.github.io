# NativeMethods.SymEnumSymbols Method 
 

Enumerates all symbols in a process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DbgHelp.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SymEnumSymbols(
	IntPtr hProcess,
	ulong baseOfDll,
	string mask,
	Delegates.SymEnumSymbolsProc enumSymbolsCallback,
	IntPtr userContext
)
```

**VB**<br />
``` VB
<DllImportAttribute("DbgHelp.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SymEnumSymbols ( 
	hProcess As IntPtr,
	baseOfDll As ULong,
	mask As String,
	enumSymbolsCallback As Delegates.SymEnumSymbolsProc,
	userContext As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim baseOfDll As ULong
Dim mask As String
Dim enumSymbolsCallback As Delegates.SymEnumSymbolsProc
Dim userContext As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SymEnumSymbols(hProcess, 
	baseOfDll, mask, enumSymbolsCallback, 
	userContext)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DbgHelp.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SymEnumSymbols(
	IntPtr hProcess, 
	unsigned long long baseOfDll, 
	String^ mask, 
	Delegates.SymEnumSymbolsProc^ enumSymbolsCallback, 
	IntPtr userContext
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DbgHelp.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SymEnumSymbols : 
        hProcess : IntPtr * 
        baseOfDll : uint64 * 
        mask : string * 
        enumSymbolsCallback : Delegates.SymEnumSymbolsProc * 
        userContext : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to a process. 

 This handle must have been previously passed to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymInitialize">SymInitialize(IntPtr, String, Boolean)</a> function.</dd><dt>baseOfDll</dt><dd>Type: System.UInt64<br />The base address of the module. 

 If this value is zero and *mask* parameter contains an exclamation point (`!`), the function looks across modules. 

 If this value is zero and *mask* parameter does not contain an exclamation point, the function uses the scope established by the `SymSetContext` function.</dd><dt>mask</dt><dd>Type: System.String<br />A wildcard string that indicates the names of the symbols to be enumerated. 

 The text can optionally contain the wildcards, "`*`" and "`?`".</dd><dt>enumSymbolsCallback</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_SymEnumSymbolsProc">DevCase.Interop.Unmanaged.Win32.Delegates.SymEnumSymbolsProc</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_SymEnumSymbolsProc">Delegates.SymEnumSymbolsProc</a> callback function that receives the symbol information.</dd><dt>userContext</dt><dd>Type: System.IntPtr<br />A user-defined value that is passed to the callback function, or Zero. 

 This parameter is typically used by an application to pass a pointer to a data structure that provides context for the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680718%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680718%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />