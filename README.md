
developer command prompt vs 2017

cd "C:\msys64\home\asus\edk2"

edksetup.bat

set PYTHON_HOME="C:\Program Files\Python311"
set PYTHON_HOME="C:\Python27"
C:\msys64\home\asus\edk2\Conf\target.txt
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
