# Delegates.SymEnumSymbolsProc Delegate
 

An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymEnumSymbols">SymEnumSymbols(IntPtr, UInt64, String, Delegates.SymEnumSymbolsProc, IntPtr)</a>, `SymEnumTypes`, and `SymEnumTypesByName` functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool SymEnumSymbolsProc(
	IntPtr symInfo,
	uint symbolSize,
	IntPtr userContext
)
```

**VB**<br />
``` VB
Public Delegate Function SymEnumSymbolsProc ( 
	symInfo As IntPtr,
	symbolSize As UInteger,
	userContext As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New SymEnumSymbolsProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool SymEnumSymbolsProc(
	IntPtr symInfo, 
	unsigned int symbolSize, 
	IntPtr userContext
)
```

**F#**<br />
``` F#
type SymEnumSymbolsProc = 
    delegate of 
        symInfo : IntPtr * 
        symbolSize : uint32 * 
        userContext : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>symInfo</dt><dd>Type: System.IntPtr<br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo">SymbolInfo</a> structure that provides information about the symbol.</dd><dt>symbolSize</dt><dd>Type: System.UInt32<br />The size of the symbol, in bytes. 

 The size is calculated and is actually a guess. 

 In some cases, this value can be zero.</dd><dt>userContext</dt><dd>Type: System.IntPtr<br />The user-defined value passed from the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymEnumSymbols">SymEnumSymbols(IntPtr, UInt64, String, Delegates.SymEnumSymbolsProc, IntPtr)</a> or `SymEnumTypes` function, or Zero. 

 This parameter is typically used by an application to pass a pointer to a data structure that provides context information for the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />To continue enumeration, the callback function must return `true` (`True` in Visual Basic); to stop enumeration, it must return `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680720%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680720%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />