# ChromeUtil.GetGoogleChromeLogins Method (FileInfo, String, String, String)
 

Gets the Google Chrome logins stored for the current user.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Chrome">DevCase.ThirdParty.Google.Chrome</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<NetworkCredential> GetGoogleChromeLogins(
	FileInfo loginDataFile,
	string defaultIfUsernameEmpty = "",
	string defaultIfPasswordEmpty = "",
	string defaultIfPasswordUndecryptable = ""
)
```

**VB**<br />
``` VB
Public Shared Function GetGoogleChromeLogins ( 
	loginDataFile As FileInfo,
	Optional defaultIfUsernameEmpty As String = "",
	Optional defaultIfPasswordEmpty As String = "",
	Optional defaultIfPasswordUndecryptable As String = ""
) As IEnumerable(Of NetworkCredential)
```

**VB Usage**<br />
``` VB Usage
Dim loginDataFile As FileInfo
Dim defaultIfUsernameEmpty As String
Dim defaultIfPasswordEmpty As String
Dim defaultIfPasswordUndecryptable As String
Dim returnValue As IEnumerable(Of NetworkCredential)

returnValue = ChromeUtil.GetGoogleChromeLogins(loginDataFile, 
	defaultIfUsernameEmpty, defaultIfPasswordEmpty, 
	defaultIfPasswordUndecryptable)
```

**C++**<br />
``` C++
public:
static IEnumerable<NetworkCredential^>^ GetGoogleChromeLogins(
	FileInfo^ loginDataFile, 
	String^ defaultIfUsernameEmpty = L"", 
	String^ defaultIfPasswordEmpty = L"", 
	String^ defaultIfPasswordUndecryptable = L""
)
```

**F#**<br />
``` F#
static member GetGoogleChromeLogins : 
        loginDataFile : FileInfo * 
        ?defaultIfUsernameEmpty : string * 
        ?defaultIfPasswordEmpty : string * 
        ?defaultIfPasswordUndecryptable : string 
(* Defaults:
        let _defaultIfUsernameEmpty = defaultArg defaultIfUsernameEmpty ""
        let _defaultIfPasswordEmpty = defaultArg defaultIfPasswordEmpty ""
        let _defaultIfPasswordUndecryptable = defaultArg defaultIfPasswordUndecryptable ""
*)
-> IEnumerable<NetworkCredential> 

```


#### Parameters
&nbsp;<dl><dt>loginDataFile</dt><dd>Type: System.IO.FileInfo<br />The "Logins Data" file that stores the user logins. 

 This file is typically located at: 'C:\Users\{USERNAME}\AppData\Local\Google\Chrome\User Data\Default'.</dd><dt>defaultIfUsernameEmpty (Optional)</dt><dd>Type: System.String<br />A default value to assign for an empty username.</dd><dt>defaultIfPasswordEmpty (Optional)</dt><dd>Type: System.String<br />A default value to assign for an empty password.</dd><dt>defaultIfPasswordUndecryptable (Optional)</dt><dd>Type: System.String<br />A default value to assign for a undecryptable password.</dd></dl>

#### Return Value
Type: IEnumerable(NetworkCredential)<br />A IEnumerable(T) containing the user logins.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim loginsFile As New FileInfo("C:\Users\Administrator\AppData\Local\Google\Chrome\User Data\Default\Login Data")
Dim logins As IEnumerable(Of NetworkCredential) =
    From login As NetworkCredential In
        GetGoogleChromeLogins(loginsFile, "_NULL_", "_NULL_", "_UNDECRYPTABLE_")
    Order By login.Domain Ascending

For Each login As NetworkCredential In logins
    Console.WriteLine("{0}; {1}; {2}", login.Domain, login.UserName, login.Password)
Next login
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Chrome_ChromeUtil">ChromeUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Chrome_ChromeUtil_GetGoogleChromeLogins">GetGoogleChromeLogins Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Chrome">DevCase.ThirdParty.Google.Chrome Namespace</a><br />