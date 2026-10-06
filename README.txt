QR Code Reader (standalone macOS build)

Run from Terminal:
  ./QR_Code_Reader

What is included:
- Pillow opens the selected image and prepares the on-screen preview.
- NumPy passes the image pixels to OpenCV, which detects and decodes QR codes.
- Tcl/Tk provides the graphical interface.
- The Python runtime and required libraries are bundled here.

Keep the executable and the other files together in this folder. Nuitka's
standalone build expects the bundled libraries and runtime files alongside it;
moving them into a subfolder can prevent the program from starting. To share
it, zip this entire QR_Code_Reader folder.

Build details: Apple Silicon (arm64), macOS 26 or later.
