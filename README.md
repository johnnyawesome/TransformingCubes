# TransformingCubes
A single cube that transforms itself into a big cube, written in JavaScript using P5JS.

![TransformingCubesRotating](https://raw.githubusercontent.com/johnnyawesome/TransformingCubes/master/TransformingCubes/DemoImages/TransformingCubesRotating.gif)

## About the Project

This is a continuation of my [ShiftingCubes Project](https://github.com/johnnyawesome/ShiftingCubes)!

It uses the same codebase. For mor information, read my [blogpost](https://breaksome.tech/coding-shifting-cubes-in-p5js/) where I explain the code step-by-step.

## How to use

There are several settings giving you full control over the cube:

```js
//Rotate the cubes when transforming
const rotateCubes = false;
//Size of the cubes
const cubeSize = 60;
//Distance between cubes
const cubeDist = 0.0001;
const delta = cubeSize + cubeDist;
//Length in cubes of one side (e.g. '5' will produce a 5 x 5 x 5 cube)
const cubeNum = 5;
```

The one that makes the most difference is this one:

```js
//Rotate the cubes when transforming
const rotateCubes = false;
```

If you set it to 'false' you'll get this animation:

![TransformingCubesNoRotating](https://raw.githubusercontent.com/johnnyawesome/TransformingCubes/master/TransformingCubes/DemoImages/TransformingCubesNoRotating.gif)

Set it to 'true' to get this:

![TransformingCubesRotating](https://raw.githubusercontent.com/johnnyawesome/TransformingCubes/master/TransformingCubes/DemoImages/TransformingCubesRotating.gif)

Enjoy!
