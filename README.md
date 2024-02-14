mingw64sys
pacman -S gcc-libs
pacman -S mingw-w64-clang-x86_64-libc++
pacman -S git
git clone https://github.com/tianocore/edk2.git
cd edk2
git submodule update --init
git tag
git checkout tags/edk2-stable202311
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
developer command prompt vs 2017

cd "C:\msys64\home\asus\edk2"
edksetup.bat

set PYTHON_HOME="C:\Program Files\Python311"
set PYTHON_HOME="C:\Python27"
C:\msys64\home\asus\edk2\Conf\target.txt (MINGW64 Shell)
=>
ACTIVE_PLATFORM = OvmfPkg/OvmfPkgX64.dsc
TARGET_ARCH = X64
<=

edksetup.bat Rebuild
choco install iasl
C:\ProgramData\chocolatey\lib\iasl\tools\iasl-win-20230628.zip
(unzip)
C:\ASL
build -t VS2019
build -t VS2019 -D ASL_COMPILER_PATH=C:\ASL -D ASL_COMPILER_VERSION=20230628
