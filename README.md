
<br>developer command prompt vs 2017
<br>
<br>cd "C:\msys64\home\asus\edk2"
<br>
<br>edksetup.bat
<br>
<br>set PYTHON_HOME="C:\Program Files\Python311"
<br>set PYTHON_HOME="C:\Python27"
<br>C:\msys64\home\asus\edk2\Conf\target.txt
<br>=>
<br>ACTIVE_PLATFORM = OvmfPkg/OvmfPkgX64.dsc
<br>TARGET_ARCH = X64
<br><=
<br>
<br>edksetup.bat Rebuild
<br>
<br>choco install iasl
<br>
<br>C:\ProgramData\chocolatey\lib\iasl\tools\iasl-win-20230628.zip
<br>
<br>(unzip)
<br>C:\ASL
<br>
<br>build -t VS2019
<br>
<br>build -t VS2019 -D ASL_COMPILER_PATH=C:\ASL -D ASL_COMPILER_VERSION=20230628
