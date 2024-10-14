## Links

Plugin repo: https://github.com/nama-gatsuo/AzureKinectForUE

Updated plugin repo: https://github.com/cormacmadden/Kinect-Body-Tracking-Unreal-Engine-Plugin


## Setting up project

Error when opening a project with the plugin:

![Missing Kinect Image Error](./missing-kinect-modules.png)

How to fix? https://www.reddit.com/r/unrealengine/comments/1acndak/the_following_modules_are_missing_or_built_with_a/

- If there are no Source files, an empty C++ class should be created inside unreal engine

- When rebuilding delete .vs, Binaries, Intermediate, Saved and solution files/folders.

![Missing Kinect Image Error](./delete-old-source-artifacts.png)

- Right click the project file and click "Generate Visual Studio project files"

![Missing Kinect Image Error](./generate-vs-project-files.png)


## View plugin content in content browser:

![Missing Kinect Image Error](./show-plugin-content.png)

