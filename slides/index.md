- title : F#: Write once, run (nearly) anywhere!
- description : F#: Write once, run (nearly) anywhere!
- author : Tomasz Heimowski
- theme : black
- transition : default

***

# F#: Write once, run (nearly) anywhere!


<img src="images/fsharp.png" style="width:256px; background: transparent; border:none; box-shadow: none"  />

Tomasz Heimowski 

<img src="images/twitter.png" style="width:48px; background: transparent; border:none; box-shadow: none"  />
<img src="images/github.png" style="width:48px; background: transparent; border: none; box-shadow: none"  />

*@theimowski*

https://theimowski.com

***

# Plan

- Goal
- The slogan
- History, evolution
- Platforms
- Mixing platforms
- ? Domains

***

# Goal

- no inventions
- discover possibilities
- share experiences
- inspire ideas

***

# The slogan

## Write once, run anywhere

- Sun Microsystems
- Java cross-platform benefits
- Variations: "Write once, **debug** anywhere"
- Copied to make my talk more catchy

https://en.wikipedia.org/wiki/Write_once,_run_anywhere

---

![one_does_not_simply.jpg](images/one_does_not_simply.jpg)

***

# History

- F# evolution
- influential platforms
- possibly not in chronological order

---

https://fsharp.org/history/

![history](images/history-hopl.png)

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/.net.png" style="width: 400px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/mono.png" style="width: 400px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/xamarin.jpg" style="width: 500px; background: white"  />


---

- data-transition : fade
- data-transition-speed : slow

### FAKE - F# Make

<img src="images/fake.png" style="width: 300px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/azure.png" style="width: 500px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/.netcore.png" style="width: 400px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/docker.png" style="width: 400px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/fable.png" style="width: 500px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/fabulous.png" style="width: 600px; background: white"  />

***

# Platforms

- Desktop
- Mobile
- Web
- IoT
- Docker
- Serverless
- Other platforms

***

## Desktop

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/desktop_windows.jpg" style="width: 600px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/desktop_linux.jpg" style="width: 600px; background: white"  />

---

- data-transition : fade
- data-transition-speed : slow

<img src="images/desktop_mac.png" style="width: 600px; background: white"  />

---

### NET Core 3.0 Supported OS

* Windows Client                | 7 SP1+, 8.1                   | x64, x86       
* Windows 10 Client             | Version 1607+                 | x64, x86       
* Windows Server                | 2008 R2 SP1+                  | x64, x86       
* Mac OS X                      | 10.12+                        | x64            
* Red Hat Enterprise Linux      | 6                             | x64            
* Fedora                        | 28                            | x64            
* Debian                        | 9                      | x64, ARM32, ARM64     
* Ubuntu                        | 16.04+                   | x64, ARM32, ARM64   
* Linux Mint                    | 18                            | x64            
* openSUSE                      | 42.3+                         | x64            
* SUSE Enterprise Linux (SLES)  | 12 SP2+                       | x64            
* Alpine Linux                  | 3.8+                          | x64, ARM64     

[Data from GitHub](https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md)

---

### Demo

* OSX + Vagrant windows + Vagrant ubuntu
* dotnet new console, run on all OS
* dotnet watch run, print OS name, run on all OS

* Maybe Desktop gui demo after "WEB" ?
* https://github.com/fable-compiler/samples-electron, run on all OS
* or maybe https://github.com/cmeeren/fable-elmish-electron-material-ui-demo
* mention fabulous: WPF, GTK, Mac


***

## Web

- Fable
- JavaScript
- HTML
- CSS
- ? WASM

---

### Demo

* Fable template
* Elmish
* React
* CSS (new Type provider)
* HMR

***

## Mobile

- Xamarin
- Fabulous
- React Native

---

### Demo

* Fabulous app for iOS and Android

***

## Back to Desktop

***

## IoT

- Raspberry PI https://github.com/pkese/raspberry-fsharp
- ARM?

---

### Demo

- video? / @forki audio project?
- https://twitter.com/search?q=%23fableconf%20raspberry&src=typd
- https://twitter.com/sforkmann/status/1076600804935680000
- https://twitter.com/sforkmann/status/1049722323262160898

***

## Docker

- .net core docker images

---

### Demo

- e.g. Docker deploy from SAFE template

***

## Serverless

- Azure Functions
- AWS Lambda

---

### Demo

- Azure function

***

## Other platforms

- Fez
- FAKE
- Tests?
- various DSL like Pulumi?
- ... ?

***

# Mixing platforms

- SAFE
- Not just Web apps
- Sharing code
- Datto RMM

---

### Bonus demo

- Go crazy and reuse code for desktop, JS, server, mobile

***

# ? Domains

***

# Recap

***

### Notes 

- .NET Core
- x-plat
- SDK
- templates
- multi-target (full .net, .net core)
