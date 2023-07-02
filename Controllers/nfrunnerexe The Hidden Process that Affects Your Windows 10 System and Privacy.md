# How to Fix nfrunnerexe High CPU Usage on Windows 10
 
If you have noticed that your Windows 10 computer is running slower than usual, you may want to check if the nfrunnerexe process is causing high CPU usage. This process is part of the Microsoft Compatibility Telemetry feature, which collects and sends usage and performance data to Microsoft to improve Windows 10. However, some users have reported that this process scans a lot of files on the hard disk and sends a large amount of data over the internet, which can affect the system performance and responsiveness.
 
In this article, we will show you how to fix nfrunnerexe high CPU usage on Windows 10 by disabling the Microsoft Compatibility Telemetry feature. There are three methods you can try:
 
**Download File ↔ [https://t.co/YhSRDoUWWG](https://t.co/YhSRDoUWWG)**


 
1. Disable Application Experience Tasks in Task Scheduler
2. Disable Windows Telemetry via Group Policy Editor
3. Disable Telemetry using Registry

## Method 1: Disable Application Experience Tasks in Task Scheduler
 
The easiest way to disable nfrunnerexe high CPU usage is to disable the Application Experience Tasks in Task Scheduler. These tasks are responsible for collecting program telemetry information if you have opted-in to the Microsoft Customer Experience Improvement Program. To disable them, follow these steps:

- Press Windows + R keys to open the Run dialog box.
- Type taskschd.msc and click OK to open the Task Scheduler.
- Navigate to Task Scheduler Library > Microsoft > Windows > Application Experience.
- Select the Microsoft Compatibility Appraiser task, right-click on it, and choose Disable.
- Repeat the same for the other tasks in the Application Experience folder, such as ProgramDataUpdater and StartupAppTask.
- Close the Task Scheduler and restart your computer.

## Method 2: Disable Windows Telemetry via Group Policy Editor
 
If you have Windows 10 Pro or Enterprise edition, you can use the Group Policy Editor to disable Windows Telemetry and nfrunnerexe high CPU usage. The Group Policy Editor allows you to configure various settings for your computer and network. To disable Windows Telemetry via Group Policy Editor, follow these steps:

- Press Windows + R keys to open the Run dialog box.
- Type gpedit.msc and click OK to open the Group Policy Editor.
- Navigate to Computer Configuration > Administrative Templates > Windows Components > Data Collection and Preview Builds.
- Double-click on Allow Telemetry and select Disabled.
- Click Apply and OK to save the changes.
- Close the Group Policy Editor and restart your computer.

## Method 3: Disable Telemetry using Registry
 
If you have Windows 10 Home edition or you don't have access to the Group Policy Editor, you can use the Registry Editor to disable Windows Telemetry and nfrunnerexe high CPU usage. The Registry Editor allows you to modify the registry entries that store various settings for your computer and applications. However, be careful when using the Registry Editor, as any wrong modification can cause serious problems for your system. To disable Telemetry using Registry, follow these steps:

- Press Windows + R keys to open the Run dialog box.
- Type regedit and click OK to open the Registry Editor.
- Navigate to HKEY\_LOCAL\_MACHINE\SOFTWARE\Policies\Microsoft\Windows\DataCollection.
- If you don't see a DataCollection folder, right-click on the Windows folder, choose New > Key, and name it DataCollection.
- Right-click on the DataCollection folder, choose New > DWORD (32-bit) Value, and name it AllowTelemetry.
- Double-click on AllowTelemetry and set its value data to 0.
- Click OK to save the changes.
- Close the Registry Editor and restart your computer.

We hope this article helped you fix nfrunnerexe high CPU usage on Windows 10 by disabling the Microsoft Compatibility Telemetry feature. If you have any questions or suggestions, feel free to leave a comment below.
 8cf37b1e13
 
