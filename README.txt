needs directx9 2010 sdk https://www.microsoft.com/en-us/download/details.aspx?id=6812
relies on custom https://github.com/Zer0Mem0ry/Detour.git one from there will cause not to find function (dllmain.cpp@58 line)
and included in project: 
"Severity	Code	Description	Project	File	Line	Suppression State
Error	MSB6006	"link.exe" exited with code 1181.	superhuman	C:\Program Files\Microsoft Visual Studio\2022\Community\MSBuild\Microsoft\VC\v170\Microsoft.CppCommon.targets	1092	
Error	LNK1181	cannot open input file 'detours.lib'	superhuman	C:\GitHub\superhuman-swine\LINK	1	
"

and its not x64, so no d3d9 or pch.h