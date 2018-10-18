# checkAllNodes

勾选或取消勾选全部节点。只有 setting.check.enable = true 且 setting.check.chkStyle = "checkbox" 时有效。此方法不会触发 beforeCheck / onCheck 事件回调函数。

### 说明
    ZTreeObj.checkAllNodes(checked)

### 参数
#### checked
checked = ture 表示勾选全部节点  
checked = false 表示全部节点取消勾选  
不会影响 treeNode.nocheck = true 的节点  
不会影响未加载的节点  
(Boolean)  

### 返回值
无
























