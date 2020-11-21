# VisualBasicProjectFileManager Class
 

Represents and manipulates an existing VisualBasic.NET Project File (vbproj).


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Settings.VisualBasicProjectFileManager<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class VisualBasicProjectFileManager : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class VisualBasicProjectFileManager
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
```

**C++**<br />
``` C++
public ref class VisualBasicProjectFileManager sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type VisualBasicProjectFileManager =  
    class
        inherit AestheticObject
    end
```

The VisualBasicProjectFileManager type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Settings_VisualBasicProjectFileManager__ctor">VisualBasicProjectFileManager(FileInfo)</a></td><td>
Initializes a new instance of the VisualBasicProjectFileManager class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Settings_VisualBasicProjectFileManager__ctor_1">VisualBasicProjectFileManager(String)</a></td><td>
Initializes a new instance of the VisualBasicProjectFileManager class.</td></tr></table>&nbsp;
<a href="#visualbasicprojectfilemanager-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_AssemblyName">AssemblyName</a></td><td>
Gets or sets the project's assembly name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_AutoGenerateBindingRedirects">AutoGenerateBindingRedirects</a></td><td>
Gets or sets a value that indicates whether binding redirects may be automatically added to the app configuration file to override assembly unification.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_Configuration">Configuration</a></td><td>
Gets or sets the project's configuration mode.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_Document">Document</a></td><td>
Gets the Xml document representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_File">File</a></td><td>
Gets the project file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_FileAlignment">FileAlignment</a></td><td>
Gets or sets the project's file alignment.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_ImportedNamespaces">ImportedNamespaces</a></td><td>
Gets or sets the imported namespaces.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_ItemGroupNodes">ItemGroupNodes</a></td><td>
Gets a collection of the `<ItemGroup>` nodes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_OptionExplicitEnabled">OptionExplicitEnabled</a></td><td>
Gets or sets a value that determines whether `OptionExplicit` is enabled by default in the project.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_OptionInferEnabled">OptionInferEnabled</a></td><td>
Gets or sets a value that determines whether `OptionInfer` is enabled by default in the project.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_OptionStrictEnabled">OptionStrictEnabled</a></td><td>
Gets or sets a value that determines whether `OptionStrict` is enabled by default in the project.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_OutputType">OutputType</a></td><td>
Gets or sets the project's output type.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_Platform">Platform</a></td><td>
Gets or sets the project's target platform.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_ProjectGuid">ProjectGuid</a></td><td>
Gets or sets the project GUID.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_PropertyGroupNodes">PropertyGroupNodes</a></td><td>
Gets a collection of the `<PropertyGroup>` nodes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_ReferencedAssemblies">ReferencedAssemblies</a></td><td>
Gets or sets the referenced assemblies.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_RootNamespace">RootNamespace</a></td><td>
Gets or sets the project's root namespace.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_StartupObject">StartupObject</a></td><td>
Gets or sets the project's startup object.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_VisualBasicProjectFileManager_TargetFrameworkVersion">TargetFrameworkVersion</a></td><td>
Gets or sets the target framework version.</td></tr></table>&nbsp;
<a href="#visualbasicprojectfilemanager-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#visualbasicprojectfilemanager-class">Back to Top</a>

## Examples
This is a code example that demonstrates a general usage of VisualBasicProjectFileManager members. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\MyProject.vbproj")

' Set some properties.
With vbproj
    .ProjectGuid = Guid.NewGuid()
    .AutoGenerateBindingRedirects = True
    .OptionExplicitEnabled = True
    .OptionStrictEnabled = True
    .OptionInferEnabled = False
End With

' Add References (or clear them).
Dim referencedAssemblies As SortedDictionary(Of String, String) = vbproj.ReferencedAssemblies
With referencedAssemblies
    .Add("System.Net", Nothing) ' Assemblies stored in GAC directory doesnt's require a hint path.
    .Add("DevCase.Application", "..\..\DevCase\DevCase.Application.dll") ' Relative path.
    .Add("DevCase.Core", "C:\DevCase\DevCase.Core.dll") ' Absolute path.
End With
vbproj.ReferencedAssemblies = referencedAssemblies

' Add Imports (or clear them).
Dim importedNamespaces As SortedSet(Of String) = vbproj.ImportedNamespaces
With importedNamespaces
    .Add("System.Net")
    .Add("DevCase.Application")
    .Add("DevCase.Core")
End With
vbproj.ImportedNamespaces = importedNamespaces

' Save the changes we made, to a new file. 
' Note that the "vbproj" instance just serves as a visual representation, changes are not saved in the original file, 
' so we need to save any changes using the "vbproj.Document.Save()" method (we can replace the original file if we like).
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />