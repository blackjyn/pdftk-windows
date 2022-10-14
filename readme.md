# pdftk (Java) Windows executable

This is the executable `pdtfk` version that I build for Windows.
Original source is from Gitlab : <https://gitlab.com/pdftk-java/pdftk>.
They release `.jar` version officially and executable version available for Mac and GNU/Linux but not for Windows.

It seems the original [pdftk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) has no longer updated for so long. The executable file <https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/
pdftk_free-2.02-win-setup.exe> is too old.
Using `curl -sI` I got `Last-Modified: Thu, 01 Aug 2013 20:21:46 GMT` which is almost a decade ago.

Luckily maintained version ported to Java is available so I build it for Windows.


# ENV
- `MSVC 14.28.29910 x64 Host`
- `GraalVM graalvm-svm-java17-windows-gluon-22.0.0.3-Final`

# History
- **14-Oct-22** v3.3.3