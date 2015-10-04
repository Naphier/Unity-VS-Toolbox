# Visual Studio 2015 Unity 3D Toolbox
Included in this project is a VS toolbox for most of the Monobehaviour events listed in order of execution. You'll also find a bunch of templates that can be installed so they will show up in the Add Item context menu.

Please note that much of this is also accessible via UnityVS Tools with certain caveats. UnityVS Tools employs a wizard to Implement Monobehaviour Events which some may feel is a little awkward and the events are not listed in order of execution. This toolbox has them listed in order of execution and you can pin it open for quick reference. UnityVS also employs a Quick Monobehaviours window (accessible via Ctrl+Shift+Q) which is pretty nice, but if you know the spelling of the event you're looking for some would agree that a snippet with Intellisense would be faster (no need for the hotkey combo).  

Please feel free to ask to contribute to this project.

#### Issues
* VS doesn't save line endings as CRLF in toolbox text and does a pretty lousy job of keeping tabs straight. Strip 'em is a nice way to address this (see below).
* 

#### Some other tools you might want to consider:
* [UnityVS Tools](https://www.visualstudio.com/features/unitytools-vs) - This should be coming in future updates of Unity in the installer package. This toolbox has some similar features, but UnityVS Tools is important for things like attaching the VS debugger to Unity.
* [Strip 'em](http://www.grebulon.com/software/stripem.php) - This automatically fixes line endings to stop any annoying warnings about this from Unity.