# UserProfileInfo.ProfilePath Field
 

A pointer to the roaming user profile path. 

 If the user does not have a roaming profile, this member can be a null reference (`Nothing` in Visual Basic). 

 To retrieve the user's roaming profile path, call the `NetUserGetInfo` function, specifying information level `3` or `4`.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ProfilePath
```

**VB**<br />
``` VB
Public ProfilePath As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As UserProfileInfo
Dim value As String

value = instance.ProfilePath

instance.ProfilePath = value
```

**C++**<br />
``` C++
public:
String^ ProfilePath
```

**F#**<br />
``` F#
val mutable ProfilePath: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo">UserProfileInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />