react-tutorial-polymer
======================

react-tutorial (https://github.com/petehunt/react-tutorial) reframed as Polymer code 

Notes on similarities:

* roughly the same code size

Notes on differences of opinion in Polymer version:

* emphasis on HTML not JavaScript
* no JavaScript entry point

Notes on improvements in Polymer version:

* no custom syntax (no JSX)
* comment-box is an actual component you could reuse (React version has a manual dependency on showdown that would have to be managed for reuse)

Other differences

* the react version includes node server code that doesn't work with latest express, so I just disabled it instead of debugging
* I eliminated comment-list because simple repeats are primitives in Polymer, this was not stricly necesary

Irregularities

* I committed `components` directly to make this easy to study without getting involved with Bower