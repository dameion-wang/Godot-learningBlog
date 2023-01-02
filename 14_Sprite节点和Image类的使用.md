- CanvasItem节点，继承关系为：CanvasItem -> node -> Object
```
- Canvas是画布的意思，所以CanvasItem代表的就是可以被绘制的节点，可以设置可视化界面和材质的颜色
- 所有的2D节点和GUI节点都继承于CanvasItem节点
```
- Sprite节点，继承关系为：Node2D -> CanvasItem -> Node -> Object
```
Sprite节点可以显示图片，但是不能直接编辑图片
```
- Texture类，继承关系为：Resource -> Reference -> Object
```
- Texture贴图，附加到物体表面的贴图，实际上就是包含一张Image图片
- 可以用在3D模型中当作贴图，或者2D的Sprite中当作图片，或者GUI的背景
```
- Image类，继承关系为：Resource -> Reference -> Object
```
- 包含了图片的原始数据，可以直接进行编辑
```
