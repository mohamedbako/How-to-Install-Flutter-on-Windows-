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


## done
