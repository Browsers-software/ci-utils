This includes binary files for archiving via zip command.

Binary files come from and are here only for easy access via CI script (it's a bit funny they serve zip binary in a zip archive):

https://sourceforge.net/projects/gnuwin32/files/bzip2/1.0.5/bzip2-1.0.5-bin.zip
https://sourceforge.net/projects/gnuwin32/files/zip/3.0/zip-3.0-bin.zip


You can download the binaries from here via

```bash
curl https://raw.githubusercontent.com/Browsers-software/ci-utils/main/zip/bzip2.dll -o bzip2.dll
curl https://raw.githubusercontent.com/Browsers-software/ci-utils/main/zip/zip.exe -o zip.exe
```