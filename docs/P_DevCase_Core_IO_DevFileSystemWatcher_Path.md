# DevFileSystemWatcher.Path Property 
 

Gets or sets the path of the directory to watch.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[IODescriptionAttribute("FSW_Path")]
[DefaultValueAttribute("")]
[SettingsBindableAttribute(true)]
[TypeConverterAttribute("System.Diagnostics.Design.StringValueConverter")]
public string Path { get; set; }
```

**VB**<br />
``` VB
<IODescriptionAttribute("FSW_Path")>
<DefaultValueAttribute("")>
<SettingsBindableAttribute(true)>
<TypeConverterAttribute("System.Diagnostics.Design.StringValueConverter")>
Public Property Path As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevFileSystemWatcher
Dim value As String

value = instance.Path

instance.Path = value
```

**C++**<br />
``` C++
public:
[IODescriptionAttribute(L"FSW_Path")]
[DefaultValueAttribute(L"")]
[SettingsBindableAttribute(true)]
[TypeConverterAttribute(L"System.Diagnostics.Design.StringValueConverter")]
property String^ Path {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<IODescriptionAttribute("FSW_Path")>]
[<DefaultValueAttribute("")>]
[<SettingsBindableAttribute(true)>]
[<TypeConverterAttribute("System.Diagnostics.Design.StringValueConverter")>]
member Path : string with get, set

```


#### Property Value
Type: String<br />The path of the directory to watch.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DevFileSystemWatcher">DevFileSystemWatcher Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />