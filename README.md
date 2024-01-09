# sixteensrc
i accidentally broke my left testicle

enough joke, its time for the real shit.
this is the original roblox 2016 source from git.rip, which is now seized.
if you dont know what to do, heres the guide:


How to Compile Block Game 2016:
Requirements
The Source 😉
Visual Studio 2015 and 2017 with the necessary build tools. (v140_xp)
DirectX 9
Microsoft Visual C++ Redistributable 2015
Windows 7 SDK
Dependencies used in the source (which will be mentioned in a sec)
A brain and some patients (Compiling does take a lot of time)!
Dependencies
In order to compile you will need some libraries/dependencies to be able to compile.

Boost 1.56.0
cpp-netlib-0.11.0-final
DSBaseClasses (For the record feature in the client)
QT 4.8.5 (for Studio) (won't be included in this guide)
SDK
SDL 2.0.4
Telemetry2SDKWin32_20M
VMProtect 2.13 2 Header Files (For client protection)
w3c-libwww-5.4.0
curl 7.43.0
zlib 1.2.8
VMProtect 2.13 Misc Files (File 1) (File 2) (File 3)
Organizing files and folders
Now before we start compiling anything we have to organize where everything goes.

Create a Folder on your root called "Trunk2012" (It should be like C:\Trunk2012)
Create another folder inside Trunk2012 Called "Contribs"
Create another folder inside Trunk2012 Called "Build"
Put your block game source inside Build folder
Download/Extract all the dependencies
Put boost inside the "Contribs" directory (The path should look like this: C:\Trunk2012\Contribs\boost_1_56_0)
Put C++ netlib dependency inside the "Contribs" directory (The path should look like this: C:\Trunk2012\Contribs\cpp-netlib-0.11.0-final)
Put DSBaseClasses inside the "Contribs" directory (The path should look like this: C:\Trunk2012\Contribs\DSBaseClasses)
Put SDK inside the "Contribs" directory (The path should should look like this: C:\Trunk2012\Contribs\SDK)
Put SDL 2.0.4 inside the "Contribs" directory (The path should look like this: C:\Trunk2012\Contribs\SDL2.0.4)
Duplicate SDL2.0.4 Folder but rename the copy to just "SDL2" (The path should look like this: C:\Trunk2012\Contribs\SDL2)
Put Telemetry inside the "Contribs" directory (The path should look like this: C:\Trunk2012\Contribs\Telemetry) (Inside should be another folder called Telemetry2SDKWin32_20M)
Create a folder inside "Contribs" called "VMProtectWin_2.13" and put the 2 Header files of VM Protect (aka VMP) Inside of "VMProtectWin_2.13".
Put w3c-libwww-5.4.0 dependency inside the "Contribs" directory (The path should look like this: C:\Trunk2012\Contribs\w3c-libwww-5.4.0)
Create a folder in Contribs Called "windows" and another inside "windows" called "x86" and place the zlib and curl dependencies inside there: (It should look like this C:\Trunk2012\windows\x86\curl\curl-7.43.0 and C:\Trunk2012\windows\x86\zlib\zlib-1.2.8) (Note how those dependencies are in nested directories)
Create a folder in Contribs Called "VMP" and put the vmp misc files inside there.
The Contribs folder should look like this:
Contribs Folder
(Ignore the fact that the "VMP" folder is missing from the screenshot)

Setting up the environment
In order for the source to know where to find the depedencies you need to create an environment variable on the system, To do this, Create a system variable with the name "CONTRIB_PATH" and the value being the contrib path (C:\Trunk2012\Contribs)
enter image description here
(In the screenshot it shows just C:\Trunk2012 but ignore that because I put the contribs all in the root of Trunk2012 instead of a dedicated folder called Contribs)

Guide by Yakov.


Disclaimer:
i might get fucked by roblox, so you should get this while u can 😀
theres a fixed version of the source made by hitius but u gotta seek for it 👀

About
the unmodified one

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 27 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Languages
C++
66.4%
 
C
22.5%
 
Objective-C
2.4%
 
Lua
2.4%
 
Java
1.5%
 
HTML
1.3%
 
Other
3.5%
Suggested workflows
Based on your tech stack
MSBuild based projects logo
MSBuild based projects
Build a MSBuild based project.
CMake based, multi-platform projects logo
CMake based, multi-platform projects
Build and test a CMake based project on multiple platforms.
CMake based, single-platform projects logo
CMake based, single-platform projects
Build and test a CMake based project on a single-platform.
More workflows
Footer

fyi this is js hitius without RCE
