# RISC-V-cc
Instructions &amp; Scripts for installing/configuring your RISC-V toolchain.


# Overview

If you're using an x86-based GNU/Linux operating system (that is to say, you're using an x86 instruction set, as found in Intel and AMD CPUs) and want to create code that's runnable on a RISC-V platform, you need to engage in the art of *Cross Compiling*.  This lets you write a program as you normally would (e.g. in *Emacs*), then compile/build the application so it uses the RISC-V instruction set instead of x86.  See https://en.wikipedia.org/wiki/Cross_compiler this for more reading on this topic.

This little project will provide you with a couple of approaches to setting up your toolchain, and provide you with push-button scripts to make it as easy as possible.


# Sources

Below are some of the important *git* repositories we'll be using.

https://github.com/riscv-software-src/riscv-tools

https://github.com/riscv-software-src/riscv-isa-sim

https://github.com/riscv-software-src/riscv-pk


# Approaches

If you'd prefer a quick (and possibly reliable) approach, consider the "Using OS Packages," instructions  described below.  This method relies  on standard Debian packages as much as possible to create your environment (and give you a place to test locally, without having to flash your code to an external board).  Since there's no guarantee these packages are up-to-date, there's a chance you might be using outdated tools.

If you'd rather be up to date (and to make contributions to the riscv-software-src repos above), you will want to use the "Using Github Repos" method, explained below.

# Using OS Packages

TODO

# Using Github Repos

TODO


