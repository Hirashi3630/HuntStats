[![Build Passing](https://img.shields.io/github/workflow/status/zaxiure/huntstats/.NET?style=for-the-badge)](https://github.com/Zaxiure/HuntStats/blob/master/.github/workflows/dotnet.yml)
[![HuntStats Current Version](https://img.shields.io/github/v/release/zaxiure/huntstats?style=for-the-badge)](https://github.com/Zaxiure/HuntStats/releases/latest)
[![Github Downloads](https://img.shields.io/github/downloads/zaxiure/huntstats/total?style=for-the-badge)](https://github.com/Zaxiure/HuntStats/releases)
# HuntStats

This is a simple application that reads and saves the XML file generated by Hunt: Showdown, essentially creating a way for you to keep track of all your matches and analyse the graphs. This application saves everything in a .sqlite file found in `%appdata%/HuntStats`. If you experience any issues with the application this file **might** be needed to debug.

A thanks to everyone in **The Rat's Nest** discord for testing my application and for the suggestions, without them I most likely wouldn't even have made this application in the first place. Feel free to join their [discord](https://discord.gg/vd5v5ua4Zr). I'll be hanging around over there :)


**WARNING: _Might be very confronting_**

# Running HuntStats

The ZIP in the release contains the whole application, so the only thing needed to do is put it somewhere and run the .exe

![Installation](https://user-images.githubusercontent.com/8901040/194702506-39b6a9e9-46fe-46fc-a26a-f26dcc8f0387.gif)

# Build HuntStats yourself

The following things are required:

 - Windows with the [.NET 6.0 SDK](https://dotnet.microsoft.com/en-us/download) installed.
 - I recommend using the latest version of [Visual Studio](https://visualstudio.microsoft.com/vs/community/) or [JetBrains Rider](https://www.jetbrains.com/rider/).
 - .NET Maui installed (Either through [Visual Studio](https://visualstudio.microsoft.com/vs/community/) or with the CLI `dotnet workload install maui`)
 
Finally to build the project you need to run the following command in the root directory of HuntStats  
`dotnet publish -f net6.0-windows10.0.19041.0 -c Release -p:WindowsPackageType=None`

## Preview of the application
![Statistics Dashboard](https://user-images.githubusercontent.com/8901040/194701514-0c4dce81-35e1-4dda-a9bb-7c230df8fcf8.png)
![Matches Screen](https://user-images.githubusercontent.com/8901040/194701522-d4808a9f-3db5-42cb-8b56-02dbcba81785.png)
![Match Screen](https://user-images.githubusercontent.com/8901040/194701569-1c6c8744-f37f-4347-a470-863fa277a8cc.png)
![Settings Screen](https://user-images.githubusercontent.com/8901040/194701552-561a3f07-117d-4775-9e1c-c1f89bc4ee2d.png)

## Usage showcase
![Graphs](https://user-images.githubusercontent.com/8901040/194701835-bd889149-55d2-4448-84ce-c08fc0d2248a.gif)
![Select Player](https://user-images.githubusercontent.com/8901040/194701784-bf9165fc-ccbc-4593-9ac2-37289e25e8ab.gif)
![Select Folder](https://user-images.githubusercontent.com/8901040/194701724-2f58485f-40cc-4a06-9282-c964e7c06fcc.gif)
