# MIDI Redux

This is a sandbox project to learn the following concepts:

* How Redux works
* How React works
* How to integrate React & Redux
* How MIDI works (harder than expected)

## Schema

![MIDI-Redux schema](MidiRedux.png)

## Installation

1. Install packages
```
$ npm install && bower install
```

1. Compile:
```
$ webpack
```

3. Run:
```
 webpack-dev-server --progress --colors --watch
```

4. Open [http://localhost:8080/webpack-dev-server/](http://localhost:8080/webpack-dev-server/)

## Load instruments

5. If you want to load your own instruments or load local files, you can change the configuration in `src/config/instruments-path`. I am using this project the sounds from this project: [Soundfont](https://github.com/gleitz/midi-js-soundfonts)

6. Find a great midi song on the Internet:
  * http://www.midiworld.com/files/
  * https://freemidi.org/
  * etc...

7. Load your .mid file and play it!


## Screenshot

![Midi Redux Interface](midi-redux-example.png)

## Redux DevTools

![Redux DevTools](midi-redux.gif)

**FEEDBACK & HELP are super welcome**. It's my first project using React&Redux. I think it could be a very beautiful project :)
