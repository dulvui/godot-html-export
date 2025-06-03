# ARCHIVED
This action has been archived and will no longer be maintained.
Please create your own fork.

# godot-html-export
Github Action for Godot 3.x HTML5 export.  
If you are facing problems with the action or this README feels not complete, pull requests are welcome or open an issue.

Also available for Godot Engine 4.x here  
https://github.com/dulvui/godot-4-html-export

## Table of contents
- [godot-html-export](#godot-html-export)
  - [Table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Parameters](#parameters)
  - [Working examples](#working-examples)
  - [License](#license)

## Requirements
 - Godot Project

## Parameters
| key | required | default | description |
| ----|----------|---------|-------------|
| godot-version | true | . | Godot Engine version. Supported are 3.x versions. Check versions [here](https://github.com/godotengine/godot-builds/releases) |
| working-directory | false | . | Path to project.godot file |
| godot-create-export-preset-cfg | false | true | Set true if a simple export_presets.cfg should be created |
| working-directory | false | html5/index.html | Path of the exported html files |


## Working examples
You an find a working examples here:  
https://github.com/dulvui/ball2box/blob/main/.github/workflows/upload-itchio.yml

## License
This software is licensed under the [MIT license](LICENSE).
