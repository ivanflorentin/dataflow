# DataFlow

A Data storage and replication library.
<p>Work in progress</p>

### Prerequisites

* nim >= 0.19
```
# step 1:
git clone https://github.com/nim-lang/Nim.git
cd Nim

# step 2 (posix) clones `csources.git`, bootstraps Nim compiler and compiles tools
sh build_all.sh

# step 2 (windows)
git clone --depth 1 https://github.com/nim-lang/csources.git

cd csources
# requires `gcc` in your PATH, see also https://nim-lang.org/install_windows.html
build.bat # x86 Windows
build64.bat # x86_64 Windows
cd ..

bin\nim c koch
koch boot -d:release
koch tools # Compile Nimble and other tools
# end of step 2 (windows)
```

* uuids >= 0.1.10
[https://github.com/pragmagic/uuids]
