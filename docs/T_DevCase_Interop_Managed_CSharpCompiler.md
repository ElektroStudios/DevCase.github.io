# CSharpCompiler Class
 

Provides CSharp code compiler features.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Interop_Managed_Compiler">DevCase.Interop.Managed.Compiler</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Interop.Managed.CSharpCompiler<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class CSharpCompiler : Compiler
```

**VB**<br />
``` VB
Public Class CSharpCompiler
	Inherits Compiler
```

**VB Usage**<br />
``` VB Usage
Dim instance As CSharpCompiler
```

**C++**<br />
``` C++
public ref class CSharpCompiler : public Compiler
```

**F#**<br />
``` F#
type CSharpCompiler =  
    class
        inherit Compiler
    end
```

The CSharpCompiler type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Managed_CSharpCompiler__ctor">CSharpCompiler</a></td><td>
Initializes a new instance of the CSharpCompiler class.</td></tr></table>&nbsp;
<a href="#csharpcompiler-class">Back to Top</a>

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
<a href="#csharpcompiler-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to use the CSharpCompiler. 
**VB**<br />
``` VB
Public NotInheritable Class Form1 : Inherits Form

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' The C# compiler instance.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    Dim WithEvents csCompiler As Compiler = New CSharpCompiler(CompilerVersions.V4)

    Private Sub Form1_Shown() Handles MyBase.Shown

        With Me.csCompiler.Compilersettings
            .GenerateDebugInformation = True
            .GenerateWarnings = True
            .GenerateXmlDocumentation = True
            .HighEntropyEnabled = True
            .IntegerOverflowChecksEnabled = False
            .OptimizationsEnabled = True
            .OutputLanguage = New CultureInfo("en-US")
            .Platform = AssemblyPlatform.AnyCpu
            .SubsystemVersion = SubsystemVersions.WindowsXP
            .TreatWarningsAsErrors = False
            .Verbose = True
            .VerboseSyntax = False
            .WarningLevel = CompilerWarningLevel.Level3
            .LibraryPaths.Add(Directory.GetCurrentDirectory)
        End With

        Dim referencedAssemblies As New List(Of String)
        referencedAssemblies.AddRange({"System.dll", "System.Windows.Forms.dll"})

        ' Compile a C# Console App from string.
        csCompiler.CompileFromString(netAssembly:=AssemblyType.Console,
                                     targetFile:="C:\CS Default Console App.exe",
                                     sourceCode:=CompilerUtil.Snippets.CSharp.ConsoleApp,
                                     mainClass:="MainNamespace.MainClass",
                                     referencedAssemblies:=referencedAssemblies,
                                     resources:=Nothing,
                                     iconFile:=Nothing)

        ' Compile a C# WinForms App from string.
        csCompiler.CompileFromString(netAssembly:=AssemblyType.WinExe,
                                     targetFile:="C:\CS Default WinForms App.exe",
                                     sourceCode:=CompilerUtil.Snippets.CSharp.WinFormsApp,
                                     mainClass:="MainNamespace.MainClass",
                                     referencedAssemblies:=referencedAssemblies,
                                     resources:=Nothing,
                                     iconFile:=Nothing)

        ' Compile a C# library from string.
        csCompiler.CompileFromString(netAssembly:=AssemblyType.DynamicLinkLibrary,
                                     targetFile:="C:\CS Default Library.dll",
                                     sourceCode:=CompilerUtil.Snippets.CSharp.Library,
                                     mainClass:="MainNamespace.MainClass",
                                     referencedAssemblies:=referencedAssemblies,
                                     resources:=Nothing,
                                     iconFile:=Nothing)

        ' Compile a C# local file that contains the sourcecode.
        csCompiler.CompileFromFile(netAssembly:=AssemblyType.WinExe,
                                   targetFile:="C:\CS Custom App.exe",
                                   sourceFile:="C:\SourceCode.cs",
                                   mainClass:="MainNamespace.MainClass",
                                   referencedAssemblies:=referencedAssemblies,
                                   resources:=Nothing,
                                   iconFile:=Nothing)

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="Compiler.CompilerWorkDone"/> event of the csCompiler instance.
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
    Public Sub CsCompiler_CompilerWorkDone(ByVal sender As Object, ByVal e As CompilerWorkDoneEventArgs) _
    Handles csCompiler.CompilerWorkDone

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
</code>
</example>
```


## See Also


#### Reference
<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />