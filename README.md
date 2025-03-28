

## [msys2](https://www.msys2.org/) install

```bash
pacman -Syu  
pacman -S mingw-w64-x86_64-toolchain mingw-w64-x86_64-cmake  
```

### path?

if you install msys2 in default path, `C:\msys64\mingw64\`  
register `C:\msys64\mingw64\bin` in ENV ARGS, $PATH  

### install another tool by pacman?  

개인적으로 powershell에서 일반적인 개발을 진행하고, 별도 설치가 필요할 때 잠깐 msys64 tty에 들어가는 workflow 선호.  


```bash
C:\\msys64\\usr\\bin\\bash.exe
```


