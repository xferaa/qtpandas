# QtPandas

### Utilities to use [pandas](https://github.com/pandas-dev/pandas)  (the data analysis/manipulation library for Python) with Qt.

## Requirements;
> Python 3.4 or greater       
> PyQt5

To use, create a new Python script containing the following:
```
from PyQt5.QtCore import *
from PyQt5.QtWidgets import *

from qtpandas.views.CSVDialogs import CSVImportDialog

if __name__ == "__main__":
    from sys import argv, exit

    app = QApplication(argv)
    dialog = CSVImportDialog()
    dialog.show()
    app.exec_()
```
# Examples

These can be found in QtPandas/examples.

- BasicExmple.py

![basic](images/BasicExample_screen_shot.PNG)

- Here is TestApp.py

![testapp](images/TestApp_screen_shot.PNG)

# Development

## Wanna contribute?
Any feedback is apprecaited.
- Report an issue
- Fork us.

Forked from @datalyze-solutions's [master](https://github.com/datalyze-solutions/pandas-qt).
