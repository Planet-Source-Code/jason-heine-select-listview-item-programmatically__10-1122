<div align="center">

## Select ListView Item Programmatically


</div>

### Description

This simple code will allow you to programmatically select an item in a listview. Hope this helps.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jason Heine](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jason-heine.md)
**Level**          |Beginner
**User Rating**    |4.7 (203 globes from 43 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jason-heine-select-listview-item-programmatically__10-1122/archive/master.zip)





### Source Code

<html>
	<head>
		<title></title>
		<meta name="GENERATOR" content="Microsoft Visual Studio.NET 7.0">
		<meta name="vs_targetSchema" content="http://schemas.microsoft.com/intellisense/ie5">
	</head>
		<P><STRONG><FONT color="#990000">How to select a ListView Item Programmatically.</FONT></STRONG></P>
		<P>&nbsp;</P>
		<P><FONT color="#990000">This is a simple process, but most people forget a little step
				in doing this.</FONT></P>
		<P><FONT color="#000099" size="4"><STRONG>Step 1:</STRONG></FONT></P>
		<P><STRONG><FONT color="#000099" size="4">Create a ListView Item and name it to whatever
					you wish. I will use <FONT color="#ff0000">lv</FONT> for simplicity.</FONT></STRONG></P>
		<P><STRONG><FONT color="#000099" size="4">Step 2:</FONT></STRONG></P>
		<P><STRONG><FONT color="#000099" size="4">Create a Button Item </FONT></STRONG>
		</P>
		<P><STRONG><FONT color="#000099" size="4">Step 3:</FONT></STRONG></P>
		<P><STRONG><FONT color="#000099" size="4">Double Click the Button to start typeing code.</FONT></STRONG></P>
		<P><STRONG><FONT color="#000099" size="4"></FONT></STRONG>&nbsp;</P>
		<P><STRONG><FONT color="#000099" size="4">Step 4:</FONT></STRONG></P>
		<P><FONT color="#993399">Enter the following code:</FONT></P>
		<P><FONT color="#0066ff">Private Sub Button1_Click(......) Handles Button1.Click</FONT></P>
		<P><FONT color="#990033">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; lv.Items(0).Selected = True</FONT></P>
		<P><FONT color="#990033">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; lv.Select() </FONT><FONT color="#009900">
				'This is what most people forget. If you don't put this in here, it will never
				select the item in the list view.</FONT></P>
		<P><FONT color="#0066ff">End Sub</FONT></P>
		<P><FONT color="#0066ff"><STRONG>And that is it! Really Really simple, but very useful.</STRONG></FONT></P>
		<P><FONT color="#0066ff"></FONT>&nbsp;</P>
		<P><STRONG><FONT color="#000099">Step 5:</FONT></STRONG></P>
		<P><STRONG><FONT color="#000099">If you find this code useful. Vote for me. </FONT></STRONG>
		</P>
</html>

