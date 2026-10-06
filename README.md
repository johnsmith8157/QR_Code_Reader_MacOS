# QR Code Reader

A simple macOS app for reading QR codes from image files. It shows the decoded contents and can copy them to the clipboard.

## Download

Open the repository's **Releases** page and download `QR_Code_Reader.zip`. Unzip it, then move **QR_Code_Reader.app** to your Applications folder.

The app is built for Apple Silicon Macs. It does not require Python or OpenCV to be installed separately.

## Open the app

The app is not signed with an Apple Developer ID or notarized, so macOS may block it the first time:

1. In Finder, Control-click **QR_Code_Reader.app** and choose **Open**.
2. Choose **Open** again in the confirmation dialog.

After the first launch, you can open it normally.

## Read a QR code

1. Open QR Code Reader and choose **Choose image…**.
2. Select an image containing one or more QR codes.
3. Read the decoded contents in the window. Choose **Copy contents** to copy them, or **Clear** to start over.

The app supports common image formats, including PNG, JPEG, BMP, WebP, and TIFF. Images are processed on your Mac.
