CC= clang
WIN32CC= x86_64-w64-mingw32-g++
SCR= main.cpp
CFLAGS= -v
WIN32CFLAGS= -v
BIN= bin

all: win32 macos

win32: $(SRC)
	$(WIN32CC) $(WIN32CFLAGS) -o åout.exe $(SRC)

macos: $(SRC)
	$(CC) $(CFLAGS) -o out $(SRC)