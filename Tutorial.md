

In this post i will share my learnings and research work done during microcorruption CTF challenge.

#### What is Microcorruption?

Its an embedded security CTF challenge where you are given a debugger and a device (a smart lock), you will be given different levels of challenges to unlock the device, find flgs, find code vulnerabilitys, memory corruption bugs etc.

You'll use the debugger to reverse-engineer the code for each level. You can provide the device with input, then step through the code watching what the device does what that input. You're looking for a specific input that unlocks the device. Maybe that input is the correct passcode. More likely, though, it's something else: an input that exploits a bug in the device's code.

#### Pre-requisites

* little knowledge of assembly
* little knowledge of debuggers
* knowledge of memory corruption vulnerabilities


To start with the CTF one is advised to go through the [lock manual](https://microcorruption.com/manual.pdf) provided by the CTF team. The manual provides of useful information from attackers perspective as well .
