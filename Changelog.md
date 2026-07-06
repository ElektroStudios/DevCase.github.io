# DevCase Class Library Version History 📋

We strive to provide you with the best possible experience by continuously improving our DevCase Class Library. While we release new versions periodically, typically every quarter, it is important to note that our development process involves numerous daily internal updates. These updates encompass additions, removals, optimizations, and fixes, all aimed at enhancing the functionality and performance of the library.

We kindly request your understanding regarding the comprehensive listing of every change in each new version. Rest assured, our team is dedicated to delivering a top-quality product that meets your expectations and requirements.

Thank you for your continued support and trust in DevCase Class Library.

Best regards,
The DevCase Team

# v6.0 🚀🆕

🚀 After receiving a considerable amount of requests from our customers, we have delivered to restore the previous file distribution and organization structure. Consequently, we have consolidated most of the libraries into a single DLL file named "DevCase.net48.dll" and "DevCase.net60.dll" respectively.

As of this update, this restructuring is permanently established for future updates.

It is important to emphasize that this change does not affect the general use of DevCase; We have simply unified all namespaces and their classes into a single DLL file. This way, instead of importing multiple DLL files into your project, you now only need to import a single DLL file.

🚀🚀 In addition, we have also introduced a standalone installer in this release, designed to make the integration process of using the DevCase user controls in the Windows Forms designer easier and faster, by using a guided installation of Nuget packages for both .NET Framework and .NET Core projects.

🚀🚀🚀 And if that were not enough, in this release we also included a standalone installer to integrate a dozen project templates into Visual Studio, for both .NET Framework and .NET Core.

# v5.2 🔄

#### 🖼️ New Controls:
    • DevCase.UI.Components.DevFloatingPicture
    • DevCase.UI.Controls.DevTitleBar
    • DevCase.UI.Controls.DevTitleBarCompact

#### 🧰 New Utility Classes:
    • DevCase.Thirdarty.WTelegramClient.WTelegramClientHelper

#### 📦 New Types:
    • DevCase.Thirdarty.WTelegramClient.MessageData
    • DevCase.Thirdarty.WTelegramClient.TelegramClientConfig

#### 🤖 New Methods:
    • DevCase.Win32.NativeMethods.DrawEdge
    • DevCase.Win32.NativeMethods.DrawFrameControl
    • DevCase.Win32.NativeMethods.SendMessage (HandleRef overloads)
    • DevCase.Win32.NativeMethods.TrackPopupMenu

#### 🧩 New Extension Methods:
    • Bitmap.ToIcon (overload)
    • FileStream.IndexOf
    • Form.AddComponents
    • Form.GetComponents
    • Form.RemoveComponents
    • IContainerControl.AddComponents
    • IContainerControl.GetComponents
    • IContainerControl.RemoveComponents
    • Image.ToIcon (overload)
    • MemoryStream.IndexOf
    • TL.Channel.GetFlags (WTelegramClient)
    • TL.Channel.GetFlags2 (WTelegramClient)
    • TL.Channel.GetId (WTelegramClient)
    • TL.Channel.GetPhoto (WTelegramClient)
    • TL.Channel.GetTitle (WTelegramClient)
    • TL.ForumTopic.GetFlags (WTelegramClient)
    • TL.ForumTopic.GetId (WTelegramClient)
    • TL.Message.GetDate (WTelegramClient)
    • TL.Message.GetFlags (WTelegramClient)
    • TL.Message.GetId (WTelegramClient)
    • TL.User.GetFlags (WTelegramClient)
    • TL.User.GetFlags2 (WTelegramClient)
    • TL.User.GetId (WTelegramClient)

#### 🚩 New Enums:
    • DevCase.Win32.Enums.DrawEdgeFlags
    • DevCase.Win32.Enums.DrawEdgeType
    • DevCase.Win32.Enums.DrawFrameControlButtonFlags
    • DevCase.Win32.Enums.DrawFrameControlCaptionType
    • DevCase.Win32.Enums.DrawFrameControlMenuType
    • DevCase.Win32.Enums.DrawFrameControlScrollFlags
    • DevCase.Win32.Enums.DrawFrameControlType
    • DevCase.Win32.Enums.TrackPopupMenuFlags

#### 🛠️ Fixes:
    • Stream.IndexOf search algorithm has been fixed and optimized.
    • Renamed DevCase.UI.Controls.DevDrivDevComboBox class to DevCase.UI.Controls.DevDriveComboBox
    • DevDriveComboBox control was unable to load in the Windows forms Designer of a NET Core project
    • DevTitleBar control was unable to load in the Windows forms Designer of a NET Core project
    • DevTitleBarCompact control was unable to load in the Windows forms Designer of a NET Core project

#### ✏️ Renamed Members:
    • DevCase.Extensions.Control.SetVisualStyle -> SetVisualTheme
    • DevCase.Extensions.Form.SetVisualStyle -> SetVisualTheme
    • DevCase.Runtime.Dialogs.DevMessageBox -> DevCase.UI.Dialogs.DevMessageBox
    • DevCase.UI.Enums.VisualStyle -> DevCase.Core.Application.Forms.VisualTheme

#### 🌟 Improvements:
    • Improved ProgressBar control support for DevCase.Extensions.Control.SetVisualTheme method.
    • Improved logic for DevCase.Core.Application.Forms.UtilForms.MinimizeToSystray method.
    • Improved logic for DevCase.Core.Application.Forms.UtilForms.RestoreFromSystray method.
    • Improved logic for DevCase.Core.Application.Forms.UtilForms.ToggleFormSystray method.

# v5.1 🔄

#### 🧰 New Utility Classes:
    • Core.DataProcessing.Common.UnicodeCharacterMaps
    • Core.DataProcessing.Html.UtilHtml
    • Core.DataProcessing.Markdown.UtilMarkdown
    • Core.Security.Passwords.UtilPasswords

#### 📦 New Types:
    • Core.DataProcessing.Common.BoxDrawingStyle
    • Core.DataProcessing.Html.LinkifyFindObject
    • Core.DataProcessing.Html.LinkifyFormatOptions
    • Core.DataProcessing.Html.UrlSlugOptions
    • Core.DataProcessing.Markdown.MarkdownItOptions
    • Core.Security.Passwords.MemorablePasswordOptions
    • Runtime.Collections.NameObjectCollection

#### 🔖 New Properties:
    • Core.Application.Console.UtilConsole.SafeHandle
    • Core.Application.Console.UtilConsole.Transparency
    • Core.DataProcessing.Common.UnicodeCharacterMaps.MathematicalBold
    • Core.DataProcessing.Common.UnicodeCharacterMaps.MathematicalBoldItalic
    • Core.DataProcessing.Common.UnicodeCharacterMaps.MathematicalBoldScript
    • Core.DataProcessing.Common.UnicodeCharacterMaps.MathematicalItalic
    • Core.DataProcessing.Common.UnicodeCharacterMaps.MonoSpace
    • Core.DataProcessing.Common.UnicodeCharacterMaps.SansSerif
    • Core.DataProcessing.Common.UnicodeCharacterMaps.SansSerifBold
    • Core.DataProcessing.Common.UnicodeCharacterMaps.SansSerifBoldItalic
    • Core.DataProcessing.Common.UnicodeCharacterMaps.SansSerifItalic
    • Core.Media.Sound.UtilAudio.InstalledVoices

#### 🤖 New Methods:
    • Core.Application.Console.UtilConsole.ConsoleTextBlinkMultiline
    • Core.Application.Console.UtilConsole.SetColors
    • Core.Application.Console.UtilConsole.SetEncodings
    • Core.DataProcessing.Common.UtilString.CalculateStringEntropy
    • Core.DataProcessing.Common.UtilString.ConvertFromSuperscript
    • Core.DataProcessing.Common.UtilString.ConvertToSuperscript
    • Core.DataProcessing.Common.UtilString.ConvertToUnicodeLetters
    • Core.DataProcessing.Common.UtilString.DrawTextBox
    • Core.DataProcessing.Common.UtilString.FlipTextVertically
    • Core.DataProcessing.Common.UtilString.GenerateTypos
    • Core.DataProcessing.Common.UtilString.JustifyText
    • Core.DataProcessing.Common.UtilString.RandomReplaceLetterOrDigit
    • Core.DataProcessing.Common.UtilString.RandomReplaceLettersAndDigits
    • Core.DataProcessing.Common.UtilString.WrapCharacters
    • Core.DataProcessing.Html.UtilHtml.CreateUrlSlug
    • Core.DataProcessing.Html.UtilHtml.FindLinks
    • Core.DataProcessing.Html.UtilHtml.IsLink
    • Core.DataProcessing.Html.UtilHtml.Linkify
    • Core.DataProcessing.Html.UtilHtml.NewLineToHtmlBreak
    • Core.DataProcessing.Json.UtilJson.ParseJson
    • Core.DataProcessing.Json.UtilJson.ParseJsonLightweight
    • Core.DataProcessing.Markdown.UtilMarkdown.ConvertMarkdownToHtml
    • Core.Security.Passwords.MaskSecureString
    • Core.Security.Passwords.MaskString
    • Core.Security.Passwords.UtilPasswords.GenerateMemorablePassword
    • Runtime.Enums.UtilEnum.EnumToList
    • ThirdParty.HtmlAgilityPack.UtilHtmlAgilityPack.StripHtml
    • Win32.NativeMethods.CompareStringOrdinal
    • Win32.NativeMethods.GetClassLong
    • Win32.NativeMethods.GetClassLongPtr
    • Win32.NativeMethods.GetLayeredWindowAttributes (method overload)
    • Win32.NativeMethods.GetStockObject
    • Win32.NativeMethods.SetBkColor
    • Win32.NativeMethods.SetClassLong
    • Win32.NativeMethods.SetClassLongPtr
    • Win32.NativeMethods.SetTextColor

#### 🧩 New Extension Methods:
    • BindingSource.GetCurrent
    • Boolean.ThrowIfFalse
    • Boolean.ThrowIfTrue
    • Char.IsConsonant
    • Char.IsVowel
    • Control.SafeBeginInvoke
    • Control.SafeInvoke
    • DataColumnCollection.Rename
    • DataGridView.GetCurrentRowCellValue
    • DataGridView.GetPrintDocument
    • DataGridView.GetSelectedColumnNameIndex
    • DataTable.GetFirstRow
    • DataTable.GetLastField
    • DataTable.GetLastRow
    • DirectoryInfo.ForceDelete
    • DirectoryInfo.IsHidden
    • DirectoryInfo.IsReadOnly
    • DirectoryInfo.IsRootVolume
    • DirectoryInfo.IsSystem
    • FileInfo.ForceDelete
    • FileInfo.IsHidden
    • FileInfo.IsReadOnly
    • FileInfo.IsSystem
    • IComparable.GreatherThan
    • IComparable.LessThan
    • IDataReader.AsEnumerable
    • IEnumerable.TakeUntil
    • IEnumerable.ToHtmlTable
    • IEnumerable.ToObservableCollection
    • IEnumerable.ToSortableObservableCollection (only for .NET Framework, i.e. not for .NET Core)
    • Object.IsDefault
    • Object.NewIfNull
    • Object.Speak
    • Object.ThrowIf
    • Object.ThrowIfNotInRange
    • Object.ThrowIfNull
    • SecureString.EqualsOrdinal
    • String.CountLines
    • String.CountWords
    • String.NormalizeNewLines
    • String.NormalizeTabs
    • String.NormalizeWhiteSpaces
    • String.ReplaceAll (various method overloads to support 'Char' arguments)
    • String.ReplaceAllRegex (various method overloads to support 'Char' arguments)
    • String.Truncate
    • String.TruncateMiddle
    • String.WordWrap (method overload)
    • StringBuilder.EndsWith
    • StringBuilder.IndexOf
    • StringBuilder.LastIndexOf
    • StringBuilder.StartsWith
    • StringBuilder.WordWrap (method overload)
    • XPathNodeIterator.AsEnumerable

#### 🚩 New Enums:
    • Core.DataProcessing.Common.UnicodeAlphabeticCharacterSets
    • Core.DataProcessing.Common.UnicodeAlphanumericCharacterSets
    • Core.DataProcessing.Common.VerticalFlipTextMode
    • Core.DataProcessing.Html.LinkifyInterfaceType
    • Core.DataProcessing.Html.LinkifyLinkType
    • Core.DataProcessing.Html.LinkifyPlugins
    • Core.DataProcessing.Markdown.MarkdownItPreset
    • Core.Security.Passwords.MemorablePasswordStringCase
    • Win32.Enums.ClassLongValues
    • Win32.Enums.StockObjects

#### 🛠️ Fixes:
    • Assembly: Extensions.System.Web.dll didn't contain available members to use in .NET Core. This assembly now is removed for .NET Core.
    • Function: Extensions.StringExtensions.ReplaceAll it was replacing only the last find keyword.
    • Function: Extensions.StringExtensions.ReplaceAllRegex it was replacing only the last find keyword.
    • Function: Win32.NativeMethods.GetLayeredWindowAttributes signature has been fixed.
    • Method: Core.Application.Console.UtilConsole.ConsoleTextBlink was adding corrupted characters to the standard output.
    • Method: Core.Application.Console.UtilConsole.Pause now it takes a ConsoleKey value as parameter instead of Windows.Forms.Keys. This avoids the requirement to add a reference to System.Windows.Forms.dll assembly when calling this method.
    • Method: Core.Application.Console.UtilConsole.SetConsolefont was not visible to the end-user.
    • Method: Core.Application.Console.UtilConsole.SpinCursor was accepting wrong values for 'repeat' parameter.
    • Namespace: Runtime.Attributes was visible in .NET Core and it didn't expose public members.

#### ✏️ Renamed Members:
    • Class    : Runtime.Enums.EnumUtil -> UtilEnum
    • Function : Core.Application.Console.TypeWritter.WriteAsync -> WriteTask
    • Function : Core.Application.Console.TypeWritter.WriteColorAsync -> WriteColorTask
    • Function : Core.Application.Console.TypeWritter.WriteColorLineAsync -> WriteColorLineTask
    • Function : Core.Application.Console.TypeWritter.WriteLineAsync -> WriteLineTask
    • Function : Core.Application.Console.UtilConsole.SpinCursorAsync -> SpinCursorTask
    • Function : Extensions.SecureStringExtensions.ToUnsecureString -> ToManagedString
    • Namespace: DevCase.Extensions.PowerShell.PSObjectExtensions -> DevCase.Extensions.PSObjectExtensions

#### 🌟 Improvements:
    • Assembly: Extensions.System.Security.dll, now it targets Windows platform.
    • Function: Extensions.StringExtensions.ExpandBlankSpace, this functionality has been replaced by the new 'NormalizeWhiteSpaces' and 'NormalizeTabs' extension methods.
    • Function: Extensions.StringExtensions.WithDoubleQuotes, added parameters to personalize the double-quote characters.
    • Function: Extensions.StringExtensions.WithQuotes, added parameters to personalize the quote characters.
    • Added a \<remarks\> section for the XML documentation block of every member that requires a third-party dependency, explaining which is the missing dependency and where to download it.
    • Added .NET Core assemblies compiled with .NET 6.0 inside the product package.

# v5.0 🔄

#### 🧰 New Utility Classes:
    • DevCase.ThirdParty.Dism.DismUtil
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil
    • DevCase.ThirdParty.PowerShell.PowerShellUtil

#### 📦 New Types:
    • DevCase.Core.Design.Events.DevProgressChangedEventArgs
    • DevCase.Core.Design.Services.ServiceProvider
    • DevCase.Core.Design.Services.TypeDescriptorContext
    • DevCase.Core.Design.Services.WindowsFormsEditorService
    • DevCase.Core.IO.FileSystem.Types.AlternateDataStreamInfo
    • DevCase.Core.IO.FileSystem.Types.FileComparer
    • DevCase.Core.IO.FileSystem.Types.FileComparerByteByByte
    • DevCase.Core.Net.Types.Ed2kFilelink
    • DevCase.Core.Net.Types.WebsiteLoginRequest
    • DevCase.Core.Net.Types.WebsiteLoginResponse
    • DevCase.Win32.SafeHandles.SafeFindHandle

#### 🔖 New Properties:
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.CursorPosition
    • DevCase.Core.Diagnostics.Tools.DebugUtil.ImmediateWindowText

#### 🤖 New Methods:
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.ConsoleChoice
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.RegisterConsoleKeyPressEventHandler
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.UnregisterConsoleKeyPressEventHandler
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.Write
    • DevCase.Core.Cryptography.Tools.CryptoUtil.PolymorphicStairsDecrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.PolymorphicStairsEncrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.StairsDeCrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.StairsEncrypt
    • DevCase.Core.Diagnostics.Tools.DebugUtil.ClearImmediateWindow
    • DevCase.Core.Interop.IPC.Tools.ProcessUtil.GetCurrentProcessPrivilegeStates
    • DevCase.Core.Interop.IPC.Tools.ProcessUtil.GetProcessRamPercentUsage
    • DevCase.Core.Interop.IPC.Tools.ProcessUtil.GetProcessRamPercentUsageAsync
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.WindowsPathToUri
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.WindowsPathToUriPath
    • DevCase.Core.Net.Tools.WebUtil.GetUrlStatusCode
    • DevCase.Core.Net.Tools.WebUtil.GetUrlStatusCodeAsync
    • DevCase.Core.Net.Tools.WebUtil.IsUrlStatusCodeSucessful
    • DevCase.Core.Net.Tools.WebUtil.IsUrlStatusCodeSucessfulAsync
    • DevCase.ThirdParty.Dism.DismUtil.CopyDriverPackageToDisk
    • DevCase.ThirdParty.Dism.DismUtil.GetDriverInfo
    • DevCase.ThirdParty.Dism.DismUtil.GetDriverPackages
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.AddDirectoryRule
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.FindDirectoryRule
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.GetDirectoryRules
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.IsDirectoryIncluded
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.RemoveDirectoryRule
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellAction
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellCommand
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellCommand
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellScript

#### 🧩 New Extension Methods:
    • Component.InvokeUITypeEditor
    • Control.InvokeUITypeEditor
    • DataColumnCollection.ForEach
    • DataGridViewCellCollection.ForEach
    • DataGridViewColumnCollection.ForEach
    • DataGridViewRowCollection.ForEach
    • DataGridViewSelectedCellCollection.ForEach
    • DataGridViewSelectedColumnCollection.ForEach
    • DataGridViewSelectedRowCollection.ForEach
    • DataRowCollection.AddRange
    • DataRowCollection.ForEach
    • DismDriver.GetDriverInfoString
    • DismDriverPackage.GetClassBitmap
    • DismDriverPackage.GetClassIcon
    • DismDriverPackage.GetClassImage
    • DismDriverPackage.GetPackageDirectory
    • DismDriverPackage.GetPackageDirectoryInfName
    • DismDriverPackage.GetPackageInfoString
    • DynamicMethod.GetIlAsByteArray
    • DynamicMethod.GetRuntimeMethodHandle
    • FileInfo.GetAlternateDataStream
    • FileInfo.GetAlternateDataStreams
    • FileInfo.SetAlternateDataStream
    • Form.InvokeUITypeEditor
    • IComponent.GetDesigner
    • ListBox.CopyAllItems
    • ListBox.ScrollToBottom
    • ListBox.ScrollToTop
    • ListView.CopyAllItems
    • ListView.DeselectallItems
    • ListView.ScrollToBottom
    • ListView.ScrollToTop
    • ListView.SelectallItems
    • MemoryStream.Equals
    • MemoryStream.EqualsAsync
    • MethodBase.GetRuntimeMethodHandle
    • NameValueCollection.ToRawString
    • Process.GetProcessPrivilegeStates
    • PSObject.GetPropertiesAsString
    • Stream.Equals
    • Stream.EqualsAsync
    • StringBuilder.RemoveEnd
    • StringCollection.AsEnumerable
    • StringCollection.ToArray
    • StringCollection.ToList

#### ⚙️ New Windows API P/Invokes:
    • (kernel32) BackupRead
    • (kernel32) BackupSeek
    • (kernel32) GetFirmwareEnvironmentVariableA
    • (kernel32) IsProcessorFeaturePresent
    • (kernel32) ReadFile
    • (kernel32) WriteFile
    • (setupapi) SetupDiDestroyDeviceInfoList
    • (setupapi) SetupDiEnumDeviceInfo
    • (setupapi) SetupDiGetClassDescription
    • (setupapi) SetupDiGetClassDevs
    • (setupapi) SetupDiGetDeviceProperty
    • (setupapi) SetupDiGetDeviceProperty
    • (setupapi) SetupDiLoadClassIcon
    • (setupapi) SetupDiLoadDeviceIcon
    • (user32) GetGuiResources

#### ✏️ Renamed Members:
    • DevCase.Core.Cryptography.Tools.CryptoUtil.Decrypt -> SymmetricDecrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.Encrypt -> SymmetricEncrypt
    • DevCase.Core.IO.FileSystem.Tools.DirectoryUtil.IsDirectory -> DirectoryExists
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.ItemNameIsInvalid -> IsValidWindowsFileName
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.ItemNameOrPathIsInvalid -> IsValidWindowsFileNameOrDirectoryPath
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.ItemPathIsInvalid -> IsValidWindowsDirectoryPath
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.MakeValidWin32Filename -> MakeValidWindowsName
    • DevCase.Core.IO.FileSystem.Tools.FileUtil.IsFile -> FileExists

#### 🗑️ Removed Methods:
    • DevCase.Core.IO.FileSystem.Tools.FileUtil.IsShortcut

# v4.2 🔄

#### 🧰 New Utility Classes:
    • DevCase.ThirdParty.Dism.DismUtil
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil
    • DevCase.ThirdParty.PowerShell.PowerShellUtil

#### 📦 New Types:
    • DevCase.Core.Design.Events.DevProgressChangedEventArgs
    • DevCase.Core.Design.Services.ServiceProvider
    • DevCase.Core.Design.Services.TypeDescriptorContext
    • DevCase.Core.Design.Services.WindowsFormsEditorService
    • DevCase.Core.IO.FileSystem.Types.AlternateDataStreamInfo
    • DevCase.Core.IO.FileSystem.Types.FileComparer
    • DevCase.Core.IO.FileSystem.Types.FileComparerByteByByte
    • DevCase.Core.Net.Types.Ed2kFilelink
    • DevCase.Core.Net.Types.WebsiteLoginRequest
    • DevCase.Core.Net.Types.WebsiteLoginResponse
    • DevCase.Win32.SafeHandles.SafeFindHandle

#### 🔖 New Properties:
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.CursorPosition
    • DevCase.Core.Diagnostics.Tools.DebugUtil.ImmediateWindowText

#### 🤖 New Methods:
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.ConsoleChoice
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.RegisterConsoleKeyPressEventHandler
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.UnregisterConsoleKeyPressEventHandler
    • DevCase.Core.Application.Console.Tools.ConsoleUtil.Write
    • DevCase.Core.Cryptography.Tools.CryptoUtil.PolymorphicStairsDecrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.PolymorphicStairsEncrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.StairsDeCrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.StairsEncrypt
    • DevCase.Core.Diagnostics.Tools.DebugUtil.ClearImmediateWindow
    • DevCase.Core.Interop.IPC.Tools.ProcessUtil.GetCurrentProcessPrivilegeStates
    • DevCase.Core.Interop.IPC.Tools.ProcessUtil.GetProcessRamPercentUsage
    • DevCase.Core.Interop.IPC.Tools.ProcessUtil.GetProcessRamPercentUsageAsync
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.WindowsPathToUri
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.WindowsPathToUriPath
    • DevCase.Core.Net.Tools.WebUtil.GetUrlStatusCode
    • DevCase.Core.Net.Tools.WebUtil.GetUrlStatusCodeAsync
    • DevCase.Core.Net.Tools.WebUtil.IsUrlStatusCodeSucessful
    • DevCase.Core.Net.Tools.WebUtil.IsUrlStatusCodeSucessfulAsync
    • DevCase.ThirdParty.Dism.DismUtil.CopyDriverPackageToDisk
    • DevCase.ThirdParty.Dism.DismUtil.GetDriverInfo
    • DevCase.ThirdParty.Dism.DismUtil.GetDriverPackages
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.AddDirectoryRule
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.FindDirectoryRule
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.GetDirectoryRules
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.IsDirectoryIncluded
    • DevCase.ThirdParty.MicrosoftSearchIndexer.SearchIndexerUtil.RemoveDirectoryRule
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellAction
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellCommand
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellCommand
    • DevCase.ThirdParty.PowerShell.PowerShellUtil.ExecutePowerShellScript

#### 🧩 New Extension Methods:
    • Component.InvokeUITypeEditor
    • Control.InvokeUITypeEditor
    • DataColumnCollection.ForEach
    • DataGridViewCellCollection.ForEach
    • DataGridViewColumnCollection.ForEach
    • DataGridViewRowCollection.ForEach
    • DataGridViewSelectedCellCollection.ForEach
    • DataGridViewSelectedColumnCollection.ForEach
    • DataGridViewSelectedRowCollection.ForEach
    • DataRowCollection.AddRange
    • DataRowCollection.ForEach
    • DismDriver.GetDriverInfoString
    • DismDriverPackage.GetClassBitmap
    • DismDriverPackage.GetClassIcon
    • DismDriverPackage.GetClassImage
    • DismDriverPackage.GetPackageDirectory
    • DismDriverPackage.GetPackageDirectoryInfName
    • DismDriverPackage.GetPackageInfoString
    • DynamicMethod.GetIlAsByteArray
    • DynamicMethod.GetRuntimeMethodHandle
    • FileInfo.GetAlternateDataStream
    • FileInfo.GetAlternateDataStreams
    • FileInfo.SetAlternateDataStream
    • Form.InvokeUITypeEditor
    • IComponent.GetDesigner
    • ListBox.CopyAllItems
    • ListBox.ScrollToBottom
    • ListBox.ScrollToTop
    • ListView.CopyAllItems
    • ListView.DeselectallItems
    • ListView.ScrollToBottom
    • ListView.ScrollToTop
    • ListView.SelectallItems
    • MemoryStream.Equals
    • MemoryStream.EqualsAsync
    • MethodBase.GetRuntimeMethodHandle
    • NameValueCollection.ToRawString
    • Process.GetProcessPrivilegeStates
    • PSObject.GetPropertiesAsString
    • Stream.Equals
    • Stream.EqualsAsync
    • StringBuilder.RemoveEnd
    • StringCollection.AsEnumerable
    • StringCollection.ToArray
    • StringCollection.ToList

#### ⚙️ New Windows API P/Invokes:
    • (kernel32) BackupRead
    • (kernel32) BackupSeek
    • (kernel32) GetFirmwareEnvironmentVariableA
    • (kernel32) IsProcessorFeaturePresent
    • (kernel32) ReadFile
    • (kernel32) WriteFile
    • (setupapi) SetupDiDestroyDeviceInfoList
    • (setupapi) SetupDiEnumDeviceInfo
    • (setupapi) SetupDiGetClassDescription
    • (setupapi) SetupDiGetClassDevs
    • (setupapi) SetupDiGetDeviceProperty
    • (setupapi) SetupDiGetDeviceProperty
    • (setupapi) SetupDiLoadClassIcon
    • (setupapi) SetupDiLoadDeviceIcon
    • (user32) GetGuiResources

#### ✏️ Renamed Members:
    • DevCase.Core.Cryptography.Tools.CryptoUtil.Decrypt -> SymmetricDecrypt
    • DevCase.Core.Cryptography.Tools.CryptoUtil.Encrypt -> SymmetricEncrypt
    • DevCase.Core.IO.FileSystem.Tools.DirectoryUtil.IsDirectory -> DirectoryExists
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.ItemNameIsInvalid -> IsValidWindowsFileName
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.ItemNameOrPathIsInvalid -> IsValidWindowsFileNameOrDirectoryPath
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.ItemPathIsInvalid -> IsValidWindowsDirectoryPath
    • DevCase.Core.IO.FileSystem.Tools.FileSystemUtil.MakeValidWin32Filename -> MakeValidWindowsName
    • DevCase.Core.IO.FileSystem.Tools.FileUtil.IsFile -> FileExists

#### 🗑️ Removed Methods:
    • DevCase.Core.IO.FileSystem.Tools.FileUtil.IsShortcut

# v4.0 🔄

#### 📦 New Types:
    • DirectoryInfoNaturalComparer
    • FileInfoNaturalComparer
    • FileSystemInfoEqualityComparer
    • StringNaturalComparer
    • DevCase.Core.Interoperability.IPC.Types.WindowParenting
    • DevCase.Core.Interoperability.Languages.Tools.PythonUtil
    • DevCase.Core.IO.DisplayResolutionMode
    • DevCase.Core.IO.FileSystem.Types.FileOperation
    • DevCase.Core.IO.FileSystem.Types.FileOperationProgressSink
    • DevCase.Core.Net.Types.TenMinuteMail
    • DevCase.Core.Numerics.Types.Fraction
    • DevCase.Core.Threading.Components.DevBackgroundWorker

#### 🤖 New Methods:
    • CryptoUtil.FileHasDigitalSignature()
    • CryptoUtil.FileHasValidDigitalSignature()
    • CryptoUtil.GetFileDigitalSignature()
    • CryptoUtil.IsDigitalSignatureValid()
    • DebugUtil.BypassAmsi()
    • DebugUtil.BypassEventTracing()
    • DebugUtil.ShellCodeExecute()
    • DeviceUtil.ComputerHardwareIdFromMicrosoftHwIdType()
    • DeviceUtil.ComputerHardwareIdFromWmi()
    • DirectoryUtil.PreloadInIconCache()
    • NumericsUtil.ConvertToFraction()
    • WebUtil.SetCookies()

#### 🧩 New Extension Methods:
    • ElementHostExtensions
    • FileSystemInfoExtensions
    • FrameworkElementExtensions
    • IWin32WindowExtensions

#### 🌟 Improvements:
    • DevCase namespaces were reorganized and recategorized.
    • DevCase now includes AnyCPU, x64 and x86 builds for net60 developers.

#### 🗑️ Removal:
    • Official out of support for .NET 4.6 and .NET 4.7 DevCase assemblies. They will still be included in the package.

# v3.3 🔄

#### 🧰 New Utility Classes:
    • DevCase.Core.IO.ShortcutFileInfoIconIndexEditor
    • DevCase.Core.IPC.PauseProcessObject
    • DevCase.Core.Shell.EnvironmentFolders

#### 🤖 New Methods:
    • DevCase.Core.Diagnostics.Tools.DebugUtil.CauseBSOD()
    • DevCase.Core.Imaging.Tools.ImageUtil.ConvertImageFile()
    • DevCase.Core.IO.Tools.FileUtil.PreloadInThumbnailCache()
    • DevCase.Core.IPC.Tools.ProcessUtil.SleepThread()
    • DevCase.Core.IPC.Tools.UIAutomationUtil.PauseProcess()
    • DevCase.Core.IPC.Tools.UIAutomationUtil.PauseThread()
    • DevCase.Core.IPC.Tools.UIAutomationUtil.ResumeProcess()
    • DevCase.Core.IPC.Tools.UIAutomationUtil.ResumeThread()
    • DevCase.Core.Shell.Tools.ExplorerUtil.RebuildIconAndThumbnailCaches()
    • DevCase.Core.Shell.Tools.ExplorerUtil.RebuildIconCache()
    • DevCase.Core.Shell.Tools.ExplorerUtil.RebuildThumbnailCache()
    • DevCase.ThirdParty.Selenium.SeleniumUtil.DeserializeCookies()
    • DevCase.ThirdParty.Selenium.SeleniumUtil.SerializeCookies()

#### 🧩 New Extension Methods:
    • DevCase.Core.Extensions.UriExtensions.GetBaseDomain()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.CloseAlert()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.FindElementsByPartialText()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.FindElementsByRegEx()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.FindElementsByText()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.IsAlertPresent()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.IsElementPresent()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.RestoreCookies()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.RestoreCookiesOfCurrentDomain()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.SaveCookies()
    • DevCase.ThirdParty.Selenium.Extensions.IWebDriverExtensions.SaveCookiesOfCurrentDomain()
    • DevCase.ThirdParty.Selenium.Extensions.IWebElementExtensions.AsRemoteWebElement()

#### 🚩 New Enums, Interfaces and Structures:
    • DevCase.Core.Imaging.IconSizes
    • DevCase.Core.Imaging.ThumbnailCacheSizes
    • DevCase.Interop.Unmanaged.Win32.Enums.DefineDosDeviceFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse
    • DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption
    • DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailAlphaType
    • DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags
    • DevCase.Interop.Unmanaged.Win32.Interfaces.ISharedBitmap
    • DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItemImageFactory
    • DevCase.Interop.Unmanaged.Win32.Interfaces.IThumbnailCache
    • DevCase.Interop.Unmanaged.Win32.Structures.ThumbnailId

#### 🗑️ Removal:
    • Removed DevCase assemblies for .NET 4.0 and 4.5. This is the end of support.

#### 🌟 Improvements:
    • Added DevCase assemblies for .NET 4.8

# v3.2 🔄

#### 🖼️ New Controls:
    • DevCase.Controls.DevWebBrowser
    • DevCase.Controls.OpenFileOrFolderDialog
    • DevCase.Controls.PropertyGridInputDialog

#### 🧰 New Utility Classes:
    • DevCase.Core.Design.EnumFlagsEditor
    • DevCase.Core.Diagnostics.DebuggerNotify
    • DevCase.Core.Diagnostics.PreventDebuggerContext
    • DevCase.Core.IO.LowMemoryNotificationContext
    • DevCase.Core.IO.ShortcutFileInfo
    • DevCase.Core.NET.DevWebClient
    • DevCase.Interop.Unmanaged.PIDL

#### 📦 New Types:
    • DevCase.Interop.Unmanaged.Win32.Structures.ConsoleFontInfo
    • DevCase.Interop.Unmanaged.Win32.Structures.ConsoleFontInfoEx
    • DevCase.Interop.Unmanaged.Win32.Structures.CredUiInfo
    • DevCase.Interop.Unmanaged.Win32.Structures.DwmBlurBehind
    • DevCase.Interop.Unmanaged.Win32.Structures.IpStats
    • DevCase.Interop.Unmanaged.Win32.Structures.IShellItem
    • DevCase.Interop.Unmanaged.Win32.Structures.IShellItemImageFactory
    • DevCase.Interop.Unmanaged.Win32.Structures.MouseMovePoint
    • DevCase.Interop.Unmanaged.Win32.Structures.NativeToolBarButton
    • DevCase.Interop.Unmanaged.Win32.Structures.NativeWindowInfo
    • DevCase.Interop.Unmanaged.Win32.Structures.OpenAsInfo
    • DevCase.Interop.Unmanaged.Win32.Structures.ProcessBasicInformation
    • DevCase.Interop.Unmanaged.Win32.Structures.TrayData

#### 🤖 New Methods:
    • DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.SetConsolefont
    • DevCase.Core.Imaging.Tools.ColorUtil.WinFormsBrushToWpfBrush
    • DevCase.Core.Imaging.Tools.ColorUtil.WinFormsColorToWpfBrush
    • DevCase.Core.Imaging.Tools.ColorUtil.WinFormsColorToWpfColor
    • DevCase.Core.Imaging.Tools.ColorUtil.WpfBrushToWinFormsBrush
    • DevCase.Core.Imaging.Tools.ColorUtil.WpfColorToWinFormsBrush
    • DevCase.Core.Imaging.Tools.ColorUtil.WpfColorToWinFormsColor
    • DevCase.Core.IO.Filesize.ToString
    • DevCase.Core.IO.Tools.MouseUtil.SendMouseButton (x2)
    • DevCase.Core.IO.Tools.MouseUtil.SendMouseButtonAsync (x2)
    • DevCase.Core.IPC.Tools.UIAutomationUtil.GetToolbarButtons
    • DevCase.Core.NET.Tools.WebUtil.SetCookies (x4)
    • DevCase.Interop.Managed.Tools.ReflectionUtil.GetAllBaseTypes
    • DevCase.Interop.Managed.Tools.ReflectionUtil.GetAllDerivedTypes (x2)
    • DevCase.Interop.Unmanaged.Win32.Delegates.ApplicationRecoveryCallback
    • DevCase.Interop.Unmanaged.Win32.Delegates.EnumCodePagesProc
    • DevCase.Interop.Unmanaged.Win32.Delegates.EnumDesktopProc
    • DevCase.Interop.Unmanaged.Win32.Delegates.EnumLocalesProc
    • DevCase.Interop.Unmanaged.Win32.Delegates.EnumUILanguagesProc

#### 🧩 New Extension Methods:
    • DevCase.Core.Extensions.Component.GetEventHandlers
    • DevCase.Core.Extensions.Control.ForEachControl (x2)
    • DevCase.Core.Extensions.Control.GetEventHandlers
    • DevCase.Core.Extensions.Control.SendMouseButton (x2)
    • DevCase.Core.Extensions.Control.SetVisualStyle
    • DevCase.Core.Extensions.EventInfo.RemoveEventHandler
    • DevCase.Core.Extensions.Form.ForEachControl (x2)
    • DevCase.Core.Extensions.Form.GetEventHandlers
    • DevCase.Core.Extensions.Form.SetVisualStyle
    • DevCase.Core.Extensions.Graphics.DrawCross (x3)
    • DevCase.Core.Extensions.Graphics.DrawRoundedRectangle
    • DevCase.Core.Extensions.Graphics.DrawTriangle2D (x2)
    • DevCase.Core.Extensions.Graphics.FillRoundedRectangle
    • DevCase.Core.Extensions.Graphics.FillTriangle2D (x2)
    • DevCase.Core.Extensions.IDictionary.AddRange
    • DevCase.Core.Extensions.Rectangle.RoundCorners
    • DevCase.Core.Extensions.RectangleF.RoundCorners
    • DevCase.Core.Extensions.Type.GetAllBaseTypes
    • DevCase.Core.Extensions.Type.GetAllDerivedTypes (x2)
    • DevCase.Core.Extensions.Vector2.ToNativePoint
    • DevCase.Core.Extensions.Vector2.ToPoint
    • DevCase.Core.Extensions.Vector2.ToPointF
    • DevCase.Core.Extensions.Vector3.ToNativePoint
    • DevCase.Core.Extensions.Vector3.ToPoint
    • DevCase.Core.Extensions.Vector3.ToPointF

#### 🚩 New Interfaces:

    • DevCase.Interop.Unmanaged.Win32.Interfaces.IDropSource
    • DevCase.Interop.Unmanaged.Win32.Interfaces.IEnumIDList
    • DevCase.Interop.Unmanaged.Win32.Interfaces.IProgressDialog
    • DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem
    • DevCase.Interop.Unmanaged.Win32.Interfaces.IShellFolder

#### 🚩 New Enums:
    • DevCase.Controls.DevProgressDialogStyle
    • DevCase.Core.Application.UserInterface.VisualStyle
    • DevCase.Interop.Unmanaged.Win32.Enums.ApplicationRestartFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyCreateFileAccess
    • DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyProcessTerminationMethod
    • DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyShowDeveloperDiagnostic
    • DevCase.Interop.Unmanaged.Win32.Enums.AppPolicyThreadInitializationType
    • DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.BackgroundMode
    • DevCase.Interop.Unmanaged.Win32.Enums.BinaryType
    • DevCase.Interop.Unmanaged.Win32.Enums.CodePage
    • DevCase.Interop.Unmanaged.Win32.Enums.CreateMutexFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.CredentialsDialogOptions
    • DevCase.Interop.Unmanaged.Win32.Enums.CredentialsPackFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.DpiAwareness
    • DevCase.Interop.Unmanaged.Win32.Enums.DwmBlurBehindFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.EnumProcessModulesFilter
    • DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemCodePagesFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemLocalesFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.FiberFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.GetMouseMovePointsResolution
    • DevCase.Interop.Unmanaged.Win32.Enums.GetPathFromIdListOption
    • DevCase.Interop.Unmanaged.Win32.Enums.HandleFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.HeapInformationClass
    • DevCase.Interop.Unmanaged.Win32.Enums.IpStatsForwarding
    • DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.KeyboardLayoutFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.MemoryResourceNotificationType
    • DevCase.Interop.Unmanaged.Win32.Enums.MuiLanguageMode
    • DevCase.Interop.Unmanaged.Win32.Enums.MultiByteCharConversionType
    • DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.OpenFolderFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.PathOptions
    • DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass
    • DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.ProgressDialogTimerFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState
    • DevCase.Interop.Unmanaged.Win32.Enums.RegionCombineMode
    • DevCase.Interop.Unmanaged.Win32.Enums.ShellFolderEnumObjectsFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.ShellFoldermGetDisplayName
    • DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask
    • DevCase.Interop.Unmanaged.Win32.Enums.ShellItemCompareFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName
    • DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.SHObjectPropertiesFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.StrFormatByteSizeFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.TokenType
    • DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting
    • DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileType
    • DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileTypeFlags
    • DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType
    • DevCase.Interop.Unmanaged.Win32.Enums.WindowsCredentialsDialogOptions

#### 🌟 Improvements:
    • DevCase.UserControls.dll assembly: All the contents of this assembly were moved to DevCase.Core.dll assembly, under the namespace: DevCase.Controls
    • DevCase.Interop.Unmanaged.Win32.NativeMetods Class: Increased the amount (unmeasurable) of new Win32 functions.
    • DevCase.Core.IO.MemoryStress Class: Added these properties: AvailablePhysicalMemory, AvailableVirtualMemory, TotalPhysicalMemory and TotalVirtualMemory
    • DevCase.Core.IO.MouseButton Enum: Added missing values/support for mouse wheel.
    • DevCase.Core.Shell.Tools.WindowsUtil.MostRecentInstalledFrameworkVersion Property: Updated to support .NET 4.7.1, 4.7.2 and 4.8

# v3.1 🔄

#### 🧰 New Utility Classes:
    • DevCase.Core.Application.UserInterface.ConsoleRectangle
    • DevCase.Core.IO.CpuStress
    • DevCase.Core.IO.DevFileSystemWatcher
    • DevCase.Core.IO.DiskStress
    • DevCase.Core.IO.MemoryStress
    • DevCase.Core.IPC.WindowInfo
    • DevCase.Core.Shell.PreventShutdownContext

#### 🤖 New Methods:
    • DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.ConsoleTextBlink
    • DevCase.Core.Cryptography.Tools.CryptoUtil.ComputeCRC32OfBytes
    • DevCase.Core.Cryptography.Tools.CryptoUtil.ComputeCRC32OfFile
    • DevCase.Core.Cryptography.Tools.CryptoUtil.ComputeCRC32OfString
    • DevCase.Core.Cryptography.Tools.CryptoUtil.ComputeCRC64OfBytes
    • DevCase.Core.Cryptography.Tools.CryptoUtil.ComputeCRC64OfFile
    • DevCase.Core.Cryptography.Tools.CryptoUtil.ComputeCRC64OfString
    • DevCase.Core.IO.Tools.DeviceUtil.GetHardDriveHandle
    • DevCase.Core.IO.Tools.DeviceUtil.GetWin32DiskDrive
    • DevCase.Core.IO.Tools.DeviceUtil.GetWin32LogicalDisk
    • DevCase.Core.IO.Tools.KeyboardUtil.SendKeyAsync
    • DevCase.Core.IPC.Tools.ProcessUtil.GetProcessPerformanceCounter
    • DevCase.Core.IPC.Tools.UIAutomationUtil.EnumerateChildWindows
    • DevCase.Core.IPC.Tools.UIAutomationUtil.EnumerateWindows
    • DevCase.Core.Text.Tools.StringUtil.GenerateLoremIpsumText
    • DevCase.Core.Text.Tools.StringUtil.GenerateRandomParagraph
    • DevCase.Core.Text.Tools.StringUtil.GenerateRandomString
    • DevCase.Interop.Unmanaged.Tools.NativeUtil.GetHiWord
    • DevCase.Interop.Unmanaged.Tools.NativeUtil.GetLoWord

#### 🧩 New Extension Methods:
    • DevCase.Core.Extensions.Action.InvokeRepeat
    • DevCase.Core.Extensions.Bitmap.Center
    • DevCase.Core.Extensions.Bitmap.Stretch
    • DevCase.Core.Extensions.Bitmap.Tile
    • DevCase.Core.Extensions.Bitmap.Zoom
    • DevCase.Core.Extensions.Color.Darken
    • DevCase.Core.Extensions.Color.Lighten
    • DevCase.Core.Extensions.Control.SendKey
    • DevCase.Core.Extensions.DataColumnCollection.AddRange
    • DevCase.Core.Extensions.Decimal.GetDecimalPlaces
    • DevCase.Core.Extensions.DirectoryInfo.CreateZipFile
    • DevCase.Core.Extensions.Double.GetDecimalPlaces
    • DevCase.Core.Extensions.FileInfo.CreateZipFile
    • DevCase.Core.Extensions.FileInfo.ExtractIcon
    • DevCase.Core.Extensions.FileSystemInfo.GetFileHandle
    • DevCase.Core.Extensions.Guid.AsNumber
    • DevCase.Core.Extensions.IDictionary.AddOrGet
    • DevCase.Core.Extensions.IDictionary.ToExpandoObject
    • DevCase.Core.Extensions.IDictionary.ToHashtable
    • DevCase.Core.Extensions.IDictionary.ToNameValueCollection
    • DevCase.Core.Extensions.IDictionary.ToSortedDictionary
    • DevCase.Core.Extensions.IEnumerable.AsReadOnly
    • DevCase.Core.Extensions.Image.Center
    • DevCase.Core.Extensions.Image.Stretch
    • DevCase.Core.Extensions.Image.Tile
    • DevCase.Core.Extensions.Image.Zoom
    • DevCase.Core.Extensions.IWin32Window.PostMessage
    • DevCase.Core.Extensions.IWin32Window.SendKeyAsync
    • DevCase.Core.Extensions.IWin32Window.SendMessage
    • DevCase.Core.Extensions.ListViewGroupCollection.AsEnumerable
    • DevCase.Core.Extensions.ListViewItem.ForEach
    • DevCase.Core.Extensions.ListViewItemCollection.AsEnumerable
    • DevCase.Core.Extensions.ListViewItemCollection.ForEach
    • DevCase.Core.Extensions.Message.ToNativeMessage
    • DevCase.Core.Extensions.Point.ToNativePoint
    • DevCase.Core.Extensions.Rectangle.ToNativeRectangle
    • DevCase.Core.Extensions.Single.GetDecimalPlaces
    • DevCase.Core.Extensions.Size.ToNativeSize
    • DevCase.Core.Extensions.TextFieldParser.ToDataTable
    • DevCase.Core.Extensions.Thread.PostThreadMessage
    • DevCase.Core.Extensions.TreeNodeCollection.AddDirectory
    • DevCase.Core.Extensions.TreeNodeCollection.AddFile
    • DevCase.Core.Extensions.TreeNodeCollection.AsEnumerable
    • DevCase.Core.Extensions.TreeView.EnumerateAllNodes

#### 🌟 Improvements:
    • Reunified all the 3rd party assemblies (DevCase.ThirdParty.{ProductName}.dll) in a single assembly with name: DevCase.ThirdParty.dll.
    • DevCase.Interop.Unmanaged.Win32.NativeMetods Class: Increased the amount (unmeasurable) of new Win32 functions, with their respective structures implementation, interfaces and enums.
