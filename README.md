# paperfetcher

gets a version of Paper jar based on commandline arguments.  Used for headless Minecraft Servers to easily download any supported version of paper.
# Usage:
Designed To run on *-nix systems with Python3 installed 
***WSL works too, if you use Windows***

**CLI Argruments**
Running the script by itself (no arguments) will default to the latest Minecraft version `i.e. 1.18.1` and latest build number `160` as of writing this.  

**The Paper Developers do not recommend using the downloads API (which is what this script uses) to auto-update servers as some plugins may unexpectedly stop working, potentially causing irrepairable damage to your worlds and server.  Believe me, it's happened to my servers before!**

The recommended method of using this script is using the command line arguments to define the `project`, the targeted `minecraft` version, and finally, the `build` number defined by the papermc download API
`./paperfetcher -p paper -v `



