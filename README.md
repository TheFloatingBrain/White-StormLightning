# Introduction

White - Storm: Lightning is a 2.5D easy to use, fast, powerful game engine written in C++ and Lua. It has a lot of nobs and buttons under the hood that are defaulted but not cut off from modification and addition. It features an addressable entity system or entity ID system where every entity is easily and efficiently identifiable and classified within the engine as well as excitability both through and outside its unique "Hierarchical Component System" which allows well defined "hierarchical components" to come packed with everything a game object then an instance of that object needs, all while being identifiable on that basis. Currently in it's alpha version, WSL (White - Storm: Lightning) is in it's fourth release (r5, starting from 0).

# Tutorials & Materials 
Accesss to the GCG Games github account has been lost however you can get WSLCLI from [here]( https://github.com/GCGGames/WSLCLI_A_Tool_Kit_For_White-Storm_Lightning), the White - Storm: Lightning website is currently under reconstruction. To find out more, please look out the [series of video tutorials](https://www.youtube.com/watch?v=d-U6QtGUhis&list=PL0YxqVtqQP1c-xjymjEtgK5PiHpT7pEKp) (2 more should be expected at some point in the future to complete the series). A correction on the "Geometry Class" tutorial, the method used should be `ThreadObject` (which does NOT refer to multi threading) not `GetObject` which does not require all the resetting to be done. Proper documentation should appear at some point.

# Binary Files
The White - Storm: Lightning includes a WSL binary and SFML 1.6, lua & luabind binaries and a Visual Studio 2008 project, this may change in the future, however this works for now and makes getting started easy without the need to compile from source or worry about the project not working (except for the old VS 2008 project). Also since WSL does not require any modification of its source code to build a game setup is made even easier as a portable executable for someone just getting started.

# Note
I have been working on a follow up to White - Storm: Lightning for a long time, assembling the components, and much has changed in the interum, Apple depracted Open GL, new VR/AR/MR technologies have arise, new C++ standards have been published. WSL is very outdated and the code quality is admittedly not the best, but it is still a very conceptually interesting engine and somewhat usable.
