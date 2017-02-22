# darkorange-pyside-stylesheet

This stylesheet has been made by LoneWolf ( http://tech-artists.org/forum/showthread.php?2359-Release-Qt-dark-orange-stylesheet )
<br>I compiled the the images and the stylesheet into a ressource file to make it easier to use.
<br>
<br>Example of use :
<br>
<br>from PySide import QtGui
<br>import darkorange
<br>import sys
<br>
<br>app = QtGui.QApplication(sys.argv)
<br>app.setStyleSheet(darkorange.getStyleSheet())
<br>app.setStyle("plastique")
<br>
<br>win = QtGui.QColorDialog()
<br>win.show()
<br>
<br>app.exec_()
<br>sys.exit()
