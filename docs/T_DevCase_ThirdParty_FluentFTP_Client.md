# Client Class
 

An FTP Client powered by FluentFTP library.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.FluentFTP.Client<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class Client : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class Client
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
```

**C++**<br />
``` C++
public ref class Client sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Client =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The Client type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client__ctor">Client</a></td><td>
Initializes a new instance of the Client class.</td></tr></table>&nbsp;
<a href="#client-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_Connect">Connect</a></td><td>
Connects to the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_CreateDirectory">CreateDirectory</a></td><td>
Creates a directory on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_DeleteDirectory">DeleteDirectory</a></td><td>
Creates a directory on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_DeleteFile">DeleteFile</a></td><td>
Deletes a file on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_DirectoryExists">DirectoryExists</a></td><td>
Checks if a directory exist on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_Disconnect">Disconnect</a></td><td>
Disconnects from the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_DownloadFile">DownloadFile</a></td><td>
Downloads a file from the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_Execute">Execute</a></td><td>
Executes a command on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_FileExists">FileExists</a></td><td>
Checks if a file exist on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetDirectories">GetDirectories</a></td><td>
Gets a directory list on the specified path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetFiles">GetFiles</a></td><td>
Gets a file list on the specified path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetFileSize">GetFileSize</a></td><td>
Gets the size of file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetHashAlgorithm">GetHashAlgorithm</a></td><td>
Gets the currently HASH algorithm used for the HASH command on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetLinks">GetLinks</a></td><td>
Gets a link list on the specified path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetListing">GetListing</a></td><td>
Gets a file/folder list on the specified path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetModifiedTime">GetModifiedTime</a></td><td>
Gets the modified time of file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetNameListing">GetNameListing</a></td><td>
Returns a file/directory listing using the NLST command.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_GetWorkingDirectory">GetWorkingDirectory</a></td><td>
Gets the current working directory on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_LogToConsole">LogToConsole</a></td><td>
Log to a console window</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_LogToFile">LogToFile</a></td><td>
Log to a text file</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_OpenAppend">OpenAppend</a></td><td>
Opens the specified file to be appended to...</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_OpenRead">OpenRead</a></td><td>
Opens the specified file for reading.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_OpenWrite">OpenWrite</a></td><td>
Opens the specified file for writing.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_RenameDirectory">RenameDirectory</a></td><td>
Rename a directory on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_RenameFile">RenameFile</a></td><td>
Rename a file on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_SetHashAlgorithm">SetHashAlgorithm</a></td><td>
Tells the FTP server wich hash algorithm to use for the HASH command.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_SetWorkingDirectory">SetWorkingDirectory</a></td><td>
Sets the working directory on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_TryExecute">TryExecute</a></td><td>
Tries to execute a command on the FTP server.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_FluentFTP_Client_UploadFile">UploadFile</a></td><td>
Uploads a file to the FTP server.</td></tr></table>&nbsp;
<a href="#client-class">Back to Top</a>

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
<a href="#client-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Private WithEvents uploadClient As New WebClient
Private WithEvents downloadClient As New WebClient

Private ftp As New Client("ftpsite", "username", "password")

Private Sub Test() Handles MyBase.Shown

    ftp.Connect()
    ftp.CreateDirectory("/DirectoryName", True)
    ftp.UploadFile(uploadClient, "C:\File.txt", "/DirectoryName/NewFile.txt", False)
    ftp.DownloadFile(downloadClient, "/DirectoryName/NewFile.txt", "c:\DownloadedFile.txt", True)

End Sub

Private Sub Client_UploadProgress(ByVal sender As Object, ByVal e As UploadProgressChangedEventArgs) _
Handles uploadClient.UploadProgressChanged

    Label_Upload.Text = e.ProgressPercentage & "%"

End Sub

Private Sub Client_UploadCompleted(ByVal sender As Object, ByVal e As UploadFileCompletedEventArgs) _
Handles uploadClient.UploadFileCompleted

    Label_UploadCompleted.Text = e.Result.ToString()

End Sub

Private Sub Client_DownloadProgress(ByVal sender As Object, ByVal e As DownloadProgressChangedEventArgs) _
Handles downloadClient.DownloadProgressChanged

    Label_Download.Text = e.ProgressPercentage & "%"

End Sub

Private Sub Client_DownloadCompleted(ByVal sender As Object, ByVal e As AsyncCompletedEventArgs) _
 Handles downloadClient.DownloadFileCompleted

    Label_DownloadCompleted.Text = "Done!"

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />