# How-to-Install-Flutter-on-Windows-
## System requirements:
- To install and run Flutter, your development environment must meet these minimum requirements:      
- 1-Operating Systems: Windows 10 or later (64-bit), x86-64 based.     
- 2-Disk Space: 1.64 GB (does not include disk space for IDE/tools).



# How to Install Flutter on Windows?


## 1- Download

1- Download **Dart**:


[https://dart.dev/tools/sdk/archive](url)

![1](https://user-images.githubusercontent.com/33379873/200084829-b9407bb3-d4cb-4a64-8cf3-e8bb13103f20.png)


2- Download **Fultter** (Download the latest version): 

[https://docs.flutter.dev/development/tools/sdk/releases](url)

![2](https://user-images.githubusercontent.com/33379873/200085027-efbe8e0f-cf56-4c60-b476-fd036a53c0b8.png)

3- Download and Install **Android Studio**: 


[https://developer.android.com/studio](url)
    
4- Downlado and Install **JAVA JDK** (Copy url and paste it in google search): 
```bash
https://drive.google.com/file/d/18XvvCPecLmazY-2i_MqbXruKOXM1cs2w/view?usp=share_link
```
    
## 2- Extract And Update Path Variable for Windows PowerShell
### 1- Extract  **Dart** and move it to disk ( C ):
- Go to:` C:\dart(or dart-sdk)\bin`
- Copy the path
- Go to: `PC -> Properties -> Advanced system settings -> Environment variable `
- Click on: `Path -> Edit ->  New -> and Paste (C:\dart(or dart-sdk)\bin)`


![3](https://user-images.githubusercontent.com/33379873/200085062-248b18ba-adac-4be1-98f8-738098aba2b3.png)


### 2- Extract  **Fultter** and move it to disk ( C ):
- Go to: `C:\Fultter\bin`
- Copy the path
- Go to: `PC -> Properties -> Advanced system settings -> Environment variable `
- Click on: `Path -> Edit ->  New -> and Paste (C:\Fultter\bin)`

![4](https://user-images.githubusercontent.com/33379873/200085086-3545de31-b691-47ba-b6eb-101f283bc5f2.png)


### 3- Install **JAVA**:
- Go to: `C:\Program Files\Java\jdk1.8.0_241`
- Copy the path
- Go to: `PC -> Properties -> Advanced system settings -> Environment variable `
- Click on: `New -> Give a name and Paste (C:\Program Files\Java\jdk1.8.0_241) `


![5](https://user-images.githubusercontent.com/33379873/200085108-9f6c8bfb-6649-4e8a-868a-990cb58729b4.png)

And

![6](https://user-images.githubusercontent.com/33379873/200085148-d9c9bde8-4017-46e1-b008-dc3237de09d6.png)


## 3- Follow in Android Studio

- Open Android Studio
- Go to: `SDK manager`

![7](https://user-images.githubusercontent.com/33379873/200085173-094a3083-ed22-471f-8c30-2989aaee1667.png)

#### Follow the following steps as shown in the figure

![8](https://user-images.githubusercontent.com/33379873/200085200-56e139c3-cbdf-4c59-888f-ee8bdd452e8b.png)
![9](https://user-images.githubusercontent.com/33379873/200085206-3cd1fc5d-1641-42c4-b49f-cfe3aff1c37d.png)
![10](https://user-images.githubusercontent.com/33379873/200085208-bc955fbc-10d5-4401-bd8b-c6ddfcd699f0.png)

- Copy Android SDK Location and following steps as shown in the figure:

![11-1](https://user-images.githubusercontent.com/33379873/200086067-2eb399e7-788d-43f6-838c-0b2306ba0d23.png)
![11](https://user-images.githubusercontent.com/33379873/200086138-fd815be4-b0d4-45f5-9345-2e8966a6b1e0.png)
![12](https://user-images.githubusercontent.com/33379873/200086141-3aa7dda3-5880-4138-b0ed-cdd480cc77e0.png)


- Now choose: `File -> Settings -> Plugins`


## 4- CMD
In CMD, run the the commands below command to confirm the installed tools along with brief descriptions.


```http
  flutter doctor
```

Then run :
```http
flutter doctor --android-licenses
```

Agine run:
```http
  flutter doctor
```

### You will get

![14](https://user-images.githubusercontent.com/33379873/200086210-7b0d9ce4-35f7-4331-b2e4-f83c376e3188.png)


## done
