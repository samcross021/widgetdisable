# WidgetDisable
Windows 11 Widget Disabler by Automation Scripts

You can disable Widgets in Windows 11 by using this script.

Internal Working of Script:
1. Dropdown Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft
2. Create New Key named "Dsh" by right-click.
3. Create New DWORD (32-bit) value named "AllowNewsAndInterests" and leave its value in "0".

Warning: This script requires elevated privileges.

After running the script, restart Explorer.exe (or) your computer.
