# What
Autoswap create and delete swap file automaticly based on memory pressure. 
# Why
Swapfile on Linux must be created and deleted manually. This often happen in memory limited environment, for example VPS. 

When buy a cloud VM or a Raspebeery PI, memory and disk is all limited. Swapfile is often essencial for these scenes. 

But we have to create swapfile manully when needed. If not enough, create more. If go beyond, the disk space is wasted.

So, we need create and delete swapfile automaticly.
# How
1. download latest appimage release
2. run
