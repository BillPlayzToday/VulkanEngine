# Vulkan Engine
## What's this?
This is my personal version of a render engine using Khronos' [Vulkan API](https://www.vulkan.org/).
The main concept of the procedure is coming from an unofficial Vulkan-Support site, which has also taught me most of the knowledge about Vulkan.

## Can I use it?
Yes, BUT ripping of a random engine from GitHub doesn't make you proud neither is it going to fit your needs, you should prefer using a frequently updated to the state-of-the-art site like [this](https://vulkan-tutorial.com/), which are dedicated to teaching Vulkan-noobs the API, you should also check out their Tutorial-Repository [here](https://github.com/Overv/VulkanTutorial).

## Requirements
You will need a few things to open the Project written in **Visual Studio 2019**, which are as follows:

 - Vulkan SDK *(1.3.216.0)* (I've installed everything available in the installer)
 - glfw *(3.3.7 WIN64)*
 - glm

Add the following to your Visual Studio Project Settings to make the packages work:

 - C/C++ -> General
	 - .../VulkanSDK/*version*/Include
	 - .../glm
	 - .../glfw-*version*.BIN.*platform*/include
 - Linker -> General
	 - .../VulkanSDK/*version*/Lib
	 - .../glfw-*version*.BIN.*platform*/lib-vc*version*
 - Linker -> Input
	 - vulkan-1.lib
	 - glfw3.lib


## Disclaimer for collecting code from raw.github.com
You should probably not collect this code from raw.github.com, because of unannounced changes.
