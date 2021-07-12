### Java Code Styles
====================

IntelliJ IDEA code style settings for Square's Java and Android projects.


Installation
------------

 * On Unix, run the `install.sh` script. Windows users should use `install.bat` instead.
 * Restart IntelliJ if it's running.
 * Open IntelliJ Project Settings -> Code Styles, change the code style for the
   project to the one you want.

Inspection
<?xml version="1.0" encoding="UTF-8"?>
<inspections version="1.0" is_locked="false">
  <option name="myName" value="Square" />
  <inspection_tool class="FallthruInSwitchStatement" enabled="true" level="ERROR" enabled_by_default="true" />
  <inspection_tool class="UnnecessarySemicolon" enabled="true" level="ERROR" enabled_by_default="true" />
</inspections>
License
-------

[![Public domain](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/legalcode)
