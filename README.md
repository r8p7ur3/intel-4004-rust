# intel-4004-rust

The purpose of this project is to recreate the funtionality of the [Intel 4004 microprocessor](https://en.wikipedia.org/wiki/Intel_4004)
within Rust (for the purpose of both understanding on a deeper level how microprossesors behave and tco improve my use of rust)

I aim to be as truthful to the capabiities of the original 4004 as possible, including:

- single multiplexed 4 bit bus for transfer of 12 bit adresses, 8 bit instructions and 4 bit data words
- full implementation of all 46 instructions the 4004 has
- 3 layers of subroutine stack


