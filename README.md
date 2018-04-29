# PYQT Integration

An extension help you coding PYQT form in vsocde. Support "`.ui`" files.

![preview](./imgs/preview.png)

## Explorer context menu

|No.|Name|Description|
|:---:|---|---|
|1|PYQT: New Form|Open designer|
|2|PYQT: Edit In Designer|Open designer with current ui form|
|3|PYQT: Preview|Preview current ui form|
|4|PYQT: Compile Form|Compile current ui form to path defined in "`pyqt-integration.pyuic.compile.filepath`"|

## Properties

|No.|Name|Description|
|:---:|---|---|
|1|`pyqt-integration.qtdesigner.path`|Path of execuable file of qt designer, the extension will ask you to set at the first time it runs, e.g. c:\\\\Users\\\\username\\\\AppData\\\\Local\\\\Programs\\\\Python\\\\Python35\\\\Lib\\\\site-packages\\\\pyqt5-tools\\\\designer.exe|
|2|`pyqt-integration.pyuic.cmd`|"pyuic" command, default "`pyuic5`"|
|3|`pyqt-integration.pyuic.compile.filepath`|Compile file path, relative path as default, switch to absolute path by involving ${workspace}, e.g. \${workspace}\\\\UI\\\\Ui_\${ui_name}.py|

```text
Compile a form will overwite the target py file without confirmation!
```