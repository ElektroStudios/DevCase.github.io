# CompilerSettings Class
 

Defines the settings of a <a href="T_DevCase_Interop_Managed_Compiler">Compiler</a>


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Interop.Managed.CompilerSettings<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CompilerSettings : IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class CompilerSettings
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As CompilerSettings
```

**C++**<br />
``` C++
public ref class CompilerSettings sealed : IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CompilerSettings =  
    class
        interface IDisposable
    end
```

The CompilerSettings type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_CompilerSettings__ctor">CompilerSettings</a></td><td>
Initializes a new instance of the CompilerSettings class.</td></tr></table>&nbsp;
<a href="#compilersettings-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_CodeProvider">CodeProvider</a></td><td>
Gets or sets the code provider.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_GenerateDebugInformation">GenerateDebugInformation</a></td><td>
Gets or sets a value that instructs the compiler to generate debug information file (pdb).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_GenerateWarnings">GenerateWarnings</a></td><td>
Gets or sets a value that instructs the compiler to be able to generate warnings.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_GenerateXmlDocumentation">GenerateXmlDocumentation</a></td><td>
Gets or sets a value that instructs the compiler to generate Xml documentation file</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_HighEntropyEnabled">HighEntropyEnabled</a></td><td>
Gets or sets a value that indicates whether a 64-bit executable or an executable that's marked by the <a href="T_DevCase_Interop_Managed_AssemblyPlatform">AnyCpu</a> compiler option supports high entropy Address Space Layout Randomization (ASLR).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_IntegerOverflowChecksEnabled">IntegerOverflowChecksEnabled</a></td><td>
Gets or sets a value that turns overflow-error checking for integer operations on or off.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_LibraryPaths">LibraryPaths</a></td><td>
Gets or sets a value that specifies additional directories in which to search for assembly references.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_OptimizationsEnabled">OptimizationsEnabled</a></td><td>
Gets or sets a value that enables or disables compiler optimizations.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_OutputLanguage">OutputLanguage</a></td><td>
Gets or sets the language that the compiler will use to display the output messages. 

 This option is only available for C# compiler.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_Platform">Platform</a></td><td>
Gets or sets a value that specifies which platform version of common language runtime (CLR) can run the output file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_SubsystemVersion">SubsystemVersion</a></td><td>
Gets or sets a value that specifies the minimum version of the subsystem on which the generated executable file can run, thereby determining the versions of Windows on which the executable file can run. Most commonly, this option ensures that the executable file can leverage particular security features that aren’t available with older versions of Windows.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_TempFileCollection">TempFileCollection</a></td><td>
Gets or sets the temporary files collection where the compiler stores the temporary files generated during a build.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_TreatWarningsAsErrors">TreatWarningsAsErrors</a></td><td>
Gets or sets a value instructs the compiler to treat warnings as errors.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_Verbose">Verbose</a></td><td>
Gets or sets a value that instructs the compiler to produce verbose status and error messages.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_VerboseSyntax">VerboseSyntax</a></td><td>
Gets or sets a value that instructs the compiler from displaying code for syntax-related errors and warnings.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Managed_CompilerSettings_WarningLevel">WarningLevel</a></td><td>
Gets or sets the level at which the compiler should start displaying warnings.</td></tr></table>&nbsp;
<a href="#compilersettings-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_CompilerSettings_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr></table>&nbsp;
<a href="#compilersettings-class">Back to Top</a>

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
<a href="#compilersettings-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />