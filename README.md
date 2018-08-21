# go-b2dJson
Loader, written in Go, for scenes created by the R.U.B.E Box2D editor.

## Usage

```go
// [...] Game init
scene := NewB2DJsonSceneFromFile("scenes/scene.json")
b2World := scene.World

// [...] Game loop
b2World.Step(1/scene.StepsPerSecond, scene.VelocityIterations, scene.PositionIterations)
```

## Links
* [R.U.B.E Json format](https://www.iforce2d.net/rube/json-structure)
* Loader for other languages https://github.com/iforce2d/b2dJson
* Information about the original loader here http://www.iforce2d.net/b2djson
