gcc `wx-config --cxxflags` `wx-config --libs` -c Hello.cpp -o Hello.exe
x86_64-w64-mingw32-g++ `wx-config --cxxflags` `wx-config --libs` -c Hello.cpp -o Hello.exe

x86_64-w64-mingw32-g++ -I/mingw64/lib/wx/include/msw-unicode-static-3.0 -I/mingw64/include/wx-3.0 -D_FILE_OFFSET_BITS=64 -D__WXMSW__ -fpermissive -g -Wall -c Hello.cpp -o Hello.o


x86_64-w64-mingw32-g++ -o Hello.exe Hello.o -static-libgcc -static-libstdc++ -L/mingw64/lib   -pipe -Wl,--subsystem,windows -mwindows /mingw64/lib/libwx_mswu_core-3.0.a /mingw64/lib/libwx_baseu-3.0.a -lwxregexu-3.0 -lwxexpat-3.0 -lwxtiff-3.0 -lwxjpeg-3.0 -lwxpng-3.0 -lwxzlib-3.0 -lrpcrt4 -loleaut32 -lole32 -luuid -llzma -ljbig -lwinspool -lwinmm -lshell32 -lcomctl32 -lcomdlg32 -ladvapi32 -lwsock32 -lgdi32 -loleacc

