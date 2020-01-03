# harness

## In Process

Mobile
- use gomobile bind.

Desktop
- just use standard go-plugins.

## Out of Process

Mobile

- needs work but not too hard.

- Not sure how a App Manifest can model its dependency on a Background Service. If many apps need the same background Service then is the Service installed in all GUI Apps Or does the OS manage it at runtime ?


Desktop

- system tray works well and avoids admin rights. Google does this for Google Chrome and just sets a startup flag in the users account.

	- this means that each OS user is 100% segregated and so you can hand your laptop to someone else using it and they can see any of your data or even the binaries.


## Useful

Bazel 
gomobile: https://github.com/znly/rules_gomobile
go: https://github.com/bazelbuild/rules_go
dart: NONE FOUND: Watch here: https://github.com/bazelbuild/bazel/issues/10207


