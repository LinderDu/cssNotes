## 层叠上下文

元素提升为一个特殊的图层，在三维空间中称之为`（z轴）`高出普通元素一层

### 触发条件

- 根层叠上下文（`html`）
- `position` 定位与`relative`和`absolute`无关，元素同级，谁在前谁在上
- CSS3 属性
    - flex
    - transform
    - opacatiy
    - filter
    - will-change
    - -webkit-overflow-scrolling

### 层叠等级

层叠上下文在z轴上的排序

- 在同一层叠上下文中，层叠等级才有意义
- `z-index` 优先级最高

![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F5e28e3e0-6b0b-4d60-bc52-d4e0162c6d1a%2FUntitled.png?table=block&id=679dbcdd-7a3e-4000-9ea8-0d63a5814861&width=1340&cache=v2)




