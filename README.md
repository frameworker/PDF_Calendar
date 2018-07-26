# PDF_Calendar
PDFKit sample

PDF Calendar uses PDF Kit to show you how to generate your own PDF content.

The sample uses a PDFPage subclass to generate a PDFPage from an NSImage. The PDFPage's draw and bounds methods are overridden,  The bounds method will return the image bounds and the draw method displays the image. This PDFPage object can be added to a PDFDocument.

It generates a calendar from images the user supplies. The resulting PDF document can be saved, printed, etc. The sample also incorporates PDFView and PDFThumbnailView.

Revision History

2006-07-31 Version 1.0

2018-07-25 Version 2.0
Brought up-to-date in macOS 10.13.5 with Xcode 9.2
Base SDK 10.13
macOS Deployment Target 10.13
Repaired warnings and updated Deprecated APIs
Added Read Me with Revision History and Eratta

Eratta

"Overridden deprecated methods" warning needs to be turned on and warnings repaired.

Turn on other warnings and fix issues that crop up.
https://github.com/boredzo/Warnings-xcconfig/wiki/Warnings-Explained
