# Getting Started

- Checkout installation instructions for F# at [fsharp.org](https://fsharp.org) under the `Use` tab.
- If you are not on Windows:
  - Install [Mono runtime](https://www.mono-project.com/download/stable/) (if you haven't already)
- Install the latest version of [Dotnet Core](https://dotnet.microsoft.com/download)

## For editing code, you can use:
- [Visual Studio Code](https://code.visualstudio.com/download) with the [Ionide](http://ionide.io) plugin
  - Recommend for just starting out.
- Visual Studio / Visual Studio for Mac
- Jetbrains Rider (commercial)
- Emacs/Vim

## To Follow Along ..
Do the above and then

### In a notebook
- Follow instructions above to install F# (and Mono if you are on mac/linux)
- clone this repo
- install juptyer (if you haven't already)
```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```
- Download [F# Juptyer Kernel](https://github.com/fsprojects/IfSharp/releases/download/v3.0.1/IfSharp.v3.0.1.zip)
- Unzip the release then run `mono ifsharp.exe` (this sets up the Jupyter kernel files in ~/.local/share/jupyter/kernels/ifsharp/)
  - if on Windows just `ifsharp.exe
- finally run `jupyter notebook` from this repo and open the `Learn-FSharp.pynb` notebook

### In Visual Studio Code
- Install Visual Studio Code and Ionide (links above)
- Open the `Command Pallete`
  - Mac
    - `Cmd` + `Shift` + `p`
  - Windows & Linux
    - `Ctrl` + `Shift` + `p`
- Create a new F# project by selecting: `F#: New Project`
  - Follow all prompts to create a new project
- Once in the F# project, open up `FSI` (Fsharp Interactive) a F# REPL
  - Open the `Command Pallete`
  - select `FSI: Start`