### Android languages: Java vs Kotlin
- Java most popular ever. Goes for: Android, web, server apps, embedded systems
- Kotlin( Jetbrains ). Officially became preferred(chosen by the course)

### Kotlin advantages
- Concise and timesaving. (simpler and fewer lines of code)
- In this case becomes easier to maintain
- Interoperable with Java (could use Java commands inside Kotlin projects )
- With a single click you can convert Java to Kotlin.
- Better addresses common crashes and errors on Android Apps.

### Some of the unique features and characteristics of the Android OS include:
- Near-field communication (NFC)
- Wi-Fi
- Custom home screen
- Widgets
- App downloads
- Custom ROMs (Android customized OS's )

### The Android OS architecture
Android software is built on top of an open-source Linux kernel and many other C or C++ libraries exposed via application framework services.
### DVM (Dalvik Virtual Machine)
Among all the components, the Linux kernel provides the main OS functions for smartphones and the Dalvik Virtual Machine (DVM) provides a platform for running an Android application. An Android OS is a stack of software components roughly divided into five sections:
- ApplicationsApplications Framework
- Android Runtime
- Platform Libraries
- Linux Kernel 


 These are separated into 4 layers, as shown in the architecture diagram below.


![ These are separated into 4 layers, as shown in the architecture diagram below.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/qHi-z6qtQ3y4vs-qrQN8xQ_a0afdd3e0c364406851e2fefe72ce3e1_Picture-1.png?expiry=1683763200000&hmac=jSf10UyhktINjtj0BN_STD3fuNr52EMB2C0w-GbalL4)


### Android Studio: key features
- Complete build system
- Fast emulator
- Develop on different android devices
- Free project templates
- 3rd party integrations

### Project templates
- Basic Activity template (common user interfaces or UI components)
- Bottom Navigation Activity template (Switch between screens with a single tap)
- Empty Activity template (really just empty)
- Project templates will give you a sneak peek at what a particular language or platform has to offer 

### Benefits of project templates
- Amongst other benefits, by previewing what a platform has to offer, project templates give you insight into the development environment before you invest your time in learning how to build your app for that platform.    


- You can start building your app quickly
Project templates can be used to quickly create new app modules, activities or other specific components of your project.      


- Your app will be aligned with specific design principles and coding best practices 
Amongst other benefits, a project template will provide you with a structure that meets the best practices recommended by the operating system (OS) manufacturer.     


### Android App Cheat Sheet: Key Android Development concepts
##### Top Level Component
The ability to connect to the internet, make calls, take pictures and much more is made possible in Android apps with the help of four top-level component classes: **BroadcastReceiver**, **ContentProvider**, **Service and Activity**. These are all accessible in the Android software development kit (**SDK**).

##### Activity Components
Activities present the content users can interact with on the screen. These are the only components that deliver interactive content to the user. An Activity represents something an application can do. Although an application can provide more than one Activity, many developers are following a Single-Activity architecture pattern when creating their apps. This implies that only one Activity or a relatively small number of Activities are used for an entire application.

##### Android Views
In Android, **Views occupy a rectangular area on the screen** and are responsible for drawing and event handling. They can display images, text and more. A combination of all of these Views forms a design interface.

##### Android Layout Files
In Android, each **layout** is represented by an **XML** **file**. These plain text files serve as blueprints for the interface that your application presents to the user. In addition to the XML approach, there are other ways to create a user interface. For example,  interfaces can be created with Android Views entirely in code using Kotlin or Java. Also, Google has created a completely new way of creating Android user interfaces - **Jetpack Compose**. With this library, interfaces are created entirely in** Kotlin code, without XML**.

##### Project Files
Android Project Files belong to one of three main categories: configuration, code and resource. Configuration files define the project structure, code files provide the logic and resource files provide essentially everything else.
