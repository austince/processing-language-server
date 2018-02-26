# Processing Language Server - PLS - _Please_ (?)
A language server for the [Processing Language](https://processing.org).  

This repository is a placeholder to remind me to start on this idea. Until a good language server is built, using Processing will be primarily restricted to the Processing IDE. While the IDE serves a great purpose, decoupling the language from the app will allow Processing developers to spend more time on language features and libraries.    

A Language server would be able to support any IDE that supports the protocol for clients: Atom, VS Code, and maybe one day official Jetbrains support.

## Inspirations + Implementation
The most up-and-coming use of the PLS is VS Code. The server will be implemented using [Microsoft's Language Server Prototcol](https://github.com/Microsoft/language-server-protocol).  

Here is a good example of a [generic language server written in Typescript](https://github.com/Microsoft/vscode-extension-samples/tree/4a1d8c37ff169c2c024e912a9f6a74fb9d372452/lsp-sample/server).  

The beginning of this project (and this README) will be a collection of resources and preliminary plans. Feel free to join in.  

* https://github.com/sourcegraph/javascript-typescript-langserver 
