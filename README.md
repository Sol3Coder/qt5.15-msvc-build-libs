# qt5.15-msvc-build-libs
windows msvc build for qt5.15.10

# ATTENTION
 no qtwebengine,qtwebview,qtserialport,openssl, examples,tools,tests,docs !!!

my configure:

```
mkdir build
cd build
..\configure  -opensource -confirm-license -qt-sqlite -qt-pcre -qt-zlib -qt-libpng -qt-libjpeg -qt-freetype -qt-harfbuzz -opengl dynamic -platform win32-msvc -combined-angle-lib -no-feature-d3d12 -skip qtwebengine -skip qtwebview -skip qtserialport -nomake tests -nomake examples -mp -release -optimize-size -strip -no-openssl
```
