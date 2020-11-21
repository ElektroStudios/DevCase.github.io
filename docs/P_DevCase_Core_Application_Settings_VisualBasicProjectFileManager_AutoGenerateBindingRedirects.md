# VisualBasicProjectFileManager.AutoGenerateBindingRedirects Property 
 

Gets or sets a value that indicates whether binding redirects may be automatically added to the app configuration file to override assembly unification.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool AutoGenerateBindingRedirects { get; set; }
```

**VB**<br />
``` VB
Public Property AutoGenerateBindingRedirects As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As Boolean

value = instance.AutoGenerateBindingRedirects

instance.AutoGenerateBindingRedirects = value
```

**C++**<br />
``` C++
public:
property bool AutoGenerateBindingRedirects {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member AutoGenerateBindingRedirects : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) to enable binding redirects, otherwise, `false` (`False` in Visual Basic).

## Remarks
Starting with Visual Studio 2013, when you compile apps that target the .NET Framework 4.5.1, binding redirects may be automatically added to the app configuration file to override assembly unification. 

 Binding redirects are added if your app or its components reference more than one version of the same assembly, even if you manually specify binding redirects in the configuration file for your app. 

 The automatic binding redirection feature affects traditional desktop apps and web apps that target the .NET Framework 4.5.1, although the behavior is slightly different for a web app. 

 You can enable automatic binding redirection if you have existing apps that target previous versions of the .NET Framework, or you can disable this feature if you want to keep manually authored binding redirects.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
vbproj.AutoGenerateBindingRedirects = True
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />