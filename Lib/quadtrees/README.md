# QuadTrees
V1.0.4
[Newest Versions Available here](https://github.com/splitice/QuadTrees)
https://github.com/splitice/QuadTrees

High Performance Quad Tree Implementations for C# (Point, Rect and PointInv).

NuGet packages published for dotnetcore 3.1

## Example

```
QuadTreeRect<QTreeObject> qtree = new QuadTreeRect<QTreeObject>();
qtree.AddRange(new List<QTreeObject>
{
	new QTreeObject(new RectangleF(10,10,10,10)), // Expected result
	new QTreeObject(new RectangleF(-1000,1000,10,10))
});

var list = new List<QTreeObject>();
qtree.GetObjects(new RectangleF(9, 9, 20, 20), list);
```

## License

Since version v1.0.3 licensed under the Apache License