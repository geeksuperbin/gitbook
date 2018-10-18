# addNodes

添加节点

### 说明
    ZTreeObj.addNodes(parentNode,[index],newNodes,isSilent)

### 参数
#### parentNode
指定的父节点，如果增加根节点，请设置 parentNode 为 null 即可。(JSON)

#### [index]
新节点插入的位置(从 0 开始)，index = -1 时，插入到最后，此参数可忽略(Number)

#### newNodes
需要增加的节点数据 JSON 对象集合，数据只需要满足 zTree 的节点数据必需的属性即可，详细请参考「treeNode 节点数据详解」(JSON/Array(JSON))

#### isSilent
设定增加节点后是否自动展开父节点(Boolean)，isSilent = true 不展开父节点，其他值或缺省状态都自动展开。

### 返回值
zTree 最终添加的节点数据集合Array(JSON)























