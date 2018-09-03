# Firebase Xcodeproj
Firebase only supports integrating their dependencies through CocoaPods or prebuilt static frameworks. The purpose of this repo is simply provide an xcodeproject containing the targets and sources of each Firebase dependency as both dynamic and static libraries. This way, one can now consume them using `git submodules` or just downloading and dragging into their existing project.

## Details/Updating
This is done by simply leveraging the generated `Pods.xcodeproj` from CocoaPods and checking that in. Updating is as easy as running `pod install` and then checking in the new project file.
