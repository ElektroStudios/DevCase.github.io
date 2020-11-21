# MCICommands Enumeration
 

Specifies a command message to use with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MciSendCommand">MciSendCommand(Int32, MCICommands, IntPtr, MciOpenParms)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MCICommands
```

**VB**<br />
``` VB
Public Enumeration MCICommands
```

**VB Usage**<br />
``` VB Usage
Dim instance As MCICommands
```

**C++**<br />
``` C++
public enum class MCICommands
```

**F#**<br />
``` F#
type MCICommands
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Break">**Break**</td><td>2065</td><td>Sets a break key for an MCI device. 

 MCI supports this command directly rather than passing it to the device. Any MCI application can use this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Capture">**Capture**</td><td>2160</td><td>Captures the contents of the frame buffer and stores it in a specified file. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Close">**Close**</td><td>2052</td><td>Releases access to a device or file. All devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Configure">**Configure**</td><td>2170</td><td>Displays a dialog box for setting the operating options. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Copy">**Copy**</td><td>2130</td><td>Copies data to the clipboard. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Cue">**Cue**</td><td>2096</td><td>Cues a device so that playback or recording begins with minimum delay. Digital-video, VCR, and waveform-audio devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Cut">**Cut**</td><td>2129</td><td>Removes data from the file and copies it to the clipboard. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Delete">**Delete**</td><td>2134</td><td>Removes data from the file. Digital-video and waveform-audio devices recognize this command..</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Escape">**Escape**</td><td>2053</td><td>Sends a string directly to the device. Videodisc devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Freeze">**Freeze**</td><td>2116</td><td>Freezes motion on the display. Digital-video, video-overlay, and VCR devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.GetDevCaps">**GetDevCaps**</td><td>2059</td><td>Retrieves static information about a device. All devices recognize this command. The parameters and flags available for this command depend on the selected device. Information is returned in the dwReturn member of the structure identified by lpCapsParms.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Info">**Info**</td><td>2058</td><td>Retrieves string information from a device. All devices recognize this command. Information is returned in the lpstrReturn member of the structure identified by lpInfo. The dwRetSize member specifies the buffer length for the returned data.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.List">**List**</td><td>2168</td><td>Obtains information about the number and types of inputs available to the device. Digital-video and VCR devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Load">**Load**</td><td>2128</td><td>Loads a file. Digital-video and video-overlay devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Monitor">**Monitor**</td><td>2161</td><td>Specifies the presentation source. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Open">**Open**</td><td>2051</td><td>Initializes a device or file. All devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Paste">**Paste**</td><td>2131</td><td>Pastes data from the clipboard into a file. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Pause">**Pause**</td><td>2057</td><td>Pauses the current action. CD audio, digital-video, MIDI sequencer, VCR, videodisc, and waveform-audio devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Play">**Play**</td><td>2054</td><td>Signals the device to begin transmitting output data. CD audio, digital-video, MIDI sequencer, videodisc, VCR, and waveform-audio devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Put">**Put**</td><td>2114</td><td>Sets the source, destination, and frame rectangles. Digital-video and video-overlay devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Quality">**Quality**</td><td>2167</td><td>Defines a custom quality level for audio, video, or still image data compression. Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Realize">**Realize**</td><td>2112</td><td>Causes a graphic device to realize its palette into a device context (DC). Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Record">**Record**</td><td>2063</td><td>Starts recording from the current position or from one specified location to another specified location. 

 VCR and waveform-audio devices recognize this command. 

 Although digital-video devices and MIDI sequencers also recognize this command, the MCIAVI and MCISEQ drivers do not implement it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Reserve">**Reserve**</td><td>2162</td><td>Allocates contiguous disk space for the workspace of the device driver instance for use with subsequent recording. Digital-video devices recognize this command..</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Restore">**Restore**</td><td>2171</td><td>Copies a bitmap from a file to the frame buffer. Digital-video devices recognize this command. This command performs the opposite action of the Capture command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Resume">**Resume**</td><td>2133</td><td>Causes a paused device to resume the paused operation. Digital-video, VCR, and waveform-audio devices recognize this command. 

 Although CD audio, MIDI sequencer, and videodisc devices also recognize this command, the MCICDA, MCISEQ, and MCIPIONR device drivers do not support it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Save">**Save**</td><td>2067</td><td>Saves the current file. 

 Devices that modify files should not destroy the original copy until they receive the save message. 

 Video-overlay and waveform-audio devices recognize this command. 

 Although digital-video devices and MIDI sequencers also recognize this command, the MCIAVI and MCISEQ drivers do not implement it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Seek">**Seek**</td><td>2055</td><td>Changes the current position in the content as quickly as possible. Video and audio output are disabled during the seek. After the seek is complete, the device is stopped. CD audio, digital-video, MIDI sequencer, VCR, videodisc, and waveform-audio devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Set">**Set**</td><td>2061</td><td>Sets device information. CD audio, digital-video, MIDI sequencer, VCR, videodisc, video-overlay, and waveform-audio devices recognize this command..</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.SetAudio">**SetAudio**</td><td>2163</td><td>Sets values associated with audio playback and capture. Digital-video and VCR devices recognize this command..</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.SetVideo">**SetVideo**</td><td>2166</td><td>Sets values associated with video playback. Digital-video and VCR devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Signal">**Signal**</td><td>2165</td><td>Sets a specified position in the workspace. Digital-video devices recognize this command. MCIAVI supports only one active signal at a time.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Spin">**Spin**</td><td>2060</td><td>Starts the device spinning up or down. 

 Videodisc devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Status">**Status**</td><td>2068</td><td>Retrieves information about an MCI device. 

 All devices recognize this command. Information is returned in the dwReturn member of the structure identified by the status parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Step">**Step**</td><td>2062</td><td>Steps the player one or more frames. 

 Digital-video, VCR, and CAV-format videodisc devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Stop">**Stop**</td><td>2056</td><td>Stops all play and record sequences, unloads all play buffers, and ceases display of video images. 

 CD audio, digital-video, MIDI sequencer, videodisc, VCR, and waveform-audio devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.SysInfo">**SysInfo**</td><td>2064</td><td>Retrieves information about MCI devices. MCI supports this command directly rather than passing it to the device. Any MCI application can use this command. 

 String information is returned in the application-supplied buffer pointed to by the l pstrReturn member of the structure identified by lpSysInfo. 

 Numeric information is returned as a DWORD value placed in the application-supplied buffer. The dwRetSize member specifies the buffer length.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Undo">**Undo**</td><td>2169</td><td>Reverses the most recent successful Cut, Copy, Delete, or Paste command. 

 Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Unfreeze">**Unfreeze**</td><td>2117</td><td>Restores motion to an area of the video buffer frozen with the Freeze command. 

 Digital-video, VCR, and video-overlay devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Update">**Update**</td><td>2132</td><td>Updates the display rectangle. 

 Digital-video devices recognize this command.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Where">**Where**</td><td>2115</td><td>obtains the clipping rectangle for the video device. Digital-video, and video-overlay devices recognize this command. 

 The top and left members of the returned RECT contain the origin of the clipping rectangle, and the right and bottom members contain the width and height of the clipping rectangle. (This is not the standard use of the right and bottom members.)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MCICommands.Window">**Window**</td><td>2113</td><td>specifies the window and the window characteristics for graphic devices. 

 Digital-video, and video-overlay devices recognize this command.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd743571(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd743571(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />