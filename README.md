# Scrypto
 Radix Academy: Scrypto 101


Segui o guia de instalação

Estrutura das pastas



Directory Structure
The Scrypto package you just created is a boilerplate called for a Hello blueprint. At the root of the generated package directory, you should find three things: 
src (source) folder
tests folder 
Cargo.toml file. 
If you’ve programmed in Rust before, you’ll immediately find this structure to be familiar and that’s because Scrypto is based on Rust! The Cargo.toml is a Rust-related file that provides metadata about the package, dependencies such as the Scrypto library that allows us to write Scrypto code, and parameters to build your Scrypto package.



Let’s move our attention a bit to the tests folder. This is where you write unit and integration tests for your package. You can run the tests located in this directory with the scrypto test command in your terminal. This is good for creating exotic and custom test scenarios. However, in this course, we’ll be using the handy resim to interact and test the Scrypto packages we create.
The src folder is where you will write your Scrypto code or in other words, your blueprint. Within this folder, you will find the lib.rs file, which contains the Hello blueprint code. All packages must have a lib.rs file - which is the starting point of your Scrypto package. Since Hello is a simple package, we’ve put all our blueprint code within this file.