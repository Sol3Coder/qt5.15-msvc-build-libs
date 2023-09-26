# qt_5_15_10_msvc
windows msvc2022 build for qt5.15.10

# ATTENTION
 no qtwebengine,qtwebview,qtserialport,openssl!!!

my configure:

```
..\configure  -opensource -confirm-license -qt-sqlite -qt-pcre -qt-zlib -qt-libpng -qt-libjpeg -qt-freetype -qt-harfbuzz -opengl dynamic -platform win32-msvc -combined-angle-lib -no-feature-d3d12 -skip qtwebengine -skip qtwebview -skip qtserialport -nomake tests -nomake examples -mp -release -optimize-size -strip -no-openssl
```
