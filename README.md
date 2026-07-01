# Unigine

This is a MIT licensed publically available collection of Unigine scripts for personal and commercial use.

## Description

The C# scripts in this repository are intended to be copied and used as source code for Unigine node components.  Currently there are component scripts supporting Skinned Mesh animations, and scripts adding support for playback of Tracker animations.

BasicAnimation.cs and CharacterAnimation.cs are intended to be used as components on an ObjectMeshSkinned node providing an accessible interface for state management of mesh bone animations.

Tracker.cs can be used as a component on a dummy node providing an interface for playback of animations created with the Tracker tool.  Additionally, tracker_wrapper.usc is a required UnigineScript which provides the "glue" required for Tracker.cs.  In order to use Tracker.cs to play back Tracker animations, use tracker_wrapper.usc as the world script in each world tracker animations are to be played.

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/webnetweaver/Unigine/blob/master/AnimationGuide.md)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
