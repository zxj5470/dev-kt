# DevKt

CI|Status
:---:|:---:
Travis CI|[![Build Status](https://travis-ci.org/ice1000/dev-kt.svg?branch=master)](https://travis-ci.org/ice1000/dev-kt)
AppVeyor|[![Build status](https://ci.appveyor.com/api/projects/status/c0aq16ej7415m302?svg=true)](https://ci.appveyor.com/project/ice1000/dev-kt)
CircleCI|[![CircleCI](https://circleci.com/gh/ice1000/dev-kt.svg?style=svg)](https://circleci.com/gh/ice1000/dev-kt)

This is a DevCpp-like cross-platform Kotlin IDE features in lightweight.

# Build

+ (Optional) Download and decompress [Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic/releases) font to `res/font`
  + As reference you can see [this shell script](./download-font.sh)
+ Use `gradlew run` to run this application

# Features

+ Fast (at least faster than Emacs/Eclipse/IntelliJ/CLion/VSCode/Atom)
+ Lightweight (Just a tiny Java Swing application)
+ Kotlin compiler integration (**100% correct parsing**)
+ JetBrains IDE icons
+ Build as jar/class files, run after build, just one click
+ Cross platform (windows/macos/linux), just one jar file

# Progress

+ Properties-based settings (hackable!)
	+ [X] Deals with missing properties
	+ [X] Auto-saving
	+ [X] Highlight color customization
	+ [ ] Text style customization
	+ [ ] Font customization
	+ [ ] Keymap customization
	+ [ ] Internationalization
+ File operations
	+ [X] Create new file when no files are opened
	+ [X] Save and sync
	+ [X] Show in files
	+ [X] Record recently opened files
	+ [ ] Create new files from templates
+ [ ] Editing
	+ [X] Lexer based highlights
	+ [X] Undo and redo (by `javax.swing.undo.UndoManager.UndoManager`)
	+ [X] Copy/paste/cut/select all
	+ [ ] Highlight selected token
+ [ ] Build and execution
	+ [ ] Build as class files
	+ [ ] Build as jar
	+ [ ] Build and run
	+ [ ] Run as class files
	+ [ ] Run as jar
	+ [ ] Run as kotlin script
+ Others
	+ [ ] Build-in documentation
	+ [X] Open alternative editors' download page in browser
