All Python QR Code generator

Is basically a fork of this:
http://code.google.com/p/pyqrnative/

**they did all the hard word** - I've just made it easier to use and slightly more flexible. And marginally more Pythonic.

Which is based on these projects:
http://d-project.googlecode.com/svn/trunk/misc/qrcode/js/qrcode.js

Here's how you use it
```
import pyqrcode

qr_image = pyqrcode.MakeQRImage("http://code.google.com/p/pyqrcode/")
qr_image.show()
```

There's options for changing the color scheme, box size, border size, rounding of corners, and encoding quality.
