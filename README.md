# ERD Preview

An extension for Visual Studio Code to preview ERD (Entity-relationship diagram) files.

## Preview

![Preview](https://github.com/kaishuu0123/vscode-erd/blob/master/vscode-erd-demo.gif)

## Configuration

Make sure the extension can find the "erd" and "dot" program. <br/>
You can set `erd-preview.erdPath` and `erd-preview.dotPath` option. <br/>
Please edit settings.json. ([File] -> [Preference] -> [Settings])

## Requirements

Use this extension require `erd` and` dot` program.

You can get `erd` Program here.

* Single binary my project
    * https://github.com/kaishuu0123/erd-go/releases
* BurntSushi erd
    * https://github.com/BurntSushi/erd

You can get `dot` Program here.

* Single binary my project
    * https://github.com/kaishuu0123/graphviz-dot.js/releases
* Official Graphviz dot program
    * http://www.graphviz.org/download/

## Usage

1. write erd file ( example: https://github.com/kaishuu0123/erd-go/blob/master/examples/simple.er )
1. Press `Ctrl+Shift+p` (windows) or `Command+Shift+p` (Mac) and select `ERD Preview`

## Known Issues

## Release Notes

-----------------------------------------------------------------------------------------------------------
