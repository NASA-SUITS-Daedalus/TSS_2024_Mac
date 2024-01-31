# 🦉 TSS 2024 (Mac Version) 🦉

## Requirement
### Browser: 
Chromium browsers: Chrome/Brave
<div>Firefox does not work</div>

### GCC Compiler Installation (Mac): 
1. Install gcc via Homebrew:
```
brew install gcc
```
2. Check gcc version,
```
gcc -v
```

## Running TSS Server
1. Navigate into the directory and build
```
chmod +x build.bat
./build.bat
```
2. Run the server locally (we receive bind() errors if not run locally)
```
./server.exe --local
```
3. Type the IP address printed by the server into a web browser
4. TSS Ready!
