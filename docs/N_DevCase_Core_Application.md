# DevCase.Core.Application Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_AppOpenWithInfo">AppOpenWithInfo</a></td><td>
Represents the `OpenWith` specific information for an application registration through `HKEY_CLASSES_ROOT\Applications\ApplicationName.exe` registry subkey.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo</a></td><td>
Represents the `ShellExecute` specific information for an application registration through `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\App Paths` registry subkey.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_CommandLineArgumentsNotifier">CommandLineArgumentsNotifier</a></td><td>
Notifies when the current application receives new command-line arguments. 

 You would use this class to manage the command-line arguments for single-instance applications that are associated to filetypes, for example.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a></td><td>
Represents a command-line parameter that does not takes any value.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Application_CommandLineParameterCollection">CommandLineParameterCollection</a></td><td>
Represents a strongly typed list of <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> that can be accessed by an index.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a></td><td>
Represents a command-line parameter that takes a value of specific Type.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection</a></td><td>
Represents a strongly typed list of <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that can be accessed by an index.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Application_DateComparer">DateComparer</a></td><td>
Performs a comparison between two DateTime instances.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_Hotkey">Hotkey</a></td><td>
Creates a system-wide hotkey for the current application.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Application_NumericComparer">NumericComparer</a></td><td>
Performs a comparison between two numeric values.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_Application_NumericSequenceFormatter">NumericSequenceFormatter</a></td><td>
Provides a mechanism to perform custom string formatting of a numeric sequence. (Byte, Int16, Int32, Int64, etc.)</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Application_StringLengthComparer">StringLengthComparer</a></td><td>
Performs a comparison between the length of two String values.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_Application_TextComparer">TextComparer</a></td><td>
Performs a comparison between two string values.</td></tr></table>

## Enumerations
&nbsp;<table><tr><th></th><th>Enumeration</th><th>Description</th></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Application_CommandLineParameterPrefix">CommandLineParameterPrefix</a></td><td>
Specifies the prefix character that indicates the start of the parameter's name of a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a></td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Application_CommandLineParameterSuffix">CommandLineParameterSuffix</a></td><td>
Specifies the suffix character that delimits the parameter's name from the parameter's value of a <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a></td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Application_ComparerResult">ComparerResult</a></td><td>
Specifies a comparison result.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Application_MutexScope">MutexScope</a></td><td>
Specifies the visibility scope for a Mutex object.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_Application_ProcessArchitecture">ProcessArchitecture</a></td><td>
Specifies a process architecture.</td></tr></table>&nbsp;
