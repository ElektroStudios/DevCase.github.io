# CommandLineValueParameterCollection Class
 

Represents a strongly typed list of <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that can be accessed by an index.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Collections.ObjectModel.Collection(<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter</a>(IConvertible))<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticCollection_1">DevCase.Core.Design.AestheticCollection</a>(<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter</a>(IConvertible))<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.CommandLineValueParameterCollection<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("CommandLineValueParameterCollection")]
public class CommandLineValueParameterCollection : AestheticCollection<CommandLineValueParameter<IConvertible>>
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("CommandLineValueParameterCollection")>
Public Class CommandLineValueParameterCollection
	Inherits AestheticCollection(Of CommandLineValueParameter(Of IConvertible))
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameterCollection
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"CommandLineValueParameterCollection")]
public ref class CommandLineValueParameterCollection : public AestheticCollection<CommandLineValueParameter<IConvertible^>^>
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("CommandLineValueParameterCollection")>]
type CommandLineValueParameterCollection =  
    class
        inherit AestheticCollection<CommandLineValueParameter<IConvertible>>
    end
```

The CommandLineValueParameterCollection type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection__ctor">CommandLineValueParameterCollection</a></td><td>
Initializes a new instance of the CommandLineValueParameterCollection class.</td></tr></table>&nbsp;
<a href="#commandlinevalueparametercollection-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_CommandLineValueParameterCollection_Item">Item</a></td><td>
Gets or sets the <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified key name.</td></tr></table>&nbsp;
<a href="#commandlinevalueparametercollection-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_Add">Add</a></td><td>
Adds a <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> to the end of the CommandLineValueParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_AddRange">AddRange</a></td><td>
Adds the specified parameters to the end of the CommandLineValueParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_Contains">Contains</a></td><td>
Determines whether the CommandLineValueParameterCollection contains a <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified key name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_Find">Find</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified parameter name, and returns the first occurrence within the entire CommandLineValueParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_IndexOf">IndexOf</a></td><td>
Searches for an <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified key name and returns the zero-based index of the first occurrence within the entire CommandLineValueParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_Remove_1">Remove(String)</a></td><td>
Removes a <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> from the CommandLineValueParameterCollection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_CommandLineValueParameterCollection_Remove">Remove(CommandLineValueParameter(IConvertible))</a></td><td>
Removes a <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> from the CommandLineValueParameterCollection.</td></tr></table>&nbsp;
<a href="#commandlinevalueparametercollection-class">Back to Top</a>

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
<a href="#commandlinevalueparametercollection-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Module Module1

    Dim params As New CommandLineValueParameterCollection From {
        New CommandLineValueParameter(Of String)("ParameterName1") With {
            .Prefix = CommandLineParameterPrefix.Slash,
            .Suffix = CommandLineParameterSuffix.EqualsSign,
            .ShortName = "Param1",
            .DefaultValue = "",
            .IsOptional = False
        },
        New CommandLineValueParameter(Of Boolean)("ParameterName2") With {
            .Prefix = CommandLineParameterPrefix.Slash,
            .Suffix = CommandLineParameterSuffix.EqualsSign,
            .ShortName = "Param2",
            .DefaultValue = False,
            .IsOptional = True
        },
        New CommandLineValueParameter(Of Integer)("ParameterName3") With {
            .Prefix = CommandLineParameterPrefix.Slash,
            .Suffix = CommandLineParameterSuffix.EqualsSign,
            .ShortName = "Param3",
            .DefaultValue = -1I,
            .IsOptional = True
        }
    }

    Public Function IsParameterAssignedInArgument(Of T As IConvertible)(ByVal parameter As CommandLineValueParameter(Of T), ByVal argument As String) As Boolean
        Return (argument.StartsWith(parameter.FullName & parameter.GetSuffixChar(), StringComparison.OrdinalIgnoreCase) OrElse
                argument.StartsWith(parameter.FullShortName & parameter.GetSuffixChar(), StringComparison.OrdinalIgnoreCase))
    End Function

    Public Sub SetParameterValue(Of T As IConvertible)(ByRef parameter As CommandLineValueParameter(Of T), ByVal argument As String)

        If IsParameterAssignedInArgument(parameter, argument) Then

            Dim value As String = argument.Substring(argument.IndexOf(parameter.GetSuffixChar()) + 1).Trim(ControlChars.Quote)

            If String.IsNullOrEmpty(value) Then
                parameter.Value = parameter.DefaultValue

            Else
                Try
                    parameter.Value = DirectCast(Convert.ChangeType(value, parameter.DefaultValue.GetType()), T)

                Catch ex As InvalidCastException
                    Throw

                Catch ex As FormatException
                    Throw

                End Try

            End If

        End If

    End Sub

    Sub Main()

        ' Parse command-line arguments to set the values of the parameters.
        ParseArguments(params, AddressOf OnSyntaxError, AddressOf OnMissingParameterRequired)

        ' Display the parameters and each value assigned.
        For Each param As CommandLineValueParameter(Of IConvertible) In params
            Console.WriteLine(param.ToString())
        Next

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Loop through all the command-line arguments of this application.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="cmds">
    ''' The commandline parameters.
    ''' </param>
    ''' 
    ''' <param name="callbackSyntaxError">
    ''' An encapsulated method that is invoked if a syntax error is found in one of the arguments.
    ''' </param>
    ''' 
    ''' <param name="callbackMissingRequired">
    ''' An encapsulated method that is invoked if a required parameter is missing in the arguments.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Friend Sub ParseArguments(ByVal cmds As CommandLineValueParameterCollection,
                              ByVal callbackSyntaxError As Action(Of CommandLineValueParameter(Of IConvertible)),
                              ByVal callbackMissingRequired As Action(Of CommandLineValueParameter(Of IConvertible)))

        ParseArguments(cmds, Environment.GetCommandLineArgs.Skip(1), callbackSyntaxError, callbackMissingRequired)

    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Loop through all the command-line arguments of this application.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="cmds">
    ''' The commandline parameters.
    ''' </param>
    ''' 
    ''' <param name="args">
    ''' The collection of commandline arguments to examine.
    ''' </param>
    ''' 
    ''' <param name="callbackSyntaxError">
    ''' An encapsulated method that is invoked if a syntax error is found in one of the arguments.
    ''' </param>
    ''' 
    ''' <param name="callbackMissingRequired">
    ''' An encapsulated method that is invoked if a required parameter is missing in the arguments.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Friend Sub ParseArguments(ByVal cmds As CommandLineValueParameterCollection,
                              ByVal args As IEnumerable(Of String),
                              ByVal callbackSyntaxError As Action(Of CommandLineValueParameter(Of IConvertible)),
                              ByVal callbackMissingRequired As Action(Of CommandLineValueParameter(Of IConvertible)))

        If Not (args.Any()) Then
            PrintHelp()
        End If

        ' Required parameters. Not optional ones.
        Dim cmdRequired As List(Of CommandLineValueParameter(Of IConvertible)) =
            (From cmd As CommandLineValueParameter(Of IConvertible) In cmds
             Where Not cmd.IsOptional).ToList()

        For Each arg As String In args

            For Each cmd As CommandLineValueParameter(Of IConvertible) In cmds

                If arg.Equals("/?") Then
                    PrintHelp()
                End If

                If IsParameterAssignedInArgument(cmd, arg) Then

                    If (cmdRequired.Contains(cmd)) Then
                        cmdRequired.Remove(cmd)
                    End If

                    Try
                        SetParameterValue(Of IConvertible)(cmd, arg)

                    Catch ex As Exception
                        callbackSyntaxError.Invoke(cmd)

                    End Try

                End If

            Next cmd

        Next arg

        If (cmdRequired.Any()) Then
            callbackMissingRequired.Invoke(cmdRequired.First())
        End If

    End Sub

    Friend Sub OnSyntaxError(ByVal cmd As CommandLineValueParameter(Of IConvertible))
        Console.WriteLine(String.Format("[X] Syntax error in parameter: {0})", cmd.FullName))
        Environment.Exit(exitCode:=1)
    End Sub

    Friend Sub OnMissingParameterRequired(ByVal cmd As CommandLineValueParameter(Of IConvertible))
        Console.WriteLine(String.Format("[X] Parameter {0} is required. ", cmd.FullName))
        Environment.Exit(exitCode:=1)
    End Sub

    Friend Sub PrintHelp()
        Dim sb As New Global.System.Text.StringBuilder
        sb.AppendLine("Commands Help:")
        For Each param As CommandLineValueParameter(Of IConvertible) In params
            sb.AppendFormat("{0} {{{1}}}", param.FullName, param.DefaultValue.GetType().Name)
            sb.AppendLine()
        Next
        Console.WriteLine(sb.ToString())
        Environment.Exit(exitCode:=1)
    End Sub

End Module
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />