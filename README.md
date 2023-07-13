# render.nodes

## Package
```
- lu.pcy113.rn
|- nodes
 |: Node
 |- generate
  |: GenerateNode (No image input, only output)
  |: PerlinNoiseNode -> GenerateNode
 |- filter
  |: FilterNode (Image input & output)
  |: GaussianBlurNode -> FilterNode
  |: MixNode -> FilterNode
 |- utils
  |: UtilsNode
  |: MathNode -> UtilsNode
 |- output
  |: OutputNode
  |: ImageOutputNode -> OuptutNode
|- data
 |: DataContainer
 |- file
  |: File -> DataContainer
  |- scene
   |: Scene -> DataContainer
   |- nodetree
    |: NodeTree -> DataContainer
```
