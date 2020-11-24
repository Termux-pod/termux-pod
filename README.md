# termux-pod

POD stands for package on demand for termux.
This repository contains debfile, it may soon move on bintary.

### How to choose debfiles ?
So simple answer is check your architecture with uname command.
`uname -m`

It will print your cpu architecture. Possible archs (arm, arch64,i686, x86_64).
and then choose which packages you need of which version,and browse folders and download debfiles. Incase your package or version is't available. Open an issues,we will try to make it available.

### Package installation.
After downloading debfiles you need to install it via dpkg.
```
dpkg -i path/of/debfile.deb
```
It should install that debfile.

**Still have problems, let us know by opening issue, we will try to resolve it.**

