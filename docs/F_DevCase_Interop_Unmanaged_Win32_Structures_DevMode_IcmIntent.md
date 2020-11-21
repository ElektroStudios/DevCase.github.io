# DevMode.IcmIntent Field
 

Specifies which color matching method, or intent, should be used by default. 

 This member is primarily for non-ICM applications. 

 ICM applications can establish intents by using the ICM functions. 

 This member can be one of the following predefined values, or a driver defined value greater than or equal to the value of `DMICM_USER`.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int IcmIntent
```

**VB**<br />
``` VB
Public IcmIntent As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As Integer

value = instance.IcmIntent

instance.IcmIntent = value
```

**C++**<br />
``` C++
public:
int IcmIntent
```

**F#**<br />
``` F#
val mutable IcmIntent: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />