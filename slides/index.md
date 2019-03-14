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

***

# Goal

- no inventions
- discover possibilities
- share experiences
- inspire ideas
- praise F#

***

# The slogan

## Write once, run anywhere

- Sun Microsystems
- Java cross-platform benefits
- Copied to make my talk more catchy

https://en.wikipedia.org/wiki/Write_once,_run_anywhere

---

![one_does_not_simply.jpg](images/one_does_not_simply.jpg)

---

![java_debug_everywhere.png](images/java_debug_everywhere.png)

<small>
https://blog.silentsignal.eu/2014/02/09/jdb-tricks-hacking-java-debug-wire/
</small>

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

* .NET Core
* .NET SDK
    * templates
    * watch mode

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

### Desktop Demo

* 3 Operating systems:
    * OSX (local MacBook)
    * Windows (Virtualbox, Vagrant)
    * Ubuntu (Virtualbox, Vagrant)
* Create console app using .NET SDK
* Print OS information
* Run the app on all OS
* Run "watch" mode

https://www.vagrantup.com/

---

### Desktop Demo recap

* Cross-platform .NET SDK
* Easy to set up
* Caution: "watch" + multi OS doesn't work with Paket
* What about GUI?

***

## Web

- Frameworks
    - Fable
    - WebSharper
- Output
    - JavaScript
    - HTML
    - CSS
    - Web Assembly *

---

### Web Demo

* Fable template
* Elmish
* React
* CSS (new Type provider)
* Hot Module Replacement
* Various browsers ?

***

## Desktop GUI

* Electron https://electronjs.org/
    * uses Node.js and Chromium
    * F# -> Fable -> Electron
* Fabulous
    * WPF
    * GTK
    * Mac

---

### Desktop GUI Demo

* https://github.com/fable-compiler/samples-electron, or
* https://github.com/cmeeren/fable-elmish-electron-material-ui-demo
* run on all OS

***

## Mobile

- Frameworks
    - Xamarin + Fabulous
    - React Native (again via Fable)
- Targets
    - Android
    - iOS

---

### Demo

* Fabulous app for iOS and Android

***

## IoT

- .NET Core to ARM architecture
    - linux-arm
    - win-arm

---

### IoT Demo

![images/forki_audio.png](images/forki_audio.png)

---

### IoT Demo

https://twitter.com/sforkmann/status/1049722323262160898

***

## Docker

- .net core docker images

---

### Docker Demo

- e.g. Docker deploy from SAFE template

***

## Serverless

- Azure Functions
- AWS Lambda

---

### Demo

- Azure function

***

## Other platforms & tools

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

## SAFE - Web

<img src="images/safe.png" style="width:256px; background: transparent; border:none; box-shadow: none"  />

<br/>
<br/>

* Web server: F# -> .NET Core
* Web client: F# -> JavaScript
* Cloud access: F# -> Azure
* Shared F# code:
    * Data-Transfer Objects
    * Remote call protocols
    * Server-side & client-side validation
    * etc...
* https://safe-stack.github.io/docs/
* https://github.com/SAFE-Stack/SAFE-template
* https://github.com/SAFE-Stack/SAFE-BookStore

---

## SAFE - Mobile

<img src="images/safe.png" style="width:256px; background: transparent; border:none; box-shadow: none"  />

<br/>
<br/>

* REST API: F# -> .NET Core
* Mobile apps: F# -> JS -> React Native -> iOS + Android
* Shared F# code:
    * Business logic
    * Mobile device OS classification
    * etc...
* https://github.com/SAFE-Stack/SAFE-Nightwatch

---

## SAFE - IoT

<img src="images/safe.png" style="width:256px; background: transparent; border:none; box-shadow: none"  />

<br/>
<br/>

* Web server: F# -> .NET Core
* Web client: F# -> JavaScript
* Raspberry PI: F# -> .NET Core (linux-arm RID)
* Shared F# code:
    * Determining firmware
    * Communication protocol
    * etc...
* https://github.com/forki/audio

---

## SAFE - Desktop


<img src="images/datto-logo.png" style="width:360px; background: transparent; border:none; box-shadow: none"  />
<img src="images/heart.png" style="padding-left: 20px; padding-right: 20px; width:100px; background: transparent; border:none; box-shadow: none"  />
<img src="images/safe.png" style="width:200px; background: transparent; border:none; box-shadow: none"  />


<br/>
<br/>

* Remote Desktop in a browser (alpha version)
* Device Agent: 
    * F# -> .NET Core and .NET 4.0
    * Windows, OSX and Linux
* Browser viewer: F# -> JS
* Development web server: F# -> .NET Core
* Shared F# code:
    * HTTP & WebSocket payload DTOs
    * JSON serialisation (Thoth.Json)
    * Protocol for Web Remote Desktop (Apache Guacamole)
* https://www.datto.com/business-management/datto-rmm

---

- data-background : images/datto-rmm-rto-screen.png
- data-background-size : contain

---

## SAFE - All inclusive?

<img src="images/safe.png" style="width:256px; background: transparent; border:none; box-shadow: none"  />

<br/>
<br/>

- Desktop
- Mobile
- Web
- IoT
- Docker
- Serverless
- Other?

***

# Recap

***

### Notes 

- .NET Core
- x-plat
- SDK
- templates
- multi-target (full .net, .net core)
- create gifs / videos for demos fallback