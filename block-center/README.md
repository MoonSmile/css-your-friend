[CSS实现块级元素水平垂直居中](https://blog.csdn.net/Hanhanyoona/article/details/84550507?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param)

### 方法一:
父级元素position:relative, 子元素position:absolute;top:0;left:0;bottom:0;right:0;margin:auto;

### 方法二:
父级元素position:relative, 子元素position:absolute;top:50%;left:50%;margin-left:-(子元素宽度的一半);margin-top:-(子元素高度的一半);

### 方法三:
使用transform:translate(-50%, -50%);

### 方法四:
使用flex布局 align-items: center;

### 方法五:
使用flex布局 flex-direction: column;align-self: center;

### 方法六:
display:table