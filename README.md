# How-to-Install-Flutter-on-Windows-
## System requirements:
- To install and run Flutter, your development environment must meet these minimum requirements:      
- 1-Operating Systems: Windows 10 or later (64-bit), x86-64 based.     
- 2-Disk Space: 1.64 GB (does not include disk space for IDE/tools).



# How to Install Flutter on Windows?


## 1- Download

1- Download **Dart**:

```bash
https://dart.dev/tools/sdk/archive
```  

2- Download **Fultter** (Download the latest version): 

```bash
https://docs.flutter.dev/development/tools/sdk/releases
```
3- Download and Install **Android Studio**: 

```bash
https://developer.android.com/studio
```
    
4- Downlado and Install **JAVA JDK**: 
```bash
https://drive.google.com/file/d/18XvvCPecLmazY-2i_MqbXruKOXM1cs2w/view?usp=share_link
```
    
## 2- Extract And Update Path Variable for Windows PowerShell
### 1- Extract  **Dart** and move it to disk ( C ):
- Go to:` C:\dart(or dart-sdk)\bin`
- Copy the path
- Go to: `PC -> Properties -> Advanced system settings -> Environment variable `
- Click on: `Path -> Edit ->  New -> and Paste (C:\dart(or dart-sdk)\bin)`

### 2- Extract  **Fultter** and move it to disk ( C ):
- Go to: `C:\Fultter\bin`
- Copy the path
- Go to: `PC -> Properties -> Advanced system settings -> Environment variable `
- Click on: `Path -> Edit ->  New -> and Paste (C:\Fultter\bin)`

### 3- Install **JAVA**:
- Go to: `C:\Program Files\Java\jdk1.8.0_241`
- Copy the path
- Go to: `PC -> Properties -> Advanced system settings -> Environment variable `
- Click on: `New -> Give a name and Paste (C:\Program Files\Java\jdk1.8.0_241) `



## 3- Follow in Android Studio

- Open Android Studio
- Go to: `SDK manager`

#### Follow the following steps as shown in the figure



- Choose: `File -> Settings -> Plugins`


## 4- CMD
In CMD, run the the commands below command to confirm the installed tools along with brief descriptions.

```http
  flutter doctor
```

Then run :
```http
flutter doctor --android-licenses
```



```http
Doctor summary (to see all details, run flutter doctor -v):
[√] Flutter (Channel stable, 3.3.6, on Microsoft Windows [Version 10.0.19043.2130], locale en-US)
[√] Android toolchain - develop for Android devices (Android SDK version 33.0.0)
[X] Chrome - develop for the web (Cannot find Chrome executable at .\Google\Chrome\Application\chrome.exe)
    ! Cannot find Chrome. Try setting CHROME_EXECUTABLE to a Chrome executable.
[!] Visual Studio - develop for Windows (Visual Studio Enterprise 2022 17.3.1)
    X Visual Studio is missing necessary components. Please re-run the Visual Studio installer for the "Desktop
      development with C++" workload, and include these components:
        MSVC v142 - VS 2019 C++ x64/x86 build tools
         - If there are multiple build tool versions available, install the latest
        C++ CMake tools for Windows
        Windows 10 SDK
[√] Android Studio (version 2021.2)
[√] VS Code (version 1.72.2)
[√] Connected device (2 available)
[√] HTTP Host Availability

! Doctor found issues in 2 categories.
```

## done
