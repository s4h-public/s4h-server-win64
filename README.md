# win64
build for win 64

1. Be shure:
    path of project is C:\git\s4h-app-server
    path of build is   C:\git\s4h-app-server\build-s4h-app-server-Desktop_Qt_5_15_1_MinGW_64_bit-Release
2. Build project in Qt
3. Run cmd.exe and do next commands:
    cd C:\git\s4h-app-server\build-s4h-app-server-Desktop_Qt_5_15_1_MinGW_64_bit-Release\release
    copy /y s4h-app-server.exe C:\git\s4h-builds\win64
    cd C:\Qt\5.15.1\mingw81_64\bin
    windeployqt --qmldir C:\git\s4h-app-server\project\src C:\git\s4h-builds\win64\s4h-app-server.exe
    cd C:\git\s4h-builds\win64

sdvSbdv