# funtime-wasmtime

some cool resources, demos and resources for learning wasm with me :)

## intro

As web applications become increasingly complex, developers are turning to new technologies that can help them build faster, more efficient, and more secure applications. WebAssembly is one such technology that is gaining popularity for its ability to run high-performance code in web browsers at near-native speed.

In this repository, you'll find a variety of resources that can help you understand how WebAssembly works and how to use it in practice. Whether you're a beginner or an experienced developer, our goal is to provide you with the tools and knowledge you need to start building fast and efficient web applications using WebAssembly.

# wasm

[WebAssembly](https://webassembly.org/) (wasm) is a low-level bytecode for [a stack-based virtual machine](https://en.wikipedia.org/wiki/Stack_machine). And it can be run on four major browsers, Chrome, Edge, Firefox, and WebKit. It was created to bring high-performance, low-latency computing to the web, making it possible to run complex applications in the browser with near-native performance.

**[mdn web docs](https://developer.mozilla.org/en-US/docs/WebAssembly)**

# wasi

The WebAssembly System Interface (WASI) is a modular system interface for WebAssembly that provides an API to interact with the host environment in a secure and sandboxed way. It allows WebAssembly modules to run in different environments without modification, making it easier to develop portable and secure applications. With WASI, developers can access file systems, network interfaces, and other system resources, all while maintaining a strict separation between the module and the host environment. This makes it possible to run untrusted code securely within a trusted environment.

# wabt

If you're looking to work with WebAssembly, then you might have come across the WebAssembly Binary Toolkit, or simply known as WABT. This open-source tool provides a set of command-line tools for working with WebAssembly binary files, allowing you to create, inspect, and manipulate WebAssembly modules. With its easy-to-use interface and powerful capabilities, WABT is an essential tool for anyone who wants to develop, debug, or optimize WebAssembly code. In this talk, we'll take a closer look at what WABT is, how it works, and how it can be used to improve your WebAssembly development workflow.

## other resources

The official WebAssembly website (https://webassembly.org/) is a great place to start learning about the technology. It provides an overview of what WebAssembly is, how it works and its benefits.

The WebAssembly Studio (https://webassembly.studio/) is an online tool that allows you to write, compile and run WebAssembly code in your browser. It also provides examples and tutorials to help you get started.

The rustwasm book (https://rustwasm.github.io/docs/book/) is a comprehensive guide for using Rust and WebAssembly together. It covers everything from setting up your development environment to writing complex applications.

The WASI website (https://wasi.dev/) is a resource specifically focused on the WebAssembly System Interface (WASI). It provides documentation, tutorials and tools to help you understand how to use WASI to build portable applications.

The Wasm By Example website (https://wasmbyexample.dev/) provides a collection of simple examples that demonstrate how to use WebAssembly to perform various tasks, such as arithmetic operations, memory management, and more.



# Tools and Libraries

Some of the most popular tools and libraries for working with wasm:

**wasm-pack**: A command-line tool that helps you build and publish Rust-generated WebAssembly packages. It generates a JavaScript API that can be used to interact with your wasm modules from JavaScript.

**emscripten**: A LLVM-based toolchain that compiles C and C++ source code into asm.js or WebAssembly. Emscripten also comes with a library called "Pthreads" that enables multithreading in the browser.

**wabt**: The WebAssembly Binary Toolkit is a suite of tools for working with WebAssembly files. It includes a disassembler, an assembler, a validator, and other utilities.

**wasmer**: A runtime for executing WebAssembly code outside the browser. Wasmer supports multiple architectures and operating systems, including Linux, Windows, macOS, and iOS.

***wasm-bindgen**: A Rust library that provides a bridge between Rust-generated wasm and JavaScript code. It makes it easy to call functions, transfer data, and create custom types across the wasm-JavaScript boundary.

**AssemblyScript**: A TypeScript-like language that compiles to WebAssembly. AssemblyScript simplifies the process of writing WebAssembly code by providing syntax similar to TypeScript and access to the full JavaScript ecosystem.

**WebAssembly Studio**: A web-based development environment for creating and testing WebAssembly modules. It includes a code editor, a compiler, a debugger, and a visualizer.

**Binaryen**: A compiler infrastructure library that optimizes and validates WebAssembly code. Binaryen provides a set of tools for manipulating WebAssembly modules, including dead code elimination and function inlining.

**wasmtime**: A standalone runtime for executing WebAssembly code. Wasmtime supports multiple architectures and operating systems, including Linux, Windows, macOS, and iOS. It is also embeddable in Rust projects.

**wasm-pack-plugin**: A webpack plugin that simplifies the process of building and bundling wasm modules with your existing JavaScript projects.


# wapm

If you're looking for a package manager specifically designed for WebAssembly, look no further than wapm. Wapm is an open-source package manager that makes it easy to discover and use packages written in WebAssembly.

## Getting Started

To get started with wapm, you'll first need to install it on your system. You can do this by following the instructions provided on the [official wapm website](https://wapm.io/).

Once you have wapm installed, you can start using it to install packages. For example, let's say you want to install the `hello-world` package. You would simply run the following command:

```
$ wapm install hello-world
```

Wapm will automatically download and install the package, along with any dependencies it may have. Once the installation is complete, you can use the package just like any other module in your project.

## Discovering Packages

One of the great things about wapm is the ease with which you can discover new packages. You can browse available packages on the [official wapm website](https://wapm.io/), or you can search for packages directly from the command line.

For example, let's say you're looking for a package that provides basic mathematical functions. You could run the following command:

```
$ wapm search math
```

This will return a list of all packages related to mathematics. From there, you can read more about each package and decide which one best meets your needs.

# examples

The examples directory contains a collection of code samples and tutorials on how to use various programming languages with WebAssembly. These examples cover a wide range of topics, from simple "hello world" programs to more complex applications that demonstrate how to interact with the browser and other JavaScript APIs.

## Available Examples

Here are some of the examples currently available in the repository:

1. **hello-world**: A simple "hello world" application that demonstrates how to compile and run a basic WebAssembly program using C++.

2. **fibonacci**: An example program that calculates the first 20 numbers in the Fibonacci sequence using Rust and WebAssembly.

3. **canvas-manipulation**: A collection of examples that show how to use WebAssembly to manipulate the HTML5 canvas element. This includes drawing shapes, animating objects, and responding to user input.

4. **webgl**: An example program that demonstrates how to use WebAssembly with WebGL to create interactive 3D graphics in the browser.

5. **audio-processing**: An example program that shows how to use WebAssembly to process audio data in real-time. This includes generating sound waves, applying effects, and creating a simple synthesizer.

## Running the Examples

To run the examples in this repository, you'll need to have a few tools installed:

- The appropriate compiler for the language used in the example (e.g., GCC for C++, Rust compiler for Rust)
- Emscripten SDK to compile code into wasm bytecode
- A modern web browser that supports WebAssembly (e.g. Chrome, Firefox)

Once you have these tools installed, simply navigate to the `examples` directory in your terminal and follow the instructions provided with each example. Some examples may require additional dependencies, such as libraries or frameworks.

# Contributing

Contributions to this project are always welcome! Whether you're a seasoned WebAssembly developer or just getting started, there are many ways you can help improve the examples and resources in this repository.

## Contributing to wapm

If you're interested in contributing to wapm, you can find the source code on [GitHub](https://github.com/wasmerio/wapm-cli). The project is open-source and welcomes contributions from developers of all skill levels.

Whether you're a seasoned veteran or just getting started with WebAssembly development, wapm is a powerful tool that can help you manage your projects more efficiently. Give it a try and see what it can do for you!

## Contributing to the Examples

If you find an issue with one of the examples, or if you'd like to contribute your own example to the repository, feel free to submit a pull request on GitHub. Contributions are always welcome and appreciated!
## How to Contribute

Here are some of the ways you can contribute:

- **Report issues**: If you find a bug or problem in one of the examples, please submit an issue on GitHub. Be as detailed as possible when describing the issue, including steps to reproduce it if possible.

- **Suggest improvements**: If you have ideas for how to improve an example or resource in this repository, please feel free to open a new issue and share your thoughts.

- **Submit a pull request**: If you'd like to contribute code changes or additions, you can do so by submitting a pull request on GitHub. Please make sure your changes are well-documented and follow the existing coding standards.

- **Translate documentation**: If you're fluent in a language other than English, we would love your help translating the documentation and resources in this repository.

## Guidelines

When contributing to this project, please keep the following guidelines in mind:

- Follow the existing coding standards and style of the project.

- Test your changes thoroughly before submitting a pull request.

- Document your changes thoroughly, including comments in the code and updates to any relevant documentation.

- Be respectful and professional in all interactions with other contributors and maintainers.

Thank you for your interest in contributing to this project! Together, we can create a valuable resource for anyone interested in WebAssembly development.

## Conclusion

Whether you're interested in using WebAssembly for game development, scientific computing, or web development, this repository contains a wide range of examples that cover many different use cases. Additionally, the tools and libraries listed in this repository can help you streamline your WebAssembly development workflow.

We encourage you to explore the resources in this repository and contribute your own examples and improvements. By working together, we can continue to grow and improve the WebAssembly ecosystem and unlock its full potential for developers everyw