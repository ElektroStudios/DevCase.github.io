# VisualBasicCompiler Class
 

Provides Visual Basic code compiler features.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Interop_Managed_Compiler">DevCase.Interop.Managed.Compiler</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Interop.Managed.VisualBasicCompiler<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class VisualBasicCompiler : Compiler
```

**VB**<br />
``` VB
Public Class VisualBasicCompiler
	Inherits Compiler
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicCompiler
```

**C++**<br />
``` C++
public ref class VisualBasicCompiler : public Compiler
```

**F#**<br />
``` F#
type VisualBasicCompiler =  
    class
        inherit Compiler
    end
```

The VisualBasicCompiler type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_VisualBasicCompiler__ctor">VisualBasicCompiler</a></td><td>
Initializes a new instance of the VisualBasicCompiler class.</td></tr></table>&nbsp;
<a href="#visualbasiccompiler-class">Back to Top</a>

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
<a href="#visualbasiccompiler-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to use the VisualBasicCompiler. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' The VisualBasic.NET compiler instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    Dim WithEvents vbCompiler As Compiler =
        New VisualBasicCompiler(CompilerVersions.V4)

    Private Sub Form1_Shown() Handles MyBase.Shown

        With Me.vbCompiler.Compilersettings
            .GenerateDebugInformation = True
            .GenerateWarnings = True
            .GenerateXmlDocumentation = True
            .HighEntropyEnabled = True
            .IntegerOverflowChecksEnabled = False
            .OptimizationsEnabled = True
            .Platform = Platform.AnyCpu
            .SubsystemVersion = SubsystemVersions.WindowsXP
            .TreatWarningsAsErrors = False
            .Verbose = True
            .VerboseSyntax = False
            .WarningLevel = WarningLevelEnum.Level3
            .LibraryPaths.Add(IO.Directory.GetCurrentDirectory)
        End With

        Dim referencedAssemblies As New List(Of String)
        referencedAssemblies.AddRange({"System.dll", "System.Windows.Forms.dll"})

        ' Compile a VB Console App from string.
        vbCompiler.CompileFromString(netAssembly:=NetAssembly.Console,
                                     targetFile:="C:\VB Default Console App.exe",
                                     sourceCode:=Templates.TemplateVbConsoleApp,
                                     mainClass:="MainNamespace.MainModule",
                                     referencedAssemblies:=referencedAssemblies,
                                     resources:=Nothing,
                                     iconFile:=Nothing)

        ' Compile a VB WinForms App from string.
        vbCompiler.CompileFromString(netAssembly:=NetAssembly.WinExe,
                                     targetFile:="C:\VB Default WinForms App.exe",
                                     sourceCode:=Templates.TemplateVbWinFormsApp,
                                     mainClass:="MainNamespace.MainClass",
                                     referencedAssemblies:=referencedAssemblies,
                                     resources:=Nothing,
                                     iconFile:=Nothing)

        ' Compile a VB library from string.
        vbCompiler.CompileFromString(netAssembly:=NetAssembly.DynamicLinkLibrary,
                                     targetFile:="C:\VB Default Library.dll",
                                     sourceCode:=Templates.TemplateVbLib,
                                     mainClass:="MainNamespace.MainClass",
                                     referencedAssemblies:=referencedAssemblies,
                                     resources:=Nothing,
                                     iconFile:=Nothing)

        ' Compile a VB local file that contains the sourcecode.
        vbCompiler.CompileFromFile(netAssembly:=NetAssembly.WinExe,
                                   targetFile:="C:\VB Custom App.exe",
                                   sourceFile:="C:\SourceCode.vb",
                                   mainClass:="MainNamespace.MainClass",
                                   referencedAssemblies:=referencedAssemblies,
                                   resources:=Nothing,
                                   iconFile:=Nothing)

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="Compiler.CompilerWorkDone"/> event of the vbCompiler instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="CompilerWorkDoneEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Public Sub VbCompiler_CompilerWorkDone(ByVal sender As Object, ByVal e As Compiler.CompilerWorkDoneEventArgs) _
    Handles vbCompiler.CompilerWorkDone

        Console.WriteLine(String.Format("Compiler: {0}", e.CodeDomProvider.ToString()))
        Console.WriteLine(String.Format("Parameters: {0}", e.CompilerParameters.CompilerOptions))

        For Each war As CompilerWarning In e.CompilerWarnings
            Console.WriteLine(String.Format("{0}| Warning: {1}", war.ErrorNumber, war.ErrorText))
        Next war

        For Each err As CompilerErrorEx In e.CompileErrors
            Console.WriteLine(String.Format("{0}| Error: {1}", err.ErrorNumber, err.ErrorText))
        Next err

        If Not e.CompileErrors.Any Then
            Console.WriteLine(String.Format("Compilation Successful: {0}", e.TargetFilePath))
        End If

        Console.WriteLine()

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />