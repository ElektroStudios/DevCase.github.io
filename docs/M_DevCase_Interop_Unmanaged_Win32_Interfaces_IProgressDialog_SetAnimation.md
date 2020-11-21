# IProgressDialog.SetAnimation Method 
 

Specifies an Audio-Video Interleaved (AVI) clip that runs in the dialog box. 

 Note: Note This method is not supported in Windows Vista or later versions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetAnimation(
	[OptionalAttribute] IntPtr hInstAnimation,
	ushort idAnimation
)
```

**VB**<br />
``` VB
Sub SetAnimation ( 
	<OptionalAttribute> hInstAnimation As IntPtr,
	idAnimation As UShort
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim hInstAnimation As IntPtr
Dim idAnimation As UShort

instance.SetAnimation(hInstAnimation, 
	idAnimation)
```

**C++**<br />
``` C++
void SetAnimation(
	[OptionalAttribute] IntPtr hInstAnimation, 
	unsigned short idAnimation
)
```

**F#**<br />
``` F#
abstract SetAnimation : 
        [<OptionalAttribute>] hInstAnimation : IntPtr * 
        idAnimation : uint16 -> unit 

```


#### Parameters
&nbsp;<dl><dt>hInstAnimation (Optional)</dt><dd>Type: System.IntPtr<br />An instance handle to the module from which the AVI resource should be loaded.</dd><dt>idAnimation</dt><dd>Type: System.UInt16<br />An AVI resource identifier. 

 To create this value, use the MAKEINTRESOURCE macro. 

 The control loads the AVI resource from the module specified by hInstAnimation.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />