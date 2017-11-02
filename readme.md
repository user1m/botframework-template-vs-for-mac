# botframework-template-vs-for-mac (unofficial)

Bot Framework template app you can build and run in VS for Mac

## Motivation

So you can create [C# Bots using Visual Studio for Windows](https://docs.microsoft.com/en-us/bot-framework/dotnet/bot-builder-dotnet-quickstart) and currently there are templates you can install in Visual Studio 2017 that allow you to create bots. The team states:


> The Bot Builder SDK for .NET currently supports C#. **Visual Studio for Mac is not supported.**

#### This repo enables you to build C# bots using [Visual Studio for Mac.](https://www.visualstudio.com/vs/visual-studio-mac/)
##### Disclaimer: While this repo enables you to build a C# bot in VS for Mac not all nuget packages are directly supported.

## Prerequisites

* [Visual Studio for Mac](https://www.visualstudio.com/vs/visual-studio-mac/)


## Using

```
1. Clone or Download this repo
```

![](./images/clone-dl.png)

```
2. Open the .csproj
```

![](./images/csproj.png)

```
3. Click on 'Project' > 'Restore NuGet packages'
```

![](./images/restore-packages.png)

```
4. Build Solution
```

![](./images/build.png)

```
5. Click on 'Project' > 'Bot Application Options' & Update 'Port:' to 3978
```

![](./images/set-port.png)

```
6. Run solution - That will open up a webpage like the one below
```

![](./images/run.png)

![](./images/webpage.png)


```
7. Connect to Bot Framework Emulator
```

![](./images/bf-emulator.png)

## Resources

* [Create a bot with the Bot Builder SDK for .NET](https://docs.microsoft.com/en-us/bot-framework/dotnet/bot-builder-dotnet-quickstart)

## Authors

* **Claudius Mbemba** - [user1m](https://github.com/user1m)

## License

This project is licensed under the MIT License 