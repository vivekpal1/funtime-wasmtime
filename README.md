# funtime-wasmtime

some cool resources, demos and resources for learning wasm with me :)

## intro

As web applications become increasingly complex, developers are turning to new technologies that can help them build faster, more efficient, and more secure applications. WebAssembly is one such technology that is gaining popularity for its ability to run high-performance code in web browsers at near-native speed.

In this repository, you'll find a variety of resources that can help you understand how WebAssembly works and how to use it in practice. Whether you're a beginner or an experienced developer, our goal is to provide you with the tools and knowledge you need to start building fast and efficient web applications using WebAssembly.

## wasm

[WebAssembly](https://webassembly.org/) (wasm) is a low-level bytecode for [a stack-based virtual machine](https://en.wikipedia.org/wiki/Stack_machine). And it can be run on four major browsers, Chrome, Edge, Firefox, and WebKit. It was created to bring high-performance, low-latency computing to the web, making it possible to run complex applications in the browser with near-native performance.

**[mdn web docs](https://developer.mozilla.org/en-US/docs/WebAssembly)**

## wasi

The WebAssembly System Interface (WASI) is a modular system interface for WebAssembly that provides an API to interact with the host environment in a secure and sandboxed way. It allows WebAssembly modules to run in different environments without modification, making it easier to develop portable and secure applications. With WASI, developers can access file systems, network interfaces, and other system resources, all while maintaining a strict separation between the module and the host environment. This makes it possible to run untrusted code securely within a trusted environment.

## wabt

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


## wapm

## examples

## Contributing

## Conclusion
