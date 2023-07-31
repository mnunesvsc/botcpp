# botcpp
A C++ bot implemented in CGI which demonstrates the integration technologies of CGI archictecture.
The project example uses Apache as webserver, but can be executed in any CGI enabled webserver.

# Getting Started
## Requirements
In an linux server environment install gnu CGI as instructed on this page https://www.gnu.org/software/cgicc/ 
Install qemu-system-riscv
(option) Install gdb-multiarch
## Build and Run
Clone this project & enter: git clone ... && cd botcpp
Build: make
Run: cargo run --target riscv64gc-unknown-none-elf, then qemu will boot octox. To exit, press Ctrl+a and x.
