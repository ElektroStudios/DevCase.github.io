# EnumSystemLocalesFlags Enumeration
 

Flags specifying the locale identifiers to enumerate when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumSystemLocales">EnumSystemLocales(Delegates.EnumLocalesProc, EnumSystemLocalesFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum EnumSystemLocalesFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration EnumSystemLocalesFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As EnumSystemLocalesFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class EnumSystemLocalesFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type EnumSystemLocalesFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemLocalesFlags.Installed">**Installed**</td><td>1</td><td>Enumerate only installed locale identifiers. 

 This value cannot be used with Supported.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemLocalesFlags.Supported">**Supported**</td><td>2</td><td>Enumerate all supported locale identifiers. 

 This value cannot be used with Installed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemLocalesFlags.AlternateSorts">**AlternateSorts**</td><td>4</td><td>Enumerate only the alternate sort locale identifiers. 

 If this value is used with either Installed or Supported, the installed or supported locales are retrieved, as well as the alternate sort locale identifiers.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemlocalesa" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumsystemlocalesa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />