- title : F#: Write once, run (nearly) anywhere!
- description : F#: Write once, run (nearly) anywhere!
- author : Tomasz Heimowski
- theme : black
- transition : default

***

## F#: Write once, 
## run (nearly) anywhere!


<img src="images/fsharp.png" style="width:180px; background: transparent; border:none; box-shadow: none"  />

Tomasz Heimowski *@theimowski*

<img src="images/twitter.png" style="width:48px; background: transparent; border:none; box-shadow: none"  />
<img src="images/github.png" style="width:48px; background: transparent; border: none; box-shadow: none"  />

https://theimowski.com

***

# Goals

- Review possibilities
- Share experiences
- Inspire ideas
- Praise F#

***

# Plan

- The slogan
- History, evolution
- Platforms
- Mixing platforms

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
- influential platforms / tools
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

<img src="images/desktop_windows.jpg" style="width: 300px; background: white"  />
<img src="images/desktop_linux.jpg" style="width: 280px; background: white"  />
<img src="images/desktop_mac.png" style="width: 290px; background: white"  />

<br/>

* .NET Core
* .NET SDK
    * templates
    * watch mode

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

<small> https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md</small>

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

<img src="images/web.jpeg" style="width: 300px; background: white"  />

<br/>

- Frameworks
    - Fable
    - WebSharper
- Output
    - JavaScript
    - HTML
    - CSS

---

<img src="images/fable.png" style="width: 500px; background: white"  />


---

### Web Demo

* Fable + Elmish + React template
* Hot Module Replacement
* https://fable.io/repl/
* [Giraffe view engine - F# to HTML](https://github.com/giraffe-fsharp/Giraffe/blob/master/DOCUMENTATION.md#giraffe-view-engine)
* [Fable Material UI - F# to CSS](https://mvsmal.github.io/fable-material-ui/#/demos/app-bar)
* [F# Type provider for CSS](https://twitter.com/FableCompiler/status/1098545200899735552)

---

### Web Demo recap

* Seamless integration with JS ecosystem
* Ability to output also HTML/CSS from F#
* Not only Web - Node.js

***

## Desktop GUI


<img src="images/desktop_windows.jpg" style="width: 300px; background: white"  />
<img src="images/desktop_linux.jpg" style="width: 280px; background: white"  />
<img src="images/desktop_mac.png" style="width: 290px; background: white"  />


* Electron https://electronjs.org/
    * uses Node.js and Chromium
    * F# -> Fable -> JS -> Electron
* Fabulous
    * WPF
    * GTK
    * Mac

---

### Desktop GUI Demo

* 3 Operating systems:
    * OSX (local MacBook)
    * Windows (Virtualbox, Vagrant)
    * Ubuntu (Virtualbox, Vagrant)
* Create app from fable-electron template
* Print OS information
* Run the app on all OS


***

## Mobile

<img src="images/ios-vs-android.jpg" style="width: 400px; background: white"  />

- Frameworks
    - Xamarin + Fabulous
    - React Native (again via Fable)
- Targets
    - Android
    - iOS

---

### Mobile Demo

* iOS and Android
* Fabulous dotnet template

---

### Mobile talks

* Jim Bennett - Build Cross-Platform Mobile Apps Using Fabulous
* Kunjan Dalal - From Concept to Creation in a Week with Fabulous 

***

## IoT

<img src="images/raspberry.png" style="width: 400px; background: white"  />

<br/>

- .NET Core to ARM architecture
    - linux-arm
    - win-arm

---

<img src="images/forki_audio.png" style="width: 400px; background: white"  />

--- 

<img src="images/iot_fableconf.png" style="width: 400px; background: white"  />

<br/>

<small> https://twitter.com/airuyi/status/1056198418501124096 </small>

---

https://twitter.com/sforkmann/status/1049722323262160898

***

## Docker

<img src="images/docker.png" style="width: 150px; background: white"  />


https://hub.docker.com/_/microsoft-dotnet-core

* >10M pulls from Docker Hub
* Featured Repos:
  * .NET Core SDK
  * ASP.NET Core Runtime
  * .NET Core Runtime
  * .NET Core Runtime Dependencies
  * .NET Core Samples

---

## Docker

<img src="images/docker.png" style="width: 150px; background: white"  />


`--deploy docker` option for [SAFE Template](https://github.com/SAFE-Stack/SAFE-template)

***

## Serverless


<img src="images/azure_functions.jpg" style="width: 130px; background: white"  />
<img src="images/aws_lambda.png" style="width: 130px; background: white"  />

- Azure Functions
    - https://docs.microsoft.com/pl-pl/azure/azure-functions/functions-reference-fsharp
    - Talk: Mikhail Shilkov - Durable F#unctions
- AWS Lambda
    - https://aws.amazon.com/blogs/developer/f-tooling-support-for-aws-lambda/
- Google Cloud
    - no official F# support, but can do F# -> Node.js


***

## Other platforms & tools

---

### Tests

* https://github.com/fsprojects/FsUnit
* https://github.com/haf/expecto
* https://github.com/fscheck/FsCheck
* https://github.com/SwensenSoftware/unquote

---

### Fake

![fake](images/fake_script.png)

--> https://fake.build/

---

### Fez

![fez](images/fez.png)

https://github.com/kjnilsson/fez

--> [FEZ - fsharp type safety for the BEAM](https://skillsmatter.com/skillscasts/11312-fez-fsharp-type-safety-for-the-beam) (F# eXchange '18)

---

### Pulumi

<img src="images/pulumi.jpg" style="width:650px; background: transparent; border:none; box-shadow: none"  />


<small> https://twitter.com/MikhailShilkov/status/1097408586349719552 </small>

--> Lightning Talk: Cloud Infrastructure as F# 

---



### More?

***

# Mixing platforms

---

## SAFE - Web

<img src="images/safe.png" style="width:256px; background: transparent; border:none; box-shadow: none"  />

<br/>
<br/>

* Web server: F# -> .NET Core
* Web client: F# -> JavaScript
* Shared F# code:
    * Remote call protocols
    * Server-side & client-side validation
    * etc...
* https://safe-stack.github.io/docs/
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

* Remote Desktop in a browser (alpha version)
* Device Agent: 
    * F# -> .NET Core and .NET 4.0
    * Windows, OSX and Linux
* Browser viewer: F# -> JS
* Shared F# code:
    * HTTP & WebSocket payload DTOs
    * JSON serialisation (Thoth.Json)
    * Protocol for Web Remote Desktop (Apache Guacamole)

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

---

## SAFE Talks

* Anthony Brown - Workshop: Up and Running with the SAFE Stack
* Tomasz Heimowski - F# SAFE Stack: Current State

***

# Recap

* Great tools -> evolution
* F# targets many platforms
* Combining platforms & sharing code

***

# Thank you!

Slides available at 

https://theimowski.com/talk-fsharp-write-once