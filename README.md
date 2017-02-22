# darkorange-pyside-stylesheet

This stylesheet has been made by LoneWolf ( http://tech-artists.org/forum/showthread.php?2359-Release-Qt-dark-orange-stylesheet )
I compiled the the images and the stylesheet into a ressource file to make it easier to use.

Example of use :

from PySide import QtGui
import darkorange
import sys

app = QtGui.QApplication(sys.argv)
app.setStyleSheet(darkorange.getStyleSheet())
app.setStyle("plastique")

win = QtGui.QColorDialog()
win.show()

app.exec_()
sys.exit()
