# 节点操作 {#node-manipulation}

## 自定义节点 {#custom-node}

有两种自定义节点的方式：

1. 传入具名插槽 `node`
2. 使用 `render` Prop

<CodeDemo component="CustomNode" />

## 拖拽 {#drag-and-drop}

启用 `draggable` 与 `droppable` 可实现拖拽功能

<CodeDemo component="DragAndDrop" />

## 节点新增与删除 {#node-creation-and-removal}

- 调用树组件的 `insertBefore`, `insertAfter` 方法，可在节点前后插入新的节点
- 调用树组件的 `prepend`, `append` 方法，可插入新的节点到子节点列表的最前面或最后面
- 调用树组件的 `remove` 方法，可移除节点

<CodeDemo component="NodeCreationAndRemoval" />
