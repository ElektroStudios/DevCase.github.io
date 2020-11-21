# KeyboardLayoutFlags Enumeration
 

Specifies how the input locale identifier is to be loaded when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadKeyboardLayout">LoadKeyboardLayout(String, KeyboardLayoutFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum KeyboardLayoutFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration KeyboardLayoutFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardLayoutFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class KeyboardLayoutFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type KeyboardLayoutFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.Activate">**Activate**</td><td>1</td><td>If the specified input locale identifier is not already loaded, the function loads and activates the input locale identifier for the system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.NoTellShell">**NoTellShell**</td><td>128</td><td>In this scenario, the last input locale identifier is set for the entire system.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.Reorder">**Reorder**</td><td>8</td><td>Moves the specified input locale identifier to the head of the input locale identifier list, making that locale identifier the active locale identifier for the system. 

 This value reorders the input locale identifier list even if Activate is not provided.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.ReplaceLang">**ReplaceLang**</td><td>16</td><td>If the new input locale identifier has the same language identifier as a current input locale identifier, the new input locale identifier replaces the current one as the input locale identifier for that language. 

 If this value is not provided and the input locale identifiers have the same language identifiers, the current input locale identifier is not replaced and the function returns NULL.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.SubstituteOk">**SubstituteOk**</td><td>2</td><td>Substitutes the specified input locale identifier with another locale preferred by the user. 

 The system starts with this flag set, and it is recommended that your application always use this flag. 

 The substitution occurs only if the registry key HKEY_CURRENT_USER\Keyboard\Layout\Substitutes explicitly defines a substitution locale. 

 For example, if the key includes the value name "00000409" with value "00010409", loading the U.S. English layout ("00000409") causes the Dvorak U.S. English layout ("00010409") to be loaded instead. 

 The system uses KLF_SUBSTITUTE_OK when booting, and it is recommended that all applications use this value when loading input locale identifiers to ensure that the user's preference is selected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.SetForProcess">**SetForProcess**</td><td>256</td><td>This flag is not used. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadKeyboardLayout">LoadKeyboardLayout(String, KeyboardLayoutFlags)</a> always activates an input locale identifier for the entire system if the current process owns the window with keyboard focus.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.ShiftLock">**ShiftLock**</td><td>65536</td><td>This is used with Reset. See Reset for an explanation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags.Reset">**Reset**</td><td>1073741824</td><td>If this flag is set but ShiftLock is not set, the Caps Lock state is turned off by pressing the Caps Lock key again. 

 If this flag is set and ShiftLock is also set, the Caps Lock state is turned off by pressing either SHIFT key. 

 These two methods are mutually exclusive, and the setting persists as part of the User's profile in the registry.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-loadkeyboardlayouta" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-loadkeyboardlayouta</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />