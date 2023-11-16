# godot-html-export
Github Action for Godot HTML5 export.  
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
| working-directory | false | . | Path to project.godot file |
| godot-create-export-preset-cfg | false | true | Set true if a simple export_presets.cfg should be created |
| working-directory | false | html5/index.html | Path of the exported html files |
| godot-version | false | 4.1.1 | Check versions [here](https://downloads.tuxfamily.org/godotengine/) |


## Working examples
You an find a working examples here:  
https://github.com/dulvui/ball2box/blob/main/.github/workflows/upload-itchio.yml

## License
This software is licensed under the [MIT license](LICENSE).