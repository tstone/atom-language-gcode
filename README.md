# language-gcode package

Converted and modified from: https://github.com/brendanjerwin/gcode.tmbundle

Forked from: https://github.com/audreyt/atom-language-gcode

## Screenshot
![screenshot](https://raw.githubusercontent.com/tstone/atom-language-gcode/master/screenshot.png)

## Customization

It's possible to further customize the presentation as G and M codes are sub-parsed into different categories.  The following can be added a `styles.less`:

```
atom-text-editor::shadow .gcode.speeds {

}

atom-text-editor::shadow .gcode.canned {

}

atom-text-editor::shadow .gcode.coordinate {

}

atom-text-editor::shadow .gcode.compensation {

}

atom-text-editor::shadow .gcode.motion {

}

atom-text-editor::shadow .gcode.other {

}

atom-text-editor::shadow .gcode.linenumber {

}

atom-text-editor::shadow .mcode.coolant {

}

atom-text-editor::shadow .mcode.spindle {

}

atom-text-editor::shadow .mcode.program {

}

atom-text-editor::shadow .mcode.other {

}

atom-text-editor::shadow .gcode.parameter {

}
```
