# Auto-Vk-Toolkit-VS-Starter

This is a starter template for setting up a new project in [Microsoft Visual Studio](https://visualstudio.microsoft.com/), based on the [Auto-Vk-Toolkit](https://github.com/cg-tuwien/Auto-Vk-Toolkit) rendering framework.     
It sets up a copy of the [hello_world](https://github.com/cg-tuwien/Auto-Vk-Toolkit/tree/master/examples/hello_world) example as a new project.

## Setup

Follow these steps:
1. Use this template to create a new project via the [Use this template](https://github.com/cg-tuwien/Auto-Vk-Toolkit-VS-Starter/generate) button above.
2. Clone this repository to a directory on your PC using [Git](https://gitforwindows.org/).
3. Within this directory, execute    
    ```
	git submodule update --init --recursive 
	```
4. Open the Visual Studio solution file `my-avk-project.sln`
5. In Visual Studio, select the project `my-avk-project` as startup project
6. Build and run 

If your program runs and produces the following rendering result, everything has been set up properly:

![expected rendering output, same as hello_world](https://github.com/cg-tuwien/Auto-Vk-Toolkit/blob/master/docs/images/example_hello_world.png)

## Hints

### Use Auto-Vk-Toolkit's latest features

Use Auto-Vk-Toolkit's [`development`](https://github.com/cg-tuwien/Auto-Vk-Toolkit/tree/development) branch to use the latest features and updates from [Auto-Vk](https://github.com/cg-tuwien/Auto-Vk) and [Auto-Vk-Toolkit](https://github.com/cg-tuwien/Auto-Vk-Toolkit).     
To switch to the `development` branch, follow these steps: 
1. `cd Auto-Vk-Toolkit` (navigate into the submodule)
2. `git fetch`
3. `git switch development`
4. `git submodule update --recursive` 

### Post Build Helper tool

Auto-Vk-Toolkit uses a _Post Build Helper_ tool for shader compilation and asset deployment. Once you build or run your project, you'll find a `PBH` icon in your tray area. Read more about it in the [Post Build Helper]() documentation section.

### CMake-based projects

A starter template for CMake-based projects based on Auto-Vk-Toolkit is available at [JolifantoBambla/Auto-Vk-Toolkit-Starter](https://github.com/JolifantoBambla/Auto-Vk-Toolkit-Starter).

### Further information

Should you run into any problems, please consult Auto-Vk-Toolkit's [FAQs, Known Issues, Troubleshooting](https://github.com/cg-tuwien/Auto-Vk-Toolkit/tree/master#faqs-known-issues-troubleshooting) section. If that doesn't help, consider creating an issue in one of the repositories.
