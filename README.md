# copy-pytest-command
Basically a mod of https://github.com/asfaltboy/SublimeTestPlier, credit to asfaltboy

Set a keybinding for the command "copy_pytest_command".

Copies a command like so `pytest test_module.py::TestClass::test_method`, based on the position of your cursor. This is all the [work of asfaltboy](https://github.com/asfaltboy/SublimeTestPlier).

My modification is simply copying the pytest command, versus executing it directly, due to complications with my environment and executing commands in a Vagrant VM >_>

Maybe this could turn into a package for customizable copying to clipboard on keypress
