# Repository
 github
BuildInfo BuildNumber="5769" ProductName="Boot Camp">
    <MsiInfo>
        <ProductManufacturer>Apple Inc.</ProductManufacturer>
        <ProductVersion>5.1.5769</ProductVersion>
        <ProductCode>{FA2B2C2A-EA41-495A-9308-60726125D562}</ProductCode>
        <Component Name="AppleOSSMgr.exe" GUID="*" SharedDLL="yes">
            <File Name="AppleOSSMgr.exe">
                <KeyPath>yes</KeyPath>
                <FileVersion>4.2.0.0</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
                <Name>Build Version</Name>
                <Type>string</Type>
                <Value>[BUILDVERSION]</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
                <Name>VersionNT</Name>
                <Type>string</Type>
                <Value>[VersionNT]</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
                <Name>ModelID</Name>
                <Type>string</Type>
                <Value>[SYSTEMMODELNAME]</Value>
            </Registry>
        </Component>
        <Component Name="AppleTimeSrv.exe" GUID="*" SharedDLL="yes">
            <File Name="AppleTimeSrv.exe">
                <KeyPath>yes</KeyPath>
                <FileVersion>3.0.1.0</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</Key>
                <Name>AppleTime</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
        </Component>
        <Component Name="AppleControlPanel.exe" GUID="*" SharedDLL="yes">
            <File Name="AppleControlPanel.exe">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.8.0</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\explorer\ControlPanel\NameSpace\{4d0f8110-1de4-11dc-8314-0800200c9a66}</Key>
                <Name>null</Name>
                <Type>string</Type>
                <Value>Apple Control Panel</Value>
            </Registry>
            <Registry>
                <Key>HKCR\CLSID\{4d0f8110-1de4-11dc-8314-0800200c9a66}</Key>
                <Name>null</Name>
                <Type>string</Type>
                <Value>Boot Camp</Value>
            </Registry>
            <Registry>
                <Key>HKCR\CLSID\{4d0f8110-1de4-11dc-8314-0800200c9a66}</Key>
                <Name>{305CA226-D286-468e-B848-2B2E8E697B74} 2</Name>
                <Type>integer</Type>
                <Value>5</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</Key>
                <Name>Brightness</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Control Panel\Extended Properties\{305CA226-D286-468e-B848-2B2E8E697B74} 2</Key>
                <Name>%SystemRoot%\system32\Startup Disk.cpl</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\explorer\ControlPanel\NameSpace\{4BCC27C9-EB40-48cd-A331-521888CCE354}</Key>
                <Name>null</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
            <Registry>
                <Key>HKCR\CLSID\{4BCC27C9-EB40-48cd-A331-521888CCE354}</Key>
                <Name>null</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
        </Component>
        <Component Name="EnableS3Registry" GUID="983D6862-F468-48ce-871D-EB221D1A8469" SharedDLL="No">
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\usb</Key>
                <Name>null</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
        </Component>
        <Component Name="WriteiMacKey" GUID="53031B5C-FD64-4A5F-97F5-9FBFF82B6F63" SharedDLL="No">
            <Registry>
                <Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
                <Name>iMac131Parameter</Name>
                <Type>integer</Type>
                <Value>2304</Value>
            </Registry>
        </Component>
        <Component Name="KeyAgent.sys" GUID="*" SharedDLL="No">
            <File Name="KeyAgent.sys">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.1.0</FileVersion>
            </File>
        </Component>
        <Component Name="MacHALDriver.sys" GUID="*" SharedDLL="No">
            <File Name="MacHALDriver.sys">
                <KeyPath>yes</KeyPath>
                <FileVersion>6.200.3.0</FileVersion>
            </File>
        </Component>
        <Component Name="AppleHFS.sys" GUID="*" SharedDLL="yes">
            <File Name="AppleHFS.sys">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.0.0.1</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
                <Name>Type</Name>
                <Type>integer</Type>
                <Value>2</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
                <Name>ErrorControl</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
                <Name>Start</Name>
                <Type>integer</Type>
                <Value>0</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
                <Name>Group</Name>
                <Type>string</Type>
                <Value>File System</Value>
            </Registry>
        </Component>
        <Component Name="AppleMNT.sys" GUID="*" SharedDLL="yes">
            <File Name="AppleMNT.sys">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.0.0.0</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
                <Name>Group</Name>
                <Type>string</Type>
                <Value>System Bus Extender</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
                <Name>Type</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
                <Name>ErrorControl</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
                <Name>Start</Name>
                <Type>integer</Type>
                <Value>0</Value>
            </Registry>
        </Component>
        <Component Name="Bootcamp.exe" GUID="*" SharedDLL="No">
            <File Name="Bootcamp.exe">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.1.0</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</Key>
                <Name>Apple_KbdMgr</Name>
                <Type>string</Type>
                <Value>[#Bootcamp.exe]</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</Key>
                <Name>Set_Hibernation</Name>
                <Type>string</Type>
                <Value>[System64Folder]powercfg.exe /hibernate on</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
                <Name>Old Preload</Name>
                <Type>string</Type>
                <Value>[OLD_KBD_PRELOAD]</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\{C4DC9AAA-64A3-4429-9C37-55D2F6CD7528}</Key>
                <Name>null</Name>
                <Type>null</Type>
                <Value>null</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</Key>
                <Name>Run_VC_Install</Name>
                <Type>string</Type>
                <Value>[TempFolder]vcredist_x64.exe /quiet</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</Key>
                <Name>Run_VC_Remove</Name>
                <Type>string</Type>
                <Value>cmd /c del /Q [TempFolder]vcredist_x64.exe</Value>
            </Registry>
        </Component>
        <Component Name="UTCTime" GUID="*" SharedDLL="No">
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation</Key>
                <Name>RealTimeIsUniversal</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
        </Component>
        <Component Name="HiDPIUserSettings" GUID="*" SharedDLL="No">
            <Registry>
                <Key>HKCU\Control Panel\Desktop</Key>
                <Name>FocusBorderHeight</Name>
                <Type>integer</Type>
                <Value>2</Value>
            </Registry>
            <Registry>
                <Key>HKCU\Control Panel\Desktop</Key>
                <Name>FocusBorderWidth</Name>
                <Type>integer</Type>
                <Value>2</Value>
            </Registry>
            <Registry>
                <Key>HKCU\Control Panel\Desktop</Key>
                <Name>LogPixels</Name>
                <Type>integer</Type>
                <Value>144</Value>
            </Registry>
            <Registry>
                <Key>HKCU\Software\Microsoft\Windows\DWM</Key>
                <Name>UseDpiScaling</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
            <Registry>
                <Key>HKCU\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>Version</Name>
                <Type>string</Type>
                <Value>4,0,0</Value>
            </Registry>
            <Registry>
                <Key>HKCU\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>ComponentID</Name>
                <Type>string</Type>
                <Value>BootCamp_UserKey</Value>
            </Registry>
            <Registry>
                <Key>HKCU\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>IsInstalled</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
        </Component>
        <Component Name="HiDPIHKLMSettings" GUID="*" SharedDLL="No">
            <Registry>
                <Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>StubPath</Name>
                <Type>string</Type>
                <Value>[System64Folder]msiexec.exe /fu {FA2B2C2A-EA41-495A-9308-60726125D562} /qb+</Value>
            </Registry>
            <Registry>
                <Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>Version</Name>
                <Type>string</Type>
                <Value>4,0,0</Value>
            </Registry>
            <Registry>
                <Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>ComponentID</Name>
                <Type>string</Type>
                <Value>BootCamp_UserKey</Value>
            </Registry>
            <Registry>
                <Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
                <Name>IsInstalled</Name>
                <Type>integer</Type>
                <Value>1</Value>
            </Registry>
        </Component>
        <Component Name="BootCamp.Resources_da.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_de.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_en.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.1.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_es.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_fi.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_fr.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_it.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_ja.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_ko.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_nb.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_nl.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_pl.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_pt_PT.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_pt.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_ru.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_sv.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_zh_CN.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_zh_TW.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_ar.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_cs.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_tr.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BootCamp.Resources_hu.lproj_Resources.dll" GUID="*" SharedDLL="No">
            <File Name="Resources.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>5.1.0.0</FileVersion>
            </File>
        </Component>
        <Component Name="BelgiumA.dll" GUID="*" SharedDLL="No">
            <File Name="BelgiumA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_BelgiumA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>BelgiumA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00cd</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>D70C1682E8F24ED4B5B70AAD37B1BA42</Value>
            </Registry>
        </Component>
        <Component Name="BritishA.dll" GUID="*" SharedDLL="No">
            <File Name="BritishA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_BritishA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>BritishA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c0</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>1A4D378083AD454BB4FE02F208614EB6</Value>
            </Registry>
        </Component>
        <Component Name="CanadaA.dll" GUID="*" SharedDLL="No">
            <File Name="CanadaA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_CanadaA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>CanadaA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00ca</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>517A729DDEC543E3A7F392E3F130C25F</Value>
            </Registry>
        </Component>
        <Component Name="DanishA.dll" GUID="*" SharedDLL="No">
            <File Name="DanishA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_DanishA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>DanishA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00cc</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>C3996498F423440FB9CE2732A821E7D9</Value>
            </Registry>
        </Component>
        <Component Name="DutchA.dll" GUID="*" SharedDLL="No">
            <File Name="DutchA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_DutchA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>DutchA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c1</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>3844B95343FB43D68E9695D6E88F016E</Value>
            </Registry>
        </Component>
        <Component Name="FinnishA.dll" GUID="*" SharedDLL="No">
            <File Name="FinnishA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_FinnishA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>FinnishA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00cb</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>ECE9937799D242F5AE0CAA446EDEDC62</Value>
            </Registry>
        </Component>
        <Component Name="FrenchA.dll" GUID="*" SharedDLL="No">
            <File Name="FrenchA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_FrenchA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>FrenchA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c2</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>2ECD3C77364749B18E910F9196B420FA</Value>
            </Registry>
        </Component>
        <Component Name="GermanA.dll" GUID="*" SharedDLL="No">
            <File Name="GermanA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_GermanA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>GermanA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c3</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>B616E2191BF048D4A554E5C6BE224AB4</Value>
            </Registry>
        </Component>
        <Component Name="ItalianA.dll" GUID="*" SharedDLL="No">
            <File Name="ItalianA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_ItalianA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>ItalianA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c4</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>6401AAA6058F431181B445C26BEF22D9</Value>
            </Registry>
        </Component>
        <Component Name="NorwayA.dll" GUID="*" SharedDLL="No">
            <File Name="NorwayA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_NorwayA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>NorwayA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c9</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>74BE397ABD8143E4960D38111394D1A3</Value>
            </Registry>
        </Component>
        <Component Name="PolishA.dll" GUID="*" SharedDLL="No">
            <File Name="PolishA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_PolishA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>PolishA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00cf</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>D3D2841618E34D09ABBCA0DA34A60FAE</Value>
            </Registry>
        </Component>
        <Component Name="PortuguA.dll" GUID="*" SharedDLL="No">
            <File Name="PortuguA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_PortuguA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>PortuguA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00ce</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>326773935C8C4597B0738FE2084D44AD</Value>
            </Registry>
        </Component>
        <Component Name="RussianA.dll" GUID="*" SharedDLL="No">
            <File Name="RussianA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_RussianA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>RussianA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c8</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>B0F62A69BE9446488ED502E800DBC36C</Value>
            </Registry>
        </Component>
        <Component Name="SpanishA.dll" GUID="*" SharedDLL="No">
            <File Name="SpanishA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_SpanishA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>SpanishA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c5</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>C3364C7C44BC444A88A50459135D35B5</Value>
            </Registry>
        </Component>
        <Component Name="SwedishA.dll" GUID="*" SharedDLL="No">
            <File Name="SwedishA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_SwedishA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>SwedishA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c7</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>8CC8067A1BFF4A0FAD38708DE4CD4BF1</Value>
            </Registry>
        </Component>
        <Component Name="SwissA.dll" GUID="*" SharedDLL="No">
            <File Name="SwissA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_SwissA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>SwissA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00c6</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>CE4C7E2419DE400B8A553E1A5C3DCD04</Value>
            </Registry>
        </Component>
        <Component Name="IntlEngA.dll" GUID="*" SharedDLL="No">
            <File Name="IntlEngA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_IntlEngA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>IntlEngA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00d0</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>241A34D0-06DB-405e-8B4E-8CA2FC34D1C7</Value>
            </Registry>
        </Component>
        <Component Name="USA.dll" GUID="*" SharedDLL="No">
            <File Name="USA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_USA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>USA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00d1</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>B422390FE3C04f3a917D15AD1ACD710F</Value>
            </Registry>
        </Component>
        <Component Name="ChinaSA.dll" GUID="BA71FA02-6823-41f5-AE45-7CE7BD063134" SharedDLL="No">
            <File Name="ChinaSA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\00000804</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>ChinaSA.dll</Value>
            </Registry>
        </Component>
        <Component Name="ChinaTA.dll" GUID="9515E71B-681D-45d4-A23C-A3F46FF09606" SharedDLL="No">
            <File Name="ChinaTA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\00000404</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>ChinaTA.dll</Value>
            </Registry>
        </Component>
        <Component Name="TurkeyA.dll" GUID="*" SharedDLL="No">
            <File Name="TurkeyA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_TurkA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>TurkeyA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00d2</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>D1502D2EF02F4e4b8D313D3C0B0457D0</Value>
            </Registry>
        </Component>
        <Component Name="TurkeyQA.dll" GUID="*" SharedDLL="No">
            <File Name="TurkeyQA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_TurkeyQA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>TurkeyQA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00d3</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>2513D09A670B4d9bA8F1BDAAAA32176F</Value>
            </Registry>
        </Component>
        <Component Name="CzechA.dll" GUID="*" SharedDLL="No">
            <File Name="CzechA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_CzechA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>CzechA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00d4</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>0C8DA389245B4792B4960E336F62AC3E</Value>
            </Registry>
        </Component>
        <Component Name="HungaryA.dll" GUID="*" SharedDLL="No">
            <File Name="HungaryA.dll">
                <KeyPath>yes</KeyPath>
                <FileVersion>1.0.3.40</FileVersion>
            </File>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
                <Name>Layout Text</Name>
                <Type>string</Type>
                <Value>!(loc.KBL_HungaryA)</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
                <Name>Layout File</Name>
                <Type>string</Type>
                <Value>HungaryA.dll</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
                <Name>Layout Id</Name>
                <Type>string</Type>
                <Value>00d5</Value>
            </Registry>
            <Registry>
                <Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
                <Name>Layout Component ID</Name>
                <Type>string</Type>
                <Value>725BE97D2AD14042BA539D96030F93AA</Value>
            </Registry>
        </Component>
        <Component Name="BootCampInstallerCache" GUID="1012A1C4-8CAF-44bd-8743-2B667E7632A0" SharedDLL="No">
        </Component></MsiInfo>
    <InfInfo>
        <Apple>
            <Name>Apple USB Ethernet Adapter
                <InfName>AppleUSBEthernet.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> AppleUSBEthernetex.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer> 02/01/2008, 3.8.3.10</DriverVer>
                <ServiceBinary>AppleUSBEthernet.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Apple USB Ethernet Adapter
                <InfName>AppleUSBEthernet.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> AppleUSBEthernetex.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer> 02/01/2008, 3.10.3.10</DriverVer>
                <ServiceBinary>AppleUSBEthernet.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple Built-in Bluetooth
                <InfName>AppleBT.inf</InfName>
                <Class>Bluetooth</Class>
                <ClassGUID>{e0cbf06c-cd8b-4647-bb8a-263b43f0f974}</ClassGUID>
                <CatalogFile>AppleBT.CAT</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer>03/01/2010, 3.0.0.5</DriverVer>
                <ServiceBinary>applebt.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Apple Built-in Bluetooth
                <InfName>AppleBT64.inf</InfName>
                <Class>Bluetooth</Class>
                <ClassGUID>{e0cbf06c-cd8b-4647-bb8a-263b43f0f974}</ClassGUID>
                <CatalogFile>AppleBT64.CAT</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>03/01/2010, 3.0.0.5</DriverVer>
                <ServiceBinary>applebt.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple Broadcom Built-in Bluetooth
                <InfName>AppleBTBC64.inf</InfName>
                <Class>Bluetooth</Class>
                <ClassGUID>{e0cbf06c-cd8b-4647-bb8a-263b43f0f974}</ClassGUID>
                <CatalogFile>AppleBTBC64.CAT</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>01/16/2014, 5.1.0.0</DriverVer>
                <ServiceBinary>AppleBtBc.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>FaceTime HD Camera
                <InfName>AppleCamera64.inf</InfName>
                <Class>Image</Class>
                <ClassGUID>{6bdd1fc6-810f-11d0-bec7-08002be2092f}</ClassGUID>
                <CatalogFile>AppleCamera64.cat ; This file is required and is supplied when the package is certified</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>11/21/2013, 5.0.22.0</DriverVer>
                <ServiceBinary>AppleCamera.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple Display Driver
                <InfName>aaplmonf.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>aaplmonf.cat</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>01/23/2009,3.0.0.0</DriverVer>
                <ServiceBinary>aaplmonf.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Apple Display Driver
                <InfName>aaplmonf64.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>aaplmonf64.cat</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>01/23/2009, 3.0.0.0</DriverVer>
                <ServiceBinary>aaplmonf.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple Null Driver
                <InfName>AppleNull64.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>AppleNull64.cat</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>05/20/2013,5.0.2.0</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple ODD
                <InfName>AppleODD.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>AppleODD.cat</CatalogFile>
                <Provider> "Apple Inc." </Provider>
                <DriverVer>05/17/2010,3.1.0.0</DriverVer>
                <ServiceBinary>AppleODD.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Apple ODD
                <InfName>AppleODD64.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>AppleODD64.cat</CatalogFile>
                <Provider> "Apple Inc." </Provider>
                <DriverVer>05/17/2010,3.1.0.0</DriverVer>
                <ServiceBinary>AppleODD.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>IR Receiver Filter Driver
                <InfName>IRFilter.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>IRFilter.cat</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>02/21/2008,2.0.4.0</DriverVer>
                <ServiceBinary>IRFilter.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>IR Receiver Filter Driver
                <InfName>IRFilter64.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>IRFilter64.cat</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>02/21/2008,2.0.4.0</DriverVer>
                <ServiceBinary>IRFilter.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple SD Card Reader
                <InfName>AppleSDR64.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>AppleSDR64.cat</CatalogFile>
                <Provider> "Apple Inc." </Provider>
                <DriverVer>07/22/2013,1.0.0.1</DriverVer>
                <ServiceBinary>AppleSDR.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name> "Apple Inc." SCSIAdapter Driver
                <InfName>AppleSSD.inf</InfName>
                <Class>SCSIAdapter</Class>
                <ClassGUID>{4D36E97B-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile> AppleSSD.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer>09/26/2013,2.0.2.2</DriverVer>
                <ServiceBinary>AppleSSD.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple Wireless Mouse
                <InfName>AppleBMT.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>applebmt.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer>06/01/2011,4.0.0.1</DriverVer>
                <ServiceBinary>applebmt.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Apple Wireless Mouse
                <InfName>AppleBMT64.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>applebmt64.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer>06/01/2011,4.0.0.1</DriverVer>
                <ServiceBinary>applebmt.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Apple Wireless Trackpad
                <InfName>AppleWTP.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>applewtp.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer>10/29/2011,5.0.0.0</DriverVer>
                <ServiceBinary>applewtp.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Apple Wireless Trackpad
                <InfName>AppleWTP64.inf</InfName>
                <Class>HIDClass</Class>
                <ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
                <CatalogFile>applewtp64.cat</CatalogFile>
                <Provider> "Apple Inc."</Provider>
                <DriverVer>10/29/2011,5.0.0.0</DriverVer>
                <ServiceBinary>applewtp.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
    <Name>System Device
                <InfName>NullSystemDevice64.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>NullSystemDevice64.cat</CatalogFile>
                <Provider>"Apple Inc."</Provider>
                <DriverVer>01/27/2014,5.1.2.0</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
                </Name>
            </Apple>
        <ThirdParty>
            <Name>Fresco Logic xHCI (USB3) Device Driver
                <InfName>FLxHCIc.inf</InfName>
                <Class> USB</Class>
                <ClassGUID> {36fc9e60-c465-11cf-8056-444553540000}</ClassGUID>
                <CatalogFile>FLxHCIc.cat</CatalogFile>
                <Provider>Fresco Logic</Provider>
                <DriverVer>10/09/2013,3.5.104.0</DriverVer>
                <ServiceBinary>FLxHCIc.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Fresco Logic xHCI (USB3) Hub Device Driver
                <InfName>FLxHCIh.inf</InfName>
                <Class> USB</Class>
                <ClassGUID> {36fc9e60-c465-11cf-8056-444553540000}</ClassGUID>
                <CatalogFile>FLxHCIh.cat</CatalogFile>
                <Provider>Fresco Logic</Provider>
                <DriverVer>10/09/2013,3.5.104.0</DriverVer>
                <ServiceBinary>FLxHCIh.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>CS420xLowerFilter
                <InfName>cs420x_46.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>CS420x64.cat</CatalogFile>
                <Provider>"Cirrus Logic, Inc."</Provider>
                <DriverVer>02/14/2014, 6.6001.1.41</DriverVer>
                <ServiceBinary>CS420x64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>CS42xxUpperFilter
                <InfName>cs4208_19.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>CS420x64.cat</CatalogFile>
                <Provider>"Cirrus Logic, Inc."</Provider>
                <DriverVer>04/10/2014, 6.6001.3.19</DriverVer>
                <ServiceBinary>CSUFD.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>AMD Audio Bus Lower Filter
                <InfName>amdkmafd.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>amdkmafd.cat</CatalogFile>
                <Provider>AMD</Provider>
                <DriverVer>09/22/2012, 9.002.0.0000</DriverVer>
                <ServiceBinary>amdkmafd.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Broadcom 802.11 SDIO Network Adapter Driver
                <InfName>bcmwl6.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>BCM43XX64.CAT</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer>05/05/2014, 6.30.224.217</DriverVer>
                <ServiceBinary>bcmwlhighsd5.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Broadcom 802.11 SDIO Network Adapter Driver
                <InfName>bcmwl63.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>BCM43XX64.CAT</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer>05/05/2014, 6.30.224.217</DriverVer>
                <ServiceBinary>bcmwlhighsd5.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Broadcom 802.11 Network Adapter Driver
                <InfName>bcmwl6.inf</InfName>
                <Class>Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>BCM43XX64.CAT</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer>11/13/2012, 5.106.199.1</DriverVer>
                <ServiceBinary>bcmwl5.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>2008s4el.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>2008s4el.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>5000XZVP.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>5000XZVP.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>5400.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>5400.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>852.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>852.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>855.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>855.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>865.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>865.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>915.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>915.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>915M.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>915M.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>945.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>945.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>945GM.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>945GM.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>965g.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>965g.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>965m.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>965m.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>cdvcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cdvcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>CentCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CentCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>CentSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CentSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel Ports Driver
                <InfName>CentURT.inf</InfName>
                <Class>Ports</Class>
                <ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CentURT.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>cougahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>cougcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>cougide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>cougsmb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougsmb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>cougusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>cougusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.0.1036</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>couide2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>couide2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>CrysWell.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CrysWell.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-ahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-ahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>DH89xxCC-cor.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-cor.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-ME.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-ME.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>DH89xxCC-smb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-smb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>DH89xxCC-usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>DH89xxCC-usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>E5100.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>E5100.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>E7220.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>E7220.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>E7230.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>E7230.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>E7300.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>E7300.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>E7520.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>E7520.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>E8500.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>E8500.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ESB2id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ESB2id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ESB2ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ESB2ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ESB2usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ESB2usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>g33q35.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>g33q35.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>Haswell.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>Haswell.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ibexahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ibexcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ibexid2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexid2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ibexide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ibexsmb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexsmb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ibexusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ibexusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ich5core.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich5core.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich5id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich5id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich5ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich5ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ich5usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ich5usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ich6core.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich6core.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich6id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich6id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich6ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich6ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ich6usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ich6usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich78id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich78id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich78ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich78ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ich78usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ich78usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ich7core.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich7core.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ich8core.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich8core.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ich9core.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich9core.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ich9usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ich9usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ichacore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ichacore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ichausb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ichausb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ichXdev.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ichXdev.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IntelCP2.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IntelCP2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IntelCPU.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IntelCPU.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IntelIOH.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IntelIOH.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ioatdma.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ioatdma.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IvyBridg.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IvyBridg.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IvyTown.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IvyTown.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>JakeTown.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>JakeTown.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>JasperFo.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>JasperFo.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxLpAHCI.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpAHCI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxLpCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxLpId2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpId2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxLpIde.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpIde.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel Sensor Driver
                <InfName>LxLpSens.inf</InfName>
                <Class>Sensor</Class>
                <ClassGUID>{5175D334-C371-4806-B3BA-71FD53C9258D}</ClassGUID>
                <CatalogFile>LxLpSens.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxLpSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxLpThrm.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpThrm.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/12/2013, 9.4.0.1022</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxLpUSB.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxLpUSB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxLpUSB3.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxLpUSB3.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxPtAHCI.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtAHCI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxPtCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxPtId2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtId2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxPtIde.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtIde.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxPtSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxPtUSB.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxPtUSB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxPtUSB3.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxPtUSB3.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>NehalMEX.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>NehalMEX.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>PantAHCI.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantAHCI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>PantCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>PantId2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantId2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>PantIDE.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantIDE.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>PantSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>PantUSB.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>PantUSB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.3.0.1030</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>PantUSB3.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantUSB3.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>patahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>patcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>patid2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patid2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>patide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>patsmb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patsmb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>patusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>patusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.3.1033</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>pm45gm45.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>pm45gm45.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>qd3nodrv.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>qd3nodrv.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>SNB2009.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>SNB2009.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>Tcreek.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>Tcreek.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>Tcrkahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>Tcrkahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel SDHost Driver
                <InfName>TcrkSD.inf</InfName>
                <Class>SDHost</Class>
                <ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>TcrkSD.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>tcrkusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>tcrkusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whed_dev.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whed_dev.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whtpI2C.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtpI2C.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whtpI2C2.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtpI2C2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whtpoint.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtpoint.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel SDHost Driver
                <InfName>whtptsd.inf</InfName>
                <Class>SDHost</Class>
                <ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtptsd.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>wptahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>wptahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>wptusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>wptusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>cdvcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cdvcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>CentCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CentCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>CentSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CentSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel Ports Driver
                <InfName>CentURT.inf</InfName>
                <Class>Ports</Class>
                <ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CentURT.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/09/2013, 9.4.0.1021</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>cougahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>cougcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>cougide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>cougsmb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>cougsmb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>cougusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>cougusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.0.1036</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>couide2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>couide2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>CrysWell.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CrysWell.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-ahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-ahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>DH89xxCC-cor.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-cor.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>DH89xxCC-ME.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-ME.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>DH89xxCC-smb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>DH89xxCC-smb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>DH89xxCC-usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>DH89xxCC-usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>Haswell.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>Haswell.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ibexahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ibexcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ibexid2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexid2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ibexide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ibexsmb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ibexsmb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ibexusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ibexusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich78id2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich78id2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>ich78ide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich78ide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>ich78usb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>ich78usb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>ich7core.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>ich7core.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IntelCP2.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IntelCP2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IntelIOH.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IntelIOH.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IvyBridg.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IvyBridg.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>IvyTown.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>IvyTown.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/09/2013, 9.4.0.1021</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>JakeTown.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>JakeTown.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>JasperFo.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>JasperFo.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxLpAHCI.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpAHCI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxLpCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxLpId2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpId2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxLpIde.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpIde.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel Sensor Driver
                <InfName>LxLpSens.inf</InfName>
                <Class>Sensor</Class>
                <ClassGUID>{5175D334-C371-4806-B3BA-71FD53C9258D}</ClassGUID>
                <CatalogFile>LxLpSens.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxLpSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxLpThrm.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxLpThrm.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/12/2013, 9.4.0.1022</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxLpUSB.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxLpUSB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxLpUSB3.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxLpUSB3.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxPtAHCI.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtAHCI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxPtCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxPtId2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtId2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>LxPtIde.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtIde.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>LxPtSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>LxPtSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxPtUSB.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxPtUSB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>LxPtUSB3.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>LxPtUSB3.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>NehalMEX.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>NehalMEX.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>PantAHCI.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantAHCI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>PantCore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantCore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>PantId2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantId2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>PantIDE.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantIDE.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>PantSMB.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantSMB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>PantUSB.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>PantUSB.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.3.0.1030</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>PantUSB3.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>PantUSB3.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>patahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>patcore.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patcore.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>patid2.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patid2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>patide.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patide.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>patsmb.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>patsmb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>patusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>patusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.3.1033</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>SNB2009.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>SNB2009.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>Tcreek.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>Tcreek.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>Tcrkahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>Tcrkahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel SDHost Driver
                <InfName>TcrkSD.inf</InfName>
                <Class>SDHost</Class>
                <ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>TcrkSD.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>tcrkusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>tcrkusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whtpI2C.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtpI2C.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whtpI2C2.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtpI2C2.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel System Driver
                <InfName>whtpoint.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtpoint.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel SDHost Driver
                <InfName>whtptsd.inf</InfName>
                <Class>SDHost</Class>
                <ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>whtptsd.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel hdc Driver
                <InfName>wptahci.inf</InfName>
                <Class>hdc</Class>
                <ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>wptahci.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel USB Driver
                <InfName>wptusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>wptusb.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver
                <InfName>e1e6232.INF</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1e6232.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>03/26/2010,9.13.41.0</DriverVer>
                <ServiceBinary>e1e6232.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver K
                <InfName>e1k6232.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1k6232.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 04/12/2010,11.6.92.0</DriverVer>
                <ServiceBinary>e1k6232.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver Q
                <InfName>e1q6232.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1q6232.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 12/04/2009,11.4.7.0</DriverVer>
                <ServiceBinary>e1q6232.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver R
                <InfName>e1r6232.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1r6232.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 01/07/2010,11.4.16.0</DriverVer>
                <ServiceBinary>e1r6232.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) Gigabit Network Connections Driver
                <InfName>e1y6232.INF</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1y6232.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 04/07/2010,10.1.9.0</DriverVer>
                <ServiceBinary>e1y6232.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver
                <InfName>e1e6232e.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1e6232e.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>03/26/2010,9.13.41.0</DriverVer>
                <ServiceBinary>e1e6232e.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver K
                <InfName>e1k62x64.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1k62x64.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 04/12/2010,11.6.92.0</DriverVer>
                <ServiceBinary>e1k62x64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver Q
                <InfName>e1q62x64.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1q62x64.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 12/04/2009,11.4.7.0</DriverVer>
                <ServiceBinary>e1q62x64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) PRO/1000 PCI Express Network Connection Driver R
                <InfName>e1r62x64.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1r62x64.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 01/07/2010,11.4.16.0</DriverVer>
                <ServiceBinary>e1r62x64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) Gigabit Network Connections Driver
                <InfName>e1y62x64.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> e1y62x64.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer> 04/07/2010,10.1.9.0</DriverVer>
                <ServiceBinary>e1y62x64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Broadcom Simple Communications Device
                <InfName>B57Ports.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> B57Ports.cat</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer> 10/15/2012,1.0.0.3</DriverVer>
                <ServiceBinary>b57ports.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Broadcom Simple Communications Device
                <InfName>B57Ports.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> B57Ports.cat</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer> 10/15/2012,1.0.0.3</DriverVer>
                <ServiceBinary>b57ports.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Broadcom NetXtreme Gigabit Ethernet - NDIS 6.0
                <InfName>b57nd60x.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> b57nd60x.cat</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer> 12/19/2013,16.4.0.2</DriverVer>
                <ServiceBinary>b57nd60x.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Broadcom NetXtreme Gigabit Ethernet - NDIS 6.0
                <InfName>b57nd60a.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile> b57nd60a.cat</CatalogFile>
                <Provider>Broadcom</Provider>
                <DriverVer> 12/19/2013,16.4.0.2</DriverVer>
                <ServiceBinary>b57nd60a.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) Display Audio" 
                <InfName>IntcDAud.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>IntcDAud.cat</CatalogFile>
                <Provider>Intel(R) Corporation</Provider>
                <DriverVer>01/15/2014,6.16.00.3135</DriverVer>
                <ServiceBinary>IntcDAud.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) HD Graphics
                <InfName>igdlh64.inf</InfName>
                <Class>Display</Class>
                <ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>igdlh.cat</CatalogFile>
                <Provider>Intel Corporation</Provider>
                <DriverVer>03/11/2014,10.18.10.3496</DriverVer>
                <ServiceBinary>igdkmd64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) Display Audio" 
                <InfName>IntcDAud.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>IntcDAud.cat</CatalogFile>
                <Provider>Intel(R) Corporation</Provider>
                <DriverVer>06/19/2012,6.14.00.3097</DriverVer>
                <ServiceBinary>IntcDAud.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) HD Graphics
                <InfName>igdlh64.inf</InfName>
                <Class>Display</Class>
                <ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>igdlh.cat</CatalogFile>
                <Provider>Intel Corporation</Provider>
                <DriverVer>10/31/2013,9.17.10.3347</DriverVer>
                <ServiceBinary>igdkmd64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>NVIDIA nForce Ethernet Driver
                <InfName>nvfd6x32.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4D36E972-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile> NVENETFD.CAT</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 02/04/2010, 73.2.8</DriverVer>
                <ServiceBinary>nvmfdx32.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Service for NVIDIA High Definition Audio Driver
                <InfName>nvhda.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>nvhda.cat</CatalogFile>
                <Provider>NVIDIA Corporation</Provider>
                <DriverVer>12/22/2011,1.3.11.1</DriverVer>
                <ServiceBinary>system32\drivers\nvhda64v.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>NVIDIA  System Driver
                <InfName>nvsmbus.inf</InfName>
                <Class> System</Class>
                <ClassGUID> {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile> nvsmb.cat</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 03/22/2010, 4.7.9</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>NVIDIA System Driver
                <InfName>smuc.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318} </ClassGUID>
                <CatalogFile>nvsmu.cat</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 03/22/2010,5.1.2600.0208 ;Changelist 5684924</DriverVer>
                <ServiceBinary>nvsmu.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>NVIDIA nForce Ethernet Driver
                <InfName>nvfd6x64.inf</InfName>
                <Class> Net</Class>
                <ClassGUID> {4D36E972-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile> NVENETFD.CAT</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 02/04/2010, 73.2.8</DriverVer>
                <ServiceBinary>nvmfdx64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Service for NVIDIA High Definition Audio Driver
                <InfName>nvhda.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>nvhda.cat</CatalogFile>
                <Provider>NVIDIA Corporation</Provider>
                <DriverVer>06/16/2013,1.3.26.4</DriverVer>
                <ServiceBinary>system32\drivers\nvhda64v.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>NVIDIA  System Driver
                <InfName>nfsmb64.inf</InfName>
                <Class> System</Class>
                <ClassGUID> {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile> nfsmb64.cat</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 03/22/2010, 4.7.9</DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>NVIDIA System Driver
                <InfName>smuc64.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318} </ClassGUID>
                <CatalogFile>nvsmu64.cat</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 03/22/2010,5.1.2600.0208 ;Changelist 5684924</DriverVer>
                <ServiceBinary>nvsmu.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>NVIDIA  Display Driver
                <InfName>nvao.inf</InfName>
                <Class> Display</Class>
                <ClassGUID> {4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile> nvao.CAT</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer> 12/24/2013, 9.18.13.3228</DriverVer>
                <ServiceBinary>nvlddmkm.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Service for NVIDIA High Definition Audio Driver
                <InfName>nvhda.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>nvhda.cat</CatalogFile>
                <Provider>NVIDIA Corporation</Provider>
                <DriverVer>11/28/2013,1.3.30.1</DriverVer>
                <ServiceBinary>system32\drivers\nvhda64v.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>NVIDIA Stereoscopic 3D USB driver
                <InfName>nvstusb.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>nvstusb.cat</CatalogFile>
                <Provider>NVIDIA</Provider>
                <DriverVer>12/19/2013,6.14.13.3221</DriverVer>
                <ServiceBinary>nvstusb.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>Broadcom Corporation        System Driver
                <InfName>bScsiSDx.inf</InfName>
                <Class>       System</Class>
                <ClassGUID>       {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>bscsisdx.cat</CatalogFile>
                <Provider>Broadcom Corporation</Provider>
                <DriverVer>01/10/2014,1.0.0.256</DriverVer>
                <ServiceBinary>bScsiSDx.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Broadcom Corporation        System Driver
                <InfName>bScsiSDa.inf</InfName>
                <Class>       System</Class>
                <ClassGUID>       {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>bscsisda.cat</CatalogFile>
                <Provider>Broadcom Corporation</Provider>
                <DriverVer>01/10/2014,1.0.0.256</DriverVer>
                <ServiceBinary>bScsiSDa.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>undefined undefined Driver
                <InfName>IntelAMTPP.inf</InfName>
                <Class></Class>
                <ClassGUID></ClassGUID>
                <CatalogFile></CatalogFile>
                <Provider></Provider>
                <DriverVer></DriverVer>
                <ServiceBinary></ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>AMD Audio Bus Lower Filter
                <InfName>amdkmafd.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>amdkmafd.cat</CatalogFile>
                <Provider>AMD</Provider>
                <DriverVer>08/15/2013, 9.002.0.0000</DriverVer>
                <ServiceBinary>amdkmafd.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>AMD PCI Root Bus Lower Filter
                <InfName>amdkmpfd.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>amdkmpfd.cat</CatalogFile>
                <Provider>AMD</Provider>
                <DriverVer>12/12/2013, 13.251.3.0000</DriverVer>
                <ServiceBinary>amdkmpfd.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>AMD PCI Root Bus Lower Filter
                <InfName>amdkmpfd.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>amdkmpfd.cat</CatalogFile>
                <Provider>AMD</Provider>
                <DriverVer>12/12/2013, 13.251.3.0000</DriverVer>
                <ServiceBinary>amdkmpfd.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name> "Advanced Micro Devices, Inc." Display Driver
                <InfName>C7179650.inf</InfName>
                <Class>Display</Class>
                <ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>C7179650.CAT</CatalogFile>
                <Provider> "Advanced Micro Devices, Inc."</Provider>
                <DriverVer>11/01/2014, 14.301.1010.0000</DriverVer>
                <ServiceBinary>atikmdag.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name> "Advanced Micro Devices, Inc." Display Driver
                <InfName>CU179650.inf</InfName>
                <Class>Display</Class>
                <ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
                <CatalogFile>CU179650.CAT</CatalogFile>
                <Provider> "Advanced Micro Devices, Inc."</Provider>
                <DriverVer>11/01/2014, 14.301.1010.0000</DriverVer>
                <ServiceBinary>atikmdag.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name> "Intel(R) Management Engine Interface "
                <InfName>heci.inf</InfName>
                <Class>System</Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>HECI.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>02/25/2013,9.5.0.1393</DriverVer>
                <ServiceBinary>HECIx64.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>Both</isX64>
            </Name>
            <Name>AMD Function Driver for HD Audio Service
                <InfName>atihdw76.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>AtihdW76.cat</CatalogFile>
                <Provider>Advanced Micro Devices</Provider>
                <DriverVer>06/20/2014,7.12.0.7719</DriverVer>
                <ServiceBinary>system32\drivers\AtihdW76.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>AMD Function Driver for HD Audio Service
                <InfName>AtihdWB6.inf</InfName>
                <Class>MEDIA</Class>
                <ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
                <CatalogFile>AtihdWB6.cat</CatalogFile>
                <Provider>Advanced Micro Devices</Provider>
                <DriverVer>02/21/2014,9.0.0.9905</DriverVer>
                <ServiceBinary>system32\drivers\AtihdWB6.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) USB 3.0 Host Controller Switch Driver
                <InfName>iusb3hcs.inf</InfName>
                <Class>System     </Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}     </ClassGUID>
                <CatalogFile>iusb3hcs.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>11/18/2013,2.5.3.34</DriverVer>
                <ServiceBinary>iusb3hcs.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>yes</isX64>
            </Name>
            <Name>Intel(R) USB 3.0 Host Controller Switch Driver
                <InfName>iusb3hcs.inf</InfName>
                <Class>System     </Class>
                <ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}     </ClassGUID>
                <CatalogFile>iusb3hcs.cat</CatalogFile>
                <Provider>Intel</Provider>
                <DriverVer>11/18/2013,2.5.3.34</DriverVer>
                <ServiceBinary>iusb3hcs.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) USB 3.0 Hub Driver
                <InfName>iusb3hub.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>iusb3hub.cat</CatalogFile>
                <Provider>Intel(R) Corporation</Provider>
                <DriverVer>11/18/2013,2.5.3.34</DriverVer>
                <ServiceBinary>iusb3hub.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) USB 3.0 eXtensible Host Controller Driver
                <InfName>iusb3xhc.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>iusb3xhc.cat</CatalogFile>
                <Provider>Intel(R) Corporation</Provider>
                <DriverVer>11/18/2013,2.5.3.34</DriverVer>
                <ServiceBinary>iusb3xhc.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) USB 3.0 Hub Driver
                <InfName>iusb3hub.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>iusb3hub.cat</CatalogFile>
                <Provider>Intel(R) Corporation</Provider>
                <DriverVer>11/18/2013,2.5.3.34</DriverVer>
                <ServiceBinary>iusb3hub.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
            <Name>Intel(R) USB 3.0 eXtensible Host Controller Driver
                <InfName>iusb3xhc.inf</InfName>
                <Class>USB</Class>
                <ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
                <CatalogFile>iusb3xhc.cat</CatalogFile>
                <Provider>Intel(R) Corporation</Provider>
                <DriverVer>11/18/2013,2.5.3.34</DriverVer>
                <ServiceBinary>iusb3xhc.sys</ServiceBinary>
                <HardwareID></HardwareID>
                <isX64>no</isX64>
            </Name>
        </ThirdParty>
    </InfInfo>
    <FileInfo/>
</BuildInfo>
BuildInfo BuildNumber="5769" ProductName="Boot Camp">
	<MsiInfo>
		<ProductManufacturer>Apple Inc.</ProductManufacturer>
		<ProductVersion>5.1.5769</ProductVersion>
		<ProductCode>{FA2B2C2A-EA41-495A-9308-60726125D562}</ProductCode>
		<Component Name="AppleOSSMgr.exe" GUID="*" SharedDLL="yes">
			<File Name="AppleOSSMgr.exe">
				<KeyPath>yes</KeyPath>
				<FileVersion>4.2.0.0</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
				<Name>Build Version</Name>
				<Type>string</Type>
				<Value>[BUILDVERSION]</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
				<Name>VersionNT</Name>
				<Type>string</Type>
				<Value>[VersionNT]</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
				<Name>ModelID</Name>
				<Type>string</Type>
				<Value>[SYSTEMMODELNAME]</Value>
			</Registry>
		</Component>
		<Component Name="AppleTimeSrv.exe" GUID="*" SharedDLL="yes">
			<File Name="AppleTimeSrv.exe">
				<KeyPath>yes</KeyPath>
				<FileVersion>3.0.1.0</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</Key>
				<Name>AppleTime</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
		</Component>
		<Component Name="AppleControlPanel.exe" GUID="*" SharedDLL="yes">
			<File Name="AppleControlPanel.exe">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.8.0</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\explorer\ControlPanel\NameSpace\{4d0f8110-1de4-11dc-8314-0800200c9a66}</Key>
				<Name>null</Name>
				<Type>string</Type>
				<Value>Apple Control Panel</Value>
			</Registry>
			<Registry>
				<Key>HKCR\CLSID\{4d0f8110-1de4-11dc-8314-0800200c9a66}</Key>
				<Name>null</Name>
				<Type>string</Type>
				<Value>Boot Camp</Value>
			</Registry>
			<Registry>
				<Key>HKCR\CLSID\{4d0f8110-1de4-11dc-8314-0800200c9a66}</Key>
				<Name>{305CA226-D286-468e-B848-2B2E8E697B74} 2</Name>
				<Type>integer</Type>
				<Value>5</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</Key>
				<Name>Brightness</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Control Panel\Extended Properties\{305CA226-D286-468e-B848-2B2E8E697B74} 2</Key>
				<Name>%SystemRoot%\system32\Startup Disk.cpl</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\explorer\ControlPanel\NameSpace\{4BCC27C9-EB40-48cd-A331-521888CCE354}</Key>
				<Name>null</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
			<Registry>
				<Key>HKCR\CLSID\{4BCC27C9-EB40-48cd-A331-521888CCE354}</Key>
				<Name>null</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
		</Component>
		<Component Name="EnableS3Registry" GUID="983D6862-F468-48ce-871D-EB221D1A8469" SharedDLL="No">
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\usb</Key>
				<Name>null</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
		</Component>
		<Component Name="WriteiMacKey" GUID="53031B5C-FD64-4A5F-97F5-9FBFF82B6F63" SharedDLL="No">
			<Registry>
				<Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
				<Name>iMac131Parameter</Name>
				<Type>integer</Type>
				<Value>2304</Value>
			</Registry>
		</Component>
		<Component Name="KeyAgent.sys" GUID="*" SharedDLL="No">
			<File Name="KeyAgent.sys">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.1.0</FileVersion>
			</File>
		</Component>
		<Component Name="MacHALDriver.sys" GUID="*" SharedDLL="No">
			<File Name="MacHALDriver.sys">
				<KeyPath>yes</KeyPath>
				<FileVersion>6.200.3.0</FileVersion>
			</File>
		</Component>
		<Component Name="AppleHFS.sys" GUID="*" SharedDLL="yes">
			<File Name="AppleHFS.sys">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.0.0.1</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
				<Name>Type</Name>
				<Type>integer</Type>
				<Value>2</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
				<Name>ErrorControl</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
				<Name>Start</Name>
				<Type>integer</Type>
				<Value>0</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleHFS</Key>
				<Name>Group</Name>
				<Type>string</Type>
				<Value>File System</Value>
			</Registry>
		</Component>
		<Component Name="AppleMNT.sys" GUID="*" SharedDLL="yes">
			<File Name="AppleMNT.sys">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.0.0.0</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
				<Name>Group</Name>
				<Type>string</Type>
				<Value>System Bus Extender</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
				<Name>Type</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
				<Name>ErrorControl</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Services\AppleMNT</Key>
				<Name>Start</Name>
				<Type>integer</Type>
				<Value>0</Value>
			</Registry>
		</Component>
		<Component Name="Bootcamp.exe" GUID="*" SharedDLL="No">
			<File Name="Bootcamp.exe">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.1.0</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run</Key>
				<Name>Apple_KbdMgr</Name>
				<Type>string</Type>
				<Value>[#Bootcamp.exe]</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</Key>
				<Name>Set_Hibernation</Name>
				<Type>string</Type>
				<Value>[System64Folder]powercfg.exe /hibernate on</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Apple Inc.\Boot Camp</Key>
				<Name>Old Preload</Name>
				<Type>string</Type>
				<Value>[OLD_KBD_PRELOAD]</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\{C4DC9AAA-64A3-4429-9C37-55D2F6CD7528}</Key>
				<Name>null</Name>
				<Type>null</Type>
				<Value>null</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</Key>
				<Name>Run_VC_Install</Name>
				<Type>string</Type>
				<Value>[TempFolder]vcredist_x64.exe /quiet</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce</Key>
				<Name>Run_VC_Remove</Name>
				<Type>string</Type>
				<Value>cmd /c del /Q [TempFolder]vcredist_x64.exe</Value>
			</Registry>
		</Component>
		<Component Name="UTCTime" GUID="*" SharedDLL="No">
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation</Key>
				<Name>RealTimeIsUniversal</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
		</Component>
		<Component Name="HiDPIUserSettings" GUID="*" SharedDLL="No">
			<Registry>
				<Key>HKCU\Control Panel\Desktop</Key>
				<Name>FocusBorderHeight</Name>
				<Type>integer</Type>
				<Value>2</Value>
			</Registry>
			<Registry>
				<Key>HKCU\Control Panel\Desktop</Key>
				<Name>FocusBorderWidth</Name>
				<Type>integer</Type>
				<Value>2</Value>
			</Registry>
			<Registry>
				<Key>HKCU\Control Panel\Desktop</Key>
				<Name>LogPixels</Name>
				<Type>integer</Type>
				<Value>144</Value>
			</Registry>
			<Registry>
				<Key>HKCU\Software\Microsoft\Windows\DWM</Key>
				<Name>UseDpiScaling</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
			<Registry>
				<Key>HKCU\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>Version</Name>
				<Type>string</Type>
				<Value>4,0,0</Value>
			</Registry>
			<Registry>
				<Key>HKCU\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>ComponentID</Name>
				<Type>string</Type>
				<Value>BootCamp_UserKey</Value>
			</Registry>
			<Registry>
				<Key>HKCU\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>IsInstalled</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
		</Component>
		<Component Name="HiDPIHKLMSettings" GUID="*" SharedDLL="No">
			<Registry>
				<Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>StubPath</Name>
				<Type>string</Type>
				<Value>[System64Folder]msiexec.exe /fu {FA2B2C2A-EA41-495A-9308-60726125D562} /qb+</Value>
			</Registry>
			<Registry>
				<Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>Version</Name>
				<Type>string</Type>
				<Value>4,0,0</Value>
			</Registry>
			<Registry>
				<Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>ComponentID</Name>
				<Type>string</Type>
				<Value>BootCamp_UserKey</Value>
			</Registry>
			<Registry>
				<Key>HKLM\Software\Microsoft\Active Setup\Installed Components\{81DCEDC9-DC5C-48AF-946A-45C09E8A33F0}</Key>
				<Name>IsInstalled</Name>
				<Type>integer</Type>
				<Value>1</Value>
			</Registry>
		</Component>
		<Component Name="BootCamp.Resources_da.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_de.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_en.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.1.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_es.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_fi.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_fr.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_it.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_ja.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_ko.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_nb.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_nl.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_pl.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_pt_PT.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_pt.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_ru.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_sv.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_zh_CN.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_zh_TW.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_ar.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_cs.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_tr.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BootCamp.Resources_hu.lproj_Resources.dll" GUID="*" SharedDLL="No">
			<File Name="Resources.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>5.1.0.0</FileVersion>
			</File>
		</Component>
		<Component Name="BelgiumA.dll" GUID="*" SharedDLL="No">
			<File Name="BelgiumA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_BelgiumA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>BelgiumA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00cd</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000813</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>D70C1682E8F24ED4B5B70AAD37B1BA42</Value>
			</Registry>
		</Component>
		<Component Name="BritishA.dll" GUID="*" SharedDLL="No">
			<File Name="BritishA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_BritishA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>BritishA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c0</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000809</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>1A4D378083AD454BB4FE02F208614EB6</Value>
			</Registry>
		</Component>
		<Component Name="CanadaA.dll" GUID="*" SharedDLL="No">
			<File Name="CanadaA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_CanadaA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>CanadaA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00ca</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000c0c</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>517A729DDEC543E3A7F392E3F130C25F</Value>
			</Registry>
		</Component>
		<Component Name="DanishA.dll" GUID="*" SharedDLL="No">
			<File Name="DanishA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_DanishA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>DanishA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00cc</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000406</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>C3996498F423440FB9CE2732A821E7D9</Value>
			</Registry>
		</Component>
		<Component Name="DutchA.dll" GUID="*" SharedDLL="No">
			<File Name="DutchA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_DutchA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>DutchA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c1</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000413</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>3844B95343FB43D68E9695D6E88F016E</Value>
			</Registry>
		</Component>
		<Component Name="FinnishA.dll" GUID="*" SharedDLL="No">
			<File Name="FinnishA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_FinnishA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>FinnishA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00cb</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040b</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>ECE9937799D242F5AE0CAA446EDEDC62</Value>
			</Registry>
		</Component>
		<Component Name="FrenchA.dll" GUID="*" SharedDLL="No">
			<File Name="FrenchA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_FrenchA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>FrenchA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c2</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040c</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>2ECD3C77364749B18E910F9196B420FA</Value>
			</Registry>
		</Component>
		<Component Name="GermanA.dll" GUID="*" SharedDLL="No">
			<File Name="GermanA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_GermanA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>GermanA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c3</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000407</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>B616E2191BF048D4A554E5C6BE224AB4</Value>
			</Registry>
		</Component>
		<Component Name="ItalianA.dll" GUID="*" SharedDLL="No">
			<File Name="ItalianA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_ItalianA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>ItalianA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c4</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000410</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>6401AAA6058F431181B445C26BEF22D9</Value>
			</Registry>
		</Component>
		<Component Name="NorwayA.dll" GUID="*" SharedDLL="No">
			<File Name="NorwayA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_NorwayA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>NorwayA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c9</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000414</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>74BE397ABD8143E4960D38111394D1A3</Value>
			</Registry>
		</Component>
		<Component Name="PolishA.dll" GUID="*" SharedDLL="No">
			<File Name="PolishA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_PolishA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>PolishA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00cf</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000415</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>D3D2841618E34D09ABBCA0DA34A60FAE</Value>
			</Registry>
		</Component>
		<Component Name="PortuguA.dll" GUID="*" SharedDLL="No">
			<File Name="PortuguA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_PortuguA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>PortuguA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00ce</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000416</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>326773935C8C4597B0738FE2084D44AD</Value>
			</Registry>
		</Component>
		<Component Name="RussianA.dll" GUID="*" SharedDLL="No">
			<File Name="RussianA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_RussianA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>RussianA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c8</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000419</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>B0F62A69BE9446488ED502E800DBC36C</Value>
			</Registry>
		</Component>
		<Component Name="SpanishA.dll" GUID="*" SharedDLL="No">
			<File Name="SpanishA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_SpanishA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>SpanishA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c5</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040a</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>C3364C7C44BC444A88A50459135D35B5</Value>
			</Registry>
		</Component>
		<Component Name="SwedishA.dll" GUID="*" SharedDLL="No">
			<File Name="SwedishA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_SwedishA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>SwedishA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c7</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041d</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>8CC8067A1BFF4A0FAD38708DE4CD4BF1</Value>
			</Registry>
		</Component>
		<Component Name="SwissA.dll" GUID="*" SharedDLL="No">
			<File Name="SwissA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_SwissA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>SwissA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00c6</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000100c</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>CE4C7E2419DE400B8A553E1A5C3DCD04</Value>
			</Registry>
		</Component>
		<Component Name="IntlEngA.dll" GUID="*" SharedDLL="No">
			<File Name="IntlEngA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_IntlEngA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>IntlEngA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00d0</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0020409</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>241A34D0-06DB-405e-8B4E-8CA2FC34D1C7</Value>
			</Registry>
		</Component>
		<Component Name="USA.dll" GUID="*" SharedDLL="No">
			<File Name="USA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_USA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>USA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00d1</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000409</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>B422390FE3C04f3a917D15AD1ACD710F</Value>
			</Registry>
		</Component>
		<Component Name="ChinaSA.dll" GUID="BA71FA02-6823-41f5-AE45-7CE7BD063134" SharedDLL="No">
			<File Name="ChinaSA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\00000804</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>ChinaSA.dll</Value>
			</Registry>
		</Component>
		<Component Name="ChinaTA.dll" GUID="9515E71B-681D-45d4-A23C-A3F46FF09606" SharedDLL="No">
			<File Name="ChinaTA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\00000404</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>ChinaTA.dll</Value>
			</Registry>
		</Component>
		<Component Name="TurkeyA.dll" GUID="*" SharedDLL="No">
			<File Name="TurkeyA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_TurkA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>TurkeyA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00d2</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a100041f</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>D1502D2EF02F4e4b8D313D3C0B0457D0</Value>
			</Registry>
		</Component>
		<Component Name="TurkeyQA.dll" GUID="*" SharedDLL="No">
			<File Name="TurkeyQA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_TurkeyQA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>TurkeyQA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00d3</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000041f</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>2513D09A670B4d9bA8F1BDAAAA32176F</Value>
			</Registry>
		</Component>
		<Component Name="CzechA.dll" GUID="*" SharedDLL="No">
			<File Name="CzechA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_CzechA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>CzechA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00d4</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a0000405</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>0C8DA389245B4792B4960E336F62AC3E</Value>
			</Registry>
		</Component>
		<Component Name="HungaryA.dll" GUID="*" SharedDLL="No">
			<File Name="HungaryA.dll">
				<KeyPath>yes</KeyPath>
				<FileVersion>1.0.3.40</FileVersion>
			</File>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
				<Name>Layout Text</Name>
				<Type>string</Type>
				<Value>!(loc.KBL_HungaryA)</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
				<Name>Layout File</Name>
				<Type>string</Type>
				<Value>HungaryA.dll</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
				<Name>Layout Id</Name>
				<Type>string</Type>
				<Value>00d5</Value>
			</Registry>
			<Registry>
				<Key>HKLM\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\a000040e</Key>
				<Name>Layout Component ID</Name>
				<Type>string</Type>
				<Value>725BE97D2AD14042BA539D96030F93AA</Value>
			</Registry>
		</Component>
		<Component Name="BootCampInstallerCache" GUID="1012A1C4-8CAF-44bd-8743-2B667E7632A0" SharedDLL="No">
		</Component></MsiInfo>
	<InfInfo>
		<Apple>
			<Name>Apple USB Ethernet Adapter
				<InfName>AppleUSBEthernet.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> AppleUSBEthernetex.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer> 02/01/2008, 3.8.3.10</DriverVer>
				<ServiceBinary>AppleUSBEthernet.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Apple USB Ethernet Adapter
				<InfName>AppleUSBEthernet.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> AppleUSBEthernetex.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer> 02/01/2008, 3.10.3.10</DriverVer>
				<ServiceBinary>AppleUSBEthernet.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple Built-in Bluetooth
				<InfName>AppleBT.inf</InfName>
				<Class>Bluetooth</Class>
				<ClassGUID>{e0cbf06c-cd8b-4647-bb8a-263b43f0f974}</ClassGUID>
				<CatalogFile>AppleBT.CAT</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer>03/01/2010, 3.0.0.5</DriverVer>
				<ServiceBinary>applebt.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Apple Built-in Bluetooth
				<InfName>AppleBT64.inf</InfName>
				<Class>Bluetooth</Class>
				<ClassGUID>{e0cbf06c-cd8b-4647-bb8a-263b43f0f974}</ClassGUID>
				<CatalogFile>AppleBT64.CAT</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>03/01/2010, 3.0.0.5</DriverVer>
				<ServiceBinary>applebt.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple Broadcom Built-in Bluetooth
				<InfName>AppleBTBC64.inf</InfName>
				<Class>Bluetooth</Class>
				<ClassGUID>{e0cbf06c-cd8b-4647-bb8a-263b43f0f974}</ClassGUID>
				<CatalogFile>AppleBTBC64.CAT</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>01/16/2014, 5.1.0.0</DriverVer>
				<ServiceBinary>AppleBtBc.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>FaceTime HD Camera
				<InfName>AppleCamera64.inf</InfName>
				<Class>Image</Class>
				<ClassGUID>{6bdd1fc6-810f-11d0-bec7-08002be2092f}</ClassGUID>
				<CatalogFile>AppleCamera64.cat ; This file is required and is supplied when the package is certified</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>11/21/2013, 5.0.22.0</DriverVer>
				<ServiceBinary>AppleCamera.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple Display Driver
				<InfName>aaplmonf.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>aaplmonf.cat</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>01/23/2009,3.0.0.0</DriverVer>
				<ServiceBinary>aaplmonf.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Apple Display Driver
				<InfName>aaplmonf64.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>aaplmonf64.cat</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>01/23/2009, 3.0.0.0</DriverVer>
				<ServiceBinary>aaplmonf.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple Null Driver
				<InfName>AppleNull64.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>AppleNull64.cat</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>05/20/2013,5.0.2.0</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple ODD
				<InfName>AppleODD.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>AppleODD.cat</CatalogFile>
				<Provider> "Apple Inc." </Provider>
				<DriverVer>05/17/2010,3.1.0.0</DriverVer>
				<ServiceBinary>AppleODD.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Apple ODD
				<InfName>AppleODD64.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>AppleODD64.cat</CatalogFile>
				<Provider> "Apple Inc." </Provider>
				<DriverVer>05/17/2010,3.1.0.0</DriverVer>
				<ServiceBinary>AppleODD.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>IR Receiver Filter Driver
				<InfName>IRFilter.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>IRFilter.cat</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>02/21/2008,2.0.4.0</DriverVer>
				<ServiceBinary>IRFilter.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>IR Receiver Filter Driver
				<InfName>IRFilter64.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>IRFilter64.cat</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>02/21/2008,2.0.4.0</DriverVer>
				<ServiceBinary>IRFilter.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple SD Card Reader
				<InfName>AppleSDR64.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>AppleSDR64.cat</CatalogFile>
				<Provider> "Apple Inc." </Provider>
				<DriverVer>07/22/2013,1.0.0.1</DriverVer>
				<ServiceBinary>AppleSDR.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name> "Apple Inc." SCSIAdapter Driver
				<InfName>AppleSSD.inf</InfName>
				<Class>SCSIAdapter</Class>
				<ClassGUID>{4D36E97B-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile> AppleSSD.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer>09/26/2013,2.0.2.2</DriverVer>
				<ServiceBinary>AppleSSD.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple Wireless Mouse
				<InfName>AppleBMT.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>applebmt.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer>06/01/2011,4.0.0.1</DriverVer>
				<ServiceBinary>applebmt.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Apple Wireless Mouse
				<InfName>AppleBMT64.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>applebmt64.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer>06/01/2011,4.0.0.1</DriverVer>
				<ServiceBinary>applebmt.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Apple Wireless Trackpad
				<InfName>AppleWTP.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>applewtp.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer>10/29/2011,5.0.0.0</DriverVer>
				<ServiceBinary>applewtp.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Apple Wireless Trackpad
				<InfName>AppleWTP64.inf</InfName>
				<Class>HIDClass</Class>
				<ClassGUID>{745a17a0-74d3-11d0-b6fe-00a0c90f57da}</ClassGUID>
				<CatalogFile>applewtp64.cat</CatalogFile>
				<Provider> "Apple Inc."</Provider>
				<DriverVer>10/29/2011,5.0.0.0</DriverVer>
				<ServiceBinary>applewtp.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
	<Name>System Device
				<InfName>NullSystemDevice64.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>NullSystemDevice64.cat</CatalogFile>
				<Provider>"Apple Inc."</Provider>
				<DriverVer>01/27/2014,5.1.2.0</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
				</Name>
			</Apple>
		<ThirdParty>
			<Name>Fresco Logic xHCI (USB3) Device Driver
				<InfName>FLxHCIc.inf</InfName>
				<Class> USB</Class>
				<ClassGUID> {36fc9e60-c465-11cf-8056-444553540000}</ClassGUID>
				<CatalogFile>FLxHCIc.cat</CatalogFile>
				<Provider>Fresco Logic</Provider>
				<DriverVer>10/09/2013,3.5.104.0</DriverVer>
				<ServiceBinary>FLxHCIc.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Fresco Logic xHCI (USB3) Hub Device Driver
				<InfName>FLxHCIh.inf</InfName>
				<Class> USB</Class>
				<ClassGUID> {36fc9e60-c465-11cf-8056-444553540000}</ClassGUID>
				<CatalogFile>FLxHCIh.cat</CatalogFile>
				<Provider>Fresco Logic</Provider>
				<DriverVer>10/09/2013,3.5.104.0</DriverVer>
				<ServiceBinary>FLxHCIh.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>CS420xLowerFilter
				<InfName>cs420x_46.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>CS420x64.cat</CatalogFile>
				<Provider>"Cirrus Logic, Inc."</Provider>
				<DriverVer>02/14/2014, 6.6001.1.41</DriverVer>
				<ServiceBinary>CS420x64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>CS42xxUpperFilter
				<InfName>cs4208_19.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>CS420x64.cat</CatalogFile>
				<Provider>"Cirrus Logic, Inc."</Provider>
				<DriverVer>04/10/2014, 6.6001.3.19</DriverVer>
				<ServiceBinary>CSUFD.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>AMD Audio Bus Lower Filter
				<InfName>amdkmafd.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>amdkmafd.cat</CatalogFile>
				<Provider>AMD</Provider>
				<DriverVer>09/22/2012, 9.002.0.0000</DriverVer>
				<ServiceBinary>amdkmafd.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Broadcom 802.11 SDIO Network Adapter Driver
				<InfName>bcmwl6.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>BCM43XX64.CAT</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer>05/05/2014, 6.30.224.217</DriverVer>
				<ServiceBinary>bcmwlhighsd5.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Broadcom 802.11 SDIO Network Adapter Driver
				<InfName>bcmwl63.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>BCM43XX64.CAT</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer>05/05/2014, 6.30.224.217</DriverVer>
				<ServiceBinary>bcmwlhighsd5.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Broadcom 802.11 Network Adapter Driver
				<InfName>bcmwl6.inf</InfName>
				<Class>Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>BCM43XX64.CAT</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer>11/13/2012, 5.106.199.1</DriverVer>
				<ServiceBinary>bcmwl5.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>2008s4el.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>2008s4el.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>5000XZVP.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>5000XZVP.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>5400.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>5400.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>852.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>852.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>855.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>855.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>865.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>865.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>915.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>915.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>915M.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>915M.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>945.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>945.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>945GM.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>945GM.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>965g.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>965g.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>965m.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>965m.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>cdvcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cdvcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>CentCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CentCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>CentSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CentSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel Ports Driver
				<InfName>CentURT.inf</InfName>
				<Class>Ports</Class>
				<ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CentURT.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>cougahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>cougcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>cougide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>cougsmb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougsmb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>cougusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>cougusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.0.1036</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>couide2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>couide2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>CrysWell.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CrysWell.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-ahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-ahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>DH89xxCC-cor.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-cor.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-ME.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-ME.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>DH89xxCC-smb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-smb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>DH89xxCC-usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>DH89xxCC-usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>E5100.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>E5100.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>E7220.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>E7220.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>E7230.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>E7230.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>E7300.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>E7300.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>E7520.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>E7520.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>E8500.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>E8500.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ESB2id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ESB2id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ESB2ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ESB2ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ESB2usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ESB2usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>g33q35.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>g33q35.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>Haswell.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>Haswell.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ibexahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ibexcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ibexid2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexid2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ibexide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ibexsmb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexsmb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ibexusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ibexusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ich5core.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich5core.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich5id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich5id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich5ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich5ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ich5usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ich5usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ich6core.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich6core.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich6id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich6id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich6ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich6ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ich6usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ich6usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich78id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich78id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich78ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich78ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ich78usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ich78usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ich7core.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich7core.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ich8core.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich8core.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ich9core.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich9core.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ich9usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ich9usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ichacore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ichacore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ichausb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ichausb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ichXdev.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ichXdev.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IntelCP2.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IntelCP2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IntelCPU.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IntelCPU.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IntelIOH.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IntelIOH.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ioatdma.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ioatdma.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IvyBridg.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IvyBridg.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IvyTown.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IvyTown.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>JakeTown.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>JakeTown.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>JasperFo.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>JasperFo.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxLpAHCI.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpAHCI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxLpCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxLpId2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpId2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxLpIde.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpIde.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel Sensor Driver
				<InfName>LxLpSens.inf</InfName>
				<Class>Sensor</Class>
				<ClassGUID>{5175D334-C371-4806-B3BA-71FD53C9258D}</ClassGUID>
				<CatalogFile>LxLpSens.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxLpSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxLpThrm.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpThrm.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/12/2013, 9.4.0.1022</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxLpUSB.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxLpUSB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxLpUSB3.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxLpUSB3.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxPtAHCI.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtAHCI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxPtCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxPtId2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtId2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxPtIde.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtIde.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxPtSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxPtUSB.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxPtUSB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxPtUSB3.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxPtUSB3.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>NehalMEX.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>NehalMEX.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>PantAHCI.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantAHCI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>PantCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>PantId2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantId2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>PantIDE.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantIDE.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>PantSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>PantUSB.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>PantUSB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.3.0.1030</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>PantUSB3.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantUSB3.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>patahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>patcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>patid2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patid2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>patide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>patsmb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patsmb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>patusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>patusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.3.1033</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>pm45gm45.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>pm45gm45.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>qd3nodrv.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>qd3nodrv.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>SNB2009.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>SNB2009.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>Tcreek.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>Tcreek.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>Tcrkahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>Tcrkahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel SDHost Driver
				<InfName>TcrkSD.inf</InfName>
				<Class>SDHost</Class>
				<ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>TcrkSD.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>tcrkusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>tcrkusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whed_dev.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whed_dev.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whtpI2C.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtpI2C.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whtpI2C2.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtpI2C2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whtpoint.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtpoint.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel SDHost Driver
				<InfName>whtptsd.inf</InfName>
				<Class>SDHost</Class>
				<ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtptsd.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>wptahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>wptahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>wptusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>wptusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>cdvcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cdvcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>CentCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CentCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>CentSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CentSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel Ports Driver
				<InfName>CentURT.inf</InfName>
				<Class>Ports</Class>
				<ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CentURT.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/09/2013, 9.4.0.1021</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>cougahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>cougcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>cougide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>cougsmb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>cougsmb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>cougusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>cougusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.0.1036</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>couide2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>couide2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>CrysWell.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CrysWell.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-ahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-ahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>DH89xxCC-cor.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-cor.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>DH89xxCC-ME.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-ME.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>DH89xxCC-smb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>DH89xxCC-smb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>DH89xxCC-usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>DH89xxCC-usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>Haswell.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>Haswell.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ibexahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ibexcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ibexid2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexid2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ibexide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ibexsmb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ibexsmb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ibexusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ibexusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich78id2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich78id2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>ich78ide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich78ide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>ich78usb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>ich78usb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>ich7core.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>ich7core.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IntelCP2.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IntelCP2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IntelIOH.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IntelIOH.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IvyBridg.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IvyBridg.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>IvyTown.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>IvyTown.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/09/2013, 9.4.0.1021</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>JakeTown.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>JakeTown.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>JasperFo.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>JasperFo.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxLpAHCI.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpAHCI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxLpCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxLpId2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpId2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxLpIde.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpIde.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel Sensor Driver
				<InfName>LxLpSens.inf</InfName>
				<Class>Sensor</Class>
				<ClassGUID>{5175D334-C371-4806-B3BA-71FD53C9258D}</ClassGUID>
				<CatalogFile>LxLpSens.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxLpSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxLpThrm.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxLpThrm.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/12/2013, 9.4.0.1022</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxLpUSB.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxLpUSB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxLpUSB3.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxLpUSB3.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxPtAHCI.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtAHCI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxPtCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxPtId2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtId2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>LxPtIde.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtIde.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>LxPtSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>LxPtSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxPtUSB.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxPtUSB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.4.0.1025</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>LxPtUSB3.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>LxPtUSB3.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.4.0.1023</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>NehalMEX.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>NehalMEX.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>PantAHCI.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantAHCI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>PantCore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantCore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>PantId2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantId2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>PantIDE.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantIDE.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>PantSMB.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantSMB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>PantUSB.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>PantUSB.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.3.0.1030</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>PantUSB3.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>PantUSB3.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.3.0.1029</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>patahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>patcore.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patcore.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>patid2.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patid2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>patide.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patide.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>patsmb.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>patsmb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.3.1032</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>patusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>patusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.3.1033</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>SNB2009.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>SNB2009.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.0.1035</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>Tcreek.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>Tcreek.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>Tcrkahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>Tcrkahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel SDHost Driver
				<InfName>TcrkSD.inf</InfName>
				<Class>SDHost</Class>
				<ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>TcrkSD.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.1.9.1005</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>tcrkusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>tcrkusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.1.9.1006</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whtpI2C.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtpI2C.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whtpI2C2.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtpI2C2.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel System Driver
				<InfName>whtpoint.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtpoint.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel SDHost Driver
				<InfName>whtptsd.inf</InfName>
				<Class>SDHost</Class>
				<ClassGUID>{4D36E978-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>whtptsd.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel hdc Driver
				<InfName>wptahci.inf</InfName>
				<Class>hdc</Class>
				<ClassGUID>{4D36E96A-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>wptahci.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/25/2013, 9.2.2.1039</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel USB Driver
				<InfName>wptusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>wptusb.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>07/31/2013, 9.2.2.1040</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver
				<InfName>e1e6232.INF</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1e6232.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>03/26/2010,9.13.41.0</DriverVer>
				<ServiceBinary>e1e6232.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver K
				<InfName>e1k6232.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1k6232.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 04/12/2010,11.6.92.0</DriverVer>
				<ServiceBinary>e1k6232.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver Q
				<InfName>e1q6232.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1q6232.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 12/04/2009,11.4.7.0</DriverVer>
				<ServiceBinary>e1q6232.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver R
				<InfName>e1r6232.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1r6232.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 01/07/2010,11.4.16.0</DriverVer>
				<ServiceBinary>e1r6232.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) Gigabit Network Connections Driver
				<InfName>e1y6232.INF</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1y6232.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 04/07/2010,10.1.9.0</DriverVer>
				<ServiceBinary>e1y6232.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver
				<InfName>e1e6232e.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1e6232e.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>03/26/2010,9.13.41.0</DriverVer>
				<ServiceBinary>e1e6232e.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver K
				<InfName>e1k62x64.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1k62x64.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 04/12/2010,11.6.92.0</DriverVer>
				<ServiceBinary>e1k62x64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver Q
				<InfName>e1q62x64.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1q62x64.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 12/04/2009,11.4.7.0</DriverVer>
				<ServiceBinary>e1q62x64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) PRO/1000 PCI Express Network Connection Driver R
				<InfName>e1r62x64.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1r62x64.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 01/07/2010,11.4.16.0</DriverVer>
				<ServiceBinary>e1r62x64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) Gigabit Network Connections Driver
				<InfName>e1y62x64.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> e1y62x64.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer> 04/07/2010,10.1.9.0</DriverVer>
				<ServiceBinary>e1y62x64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Broadcom Simple Communications Device
				<InfName>B57Ports.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> B57Ports.cat</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer> 10/15/2012,1.0.0.3</DriverVer>
				<ServiceBinary>b57ports.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Broadcom Simple Communications Device
				<InfName>B57Ports.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> B57Ports.cat</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer> 10/15/2012,1.0.0.3</DriverVer>
				<ServiceBinary>b57ports.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Broadcom NetXtreme Gigabit Ethernet - NDIS 6.0
				<InfName>b57nd60x.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> b57nd60x.cat</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer> 12/19/2013,16.4.0.2</DriverVer>
				<ServiceBinary>b57nd60x.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Broadcom NetXtreme Gigabit Ethernet - NDIS 6.0
				<InfName>b57nd60a.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4d36e972-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile> b57nd60a.cat</CatalogFile>
				<Provider>Broadcom</Provider>
				<DriverVer> 12/19/2013,16.4.0.2</DriverVer>
				<ServiceBinary>b57nd60a.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) Display Audio" 
				<InfName>IntcDAud.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>IntcDAud.cat</CatalogFile>
				<Provider>Intel(R) Corporation</Provider>
				<DriverVer>01/15/2014,6.16.00.3135</DriverVer>
				<ServiceBinary>IntcDAud.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) HD Graphics
				<InfName>igdlh64.inf</InfName>
				<Class>Display</Class>
				<ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>igdlh.cat</CatalogFile>
				<Provider>Intel Corporation</Provider>
				<DriverVer>03/11/2014,10.18.10.3496</DriverVer>
				<ServiceBinary>igdkmd64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) Display Audio" 
				<InfName>IntcDAud.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>IntcDAud.cat</CatalogFile>
				<Provider>Intel(R) Corporation</Provider>
				<DriverVer>06/19/2012,6.14.00.3097</DriverVer>
				<ServiceBinary>IntcDAud.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) HD Graphics
				<InfName>igdlh64.inf</InfName>
				<Class>Display</Class>
				<ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>igdlh.cat</CatalogFile>
				<Provider>Intel Corporation</Provider>
				<DriverVer>10/31/2013,9.17.10.3347</DriverVer>
				<ServiceBinary>igdkmd64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>NVIDIA nForce Ethernet Driver
				<InfName>nvfd6x32.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4D36E972-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile> NVENETFD.CAT</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 02/04/2010, 73.2.8</DriverVer>
				<ServiceBinary>nvmfdx32.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Service for NVIDIA High Definition Audio Driver
				<InfName>nvhda.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>nvhda.cat</CatalogFile>
				<Provider>NVIDIA Corporation</Provider>
				<DriverVer>12/22/2011,1.3.11.1</DriverVer>
				<ServiceBinary>system32\drivers\nvhda64v.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>NVIDIA  System Driver
				<InfName>nvsmbus.inf</InfName>
				<Class> System</Class>
				<ClassGUID> {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile> nvsmb.cat</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 03/22/2010, 4.7.9</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>NVIDIA System Driver
				<InfName>smuc.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318} </ClassGUID>
				<CatalogFile>nvsmu.cat</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 03/22/2010,5.1.2600.0208 ;Changelist 5684924</DriverVer>
				<ServiceBinary>nvsmu.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>NVIDIA nForce Ethernet Driver
				<InfName>nvfd6x64.inf</InfName>
				<Class> Net</Class>
				<ClassGUID> {4D36E972-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile> NVENETFD.CAT</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 02/04/2010, 73.2.8</DriverVer>
				<ServiceBinary>nvmfdx64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Service for NVIDIA High Definition Audio Driver
				<InfName>nvhda.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>nvhda.cat</CatalogFile>
				<Provider>NVIDIA Corporation</Provider>
				<DriverVer>06/16/2013,1.3.26.4</DriverVer>
				<ServiceBinary>system32\drivers\nvhda64v.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>NVIDIA  System Driver
				<InfName>nfsmb64.inf</InfName>
				<Class> System</Class>
				<ClassGUID> {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile> nfsmb64.cat</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 03/22/2010, 4.7.9</DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>NVIDIA System Driver
				<InfName>smuc64.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318} </ClassGUID>
				<CatalogFile>nvsmu64.cat</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 03/22/2010,5.1.2600.0208 ;Changelist 5684924</DriverVer>
				<ServiceBinary>nvsmu.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>NVIDIA  Display Driver
				<InfName>nvao.inf</InfName>
				<Class> Display</Class>
				<ClassGUID> {4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile> nvao.CAT</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer> 12/24/2013, 9.18.13.3228</DriverVer>
				<ServiceBinary>nvlddmkm.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Service for NVIDIA High Definition Audio Driver
				<InfName>nvhda.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>nvhda.cat</CatalogFile>
				<Provider>NVIDIA Corporation</Provider>
				<DriverVer>11/28/2013,1.3.30.1</DriverVer>
				<ServiceBinary>system32\drivers\nvhda64v.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>NVIDIA Stereoscopic 3D USB driver
				<InfName>nvstusb.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>nvstusb.cat</CatalogFile>
				<Provider>NVIDIA</Provider>
				<DriverVer>12/19/2013,6.14.13.3221</DriverVer>
				<ServiceBinary>nvstusb.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>Broadcom Corporation        System Driver
				<InfName>bScsiSDx.inf</InfName>
				<Class>       System</Class>
				<ClassGUID>       {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>bscsisdx.cat</CatalogFile>
				<Provider>Broadcom Corporation</Provider>
				<DriverVer>01/10/2014,1.0.0.256</DriverVer>
				<ServiceBinary>bScsiSDx.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Broadcom Corporation        System Driver
				<InfName>bScsiSDa.inf</InfName>
				<Class>       System</Class>
				<ClassGUID>       {4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>bscsisda.cat</CatalogFile>
				<Provider>Broadcom Corporation</Provider>
				<DriverVer>01/10/2014,1.0.0.256</DriverVer>
				<ServiceBinary>bScsiSDa.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>undefined undefined Driver
				<InfName>IntelAMTPP.inf</InfName>
				<Class></Class>
				<ClassGUID></ClassGUID>
				<CatalogFile></CatalogFile>
				<Provider></Provider>
				<DriverVer></DriverVer>
				<ServiceBinary></ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>AMD Audio Bus Lower Filter
				<InfName>amdkmafd.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>amdkmafd.cat</CatalogFile>
				<Provider>AMD</Provider>
				<DriverVer>08/15/2013, 9.002.0.0000</DriverVer>
				<ServiceBinary>amdkmafd.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>AMD PCI Root Bus Lower Filter
				<InfName>amdkmpfd.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>amdkmpfd.cat</CatalogFile>
				<Provider>AMD</Provider>
				<DriverVer>12/12/2013, 13.251.3.0000</DriverVer>
				<ServiceBinary>amdkmpfd.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>AMD PCI Root Bus Lower Filter
				<InfName>amdkmpfd.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4D36E97D-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>amdkmpfd.cat</CatalogFile>
				<Provider>AMD</Provider>
				<DriverVer>12/12/2013, 13.251.3.0000</DriverVer>
				<ServiceBinary>amdkmpfd.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name> "Advanced Micro Devices, Inc." Display Driver
				<InfName>C7179650.inf</InfName>
				<Class>Display</Class>
				<ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>C7179650.CAT</CatalogFile>
				<Provider> "Advanced Micro Devices, Inc."</Provider>
				<DriverVer>11/01/2014, 14.301.1010.0000</DriverVer>
				<ServiceBinary>atikmdag.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name> "Advanced Micro Devices, Inc." Display Driver
				<InfName>CU179650.inf</InfName>
				<Class>Display</Class>
				<ClassGUID>{4D36E968-E325-11CE-BFC1-08002BE10318}</ClassGUID>
				<CatalogFile>CU179650.CAT</CatalogFile>
				<Provider> "Advanced Micro Devices, Inc."</Provider>
				<DriverVer>11/01/2014, 14.301.1010.0000</DriverVer>
				<ServiceBinary>atikmdag.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name> "Intel(R) Management Engine Interface "
				<InfName>heci.inf</InfName>
				<Class>System</Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>HECI.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>02/25/2013,9.5.0.1393</DriverVer>
				<ServiceBinary>HECIx64.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>Both</isX64>
			</Name>
			<Name>AMD Function Driver for HD Audio Service
				<InfName>atihdw76.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>AtihdW76.cat</CatalogFile>
				<Provider>Advanced Micro Devices</Provider>
				<DriverVer>06/20/2014,7.12.0.7719</DriverVer>
				<ServiceBinary>system32\drivers\AtihdW76.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>AMD Function Driver for HD Audio Service
				<InfName>AtihdWB6.inf</InfName>
				<Class>MEDIA</Class>
				<ClassGUID>{4d36e96c-e325-11ce-bfc1-08002be10318}</ClassGUID>
				<CatalogFile>AtihdWB6.cat</CatalogFile>
				<Provider>Advanced Micro Devices</Provider>
				<DriverVer>02/21/2014,9.0.0.9905</DriverVer>
				<ServiceBinary>system32\drivers\AtihdWB6.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) USB 3.0 Host Controller Switch Driver
				<InfName>iusb3hcs.inf</InfName>
				<Class>System     </Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}     </ClassGUID>
				<CatalogFile>iusb3hcs.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>11/18/2013,2.5.3.34</DriverVer>
				<ServiceBinary>iusb3hcs.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>yes</isX64>
			</Name>
			<Name>Intel(R) USB 3.0 Host Controller Switch Driver
				<InfName>iusb3hcs.inf</InfName>
				<Class>System     </Class>
				<ClassGUID>{4d36e97d-e325-11ce-bfc1-08002be10318}     </ClassGUID>
				<CatalogFile>iusb3hcs.cat</CatalogFile>
				<Provider>Intel</Provider>
				<DriverVer>11/18/2013,2.5.3.34</DriverVer>
				<ServiceBinary>iusb3hcs.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) USB 3.0 Hub Driver
				<InfName>iusb3hub.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>iusb3hub.cat</CatalogFile>
				<Provider>Intel(R) Corporation</Provider>
				<DriverVer>11/18/2013,2.5.3.34</DriverVer>
				<ServiceBinary>iusb3hub.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) USB 3.0 eXtensible Host Controller Driver
				<InfName>iusb3xhc.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>iusb3xhc.cat</CatalogFile>
				<Provider>Intel(R) Corporation</Provider>
				<DriverVer>11/18/2013,2.5.3.34</DriverVer>
				<ServiceBinary>iusb3xhc.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) USB 3.0 Hub Driver
				<InfName>iusb3hub.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>iusb3hub.cat</CatalogFile>
				<Provider>Intel(R) Corporation</Provider>
				<DriverVer>11/18/2013,2.5.3.34</DriverVer>
				<ServiceBinary>iusb3hub.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
			<Name>Intel(R) USB 3.0 eXtensible Host Controller Driver
				<InfName>iusb3xhc.inf</InfName>
				<Class>USB</Class>
				<ClassGUID>{36FC9E60-C465-11CF-8056-444553540000}</ClassGUID>
				<CatalogFile>iusb3xhc.cat</CatalogFile>
				<Provider>Intel(R) Corporation</Provider>
				<DriverVer>11/18/2013,2.5.3.34</DriverVer>
				<ServiceBinary>iusb3xhc.sys</ServiceBinary>
				<HardwareID></HardwareID>
				<isX64>no</isX64>
			</Name>
		</ThirdParty>
	</InfInfo>
	<FileInfo/>
</BuildInfo>
