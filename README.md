# TL-RippleAdder
## Introduction
Designing and implementing transistor level ripple adder in three families: Static CMOS, Dynamic CMOS and DCVSL.
## Report
|Family             |Static Power [input = 0] |Static Power [input = 1] |Dynamic Power|tplh   |tphl  |
|:------------------|:-----------------------:|:-----------------------:|:-----------:|:-----:|:----:|
|Static             |*19.28u*                 |*8.53u*                  |*25.656u*    |*63p*  |*64p* |
|Dynamic  [clk = 0] |*4.48u*                  |*4.38u*                  |*16.8u*      |*-*    |*22p* |
|Dynamic  [clk = 1] |*7.86u*                  |*8.52u*                  |*16.8u*      |*-*    |*22p* |
|CVSL               |*9.52u*                  |*7.62u*                  |*19.5u*      |*83.5p*|*32p* |
