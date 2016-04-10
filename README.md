# uhs_testbench
UHS development shared use test bench

Here I propose putting information pertaining to USB Host Shield test bench. At the moment, I have Debian machine online, reachable via ipv6 only (ssh). Beagle USB protocol analyzer is permanently wired to this machine (it is doubled as my UHS dev. workstation). Also, there will be a bunch of Arduino/UHS combos available. Also, a disconnector, i.e., a method of simulate device disconnect/connect remotely, is in late alpha.

What I want to achieve:

1. A place for us to work together on a hardware and share access to analyzer. Typical use: xxxajk needs a trace. I build him a setup here and he can then run traces while changing the code.
2. Standard test setup to verify the code after major changes. I see it as a set of all supported boards plus some representative devices.
3. Any other use - suggest.
