confetti-engine-fet-windows
=========================

Provides a Windows specific FET executable. FET is a timetabling application 
written by Liviu Lalescu in C++. Confetti is the rethinking of the UI of FET, but 
reusing the FET's algorithm, which generates the timetable.

Confetti is written in Java as an Eclipse RCP application, so the most obvious
way to integrate FET into Confetti in an operating system independent manner was
to use Eclipse's fragment technology.

This repo is included into the main Confetti repo as a git submodule. The release
of a new version of FET by Liviu means to delete and to recreate this repo
with the new executable. In this way we can avoid the unnecessary size increment
of the main Confetti repo.

At the moment the following engines are supported by Confetti:

Engine	|OS 	 | Repo
--------|--------|-------------------------------------------------------
FET	|Linux	 | https://github.com/karandit/confetti-engine-fet-linux
FET	|Windows | https://github.com/karandit/confetti-engine-fet-win32
FET	|OS X	 | https://github.com/karandit/confetti-engine-fet-osx
 
