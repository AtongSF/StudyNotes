# 为什么使用v-for时必须添加唯一的key?

key是作为

使用 v-for 更新已渲染的元素列表时,默认用`就地复用`策略;列表数据修改的时候,他会根据key值去判断某个值是否修改,如果修改,则重新渲染这一项,否则复用之前的元素

xu'ni