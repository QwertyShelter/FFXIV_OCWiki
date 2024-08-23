# **莎莉雅·娜爱**
!!! warning "尚未补全，正在施工"

<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>两端对齐的无序列表</title>  
<style>  
  /* 样式化无序列表 */  
  ul {  
    list-style-type: none; /* 移除默认的列表项标记 */  
    padding: 0; /* 移除默认的填充 */  
    margin: 0; /* 移除默认的边距 */  
    
  }  
  
  /* 样式化列表项 */  
  li {  
    text-align: justify; /* 尝试两端对齐文本 */  
    margin-bottom: 10px; /* 在列表项之间添加一些垂直间距 */  
    /* 你可能还需要添加一些额外的CSS来处理较短的行，比如设置伪元素来强制最后一行对齐 */  
  }  
  
  /* 伪元素技巧来强制短行两端对齐（可选） */  
  li:after {  
    content: "";  
    display: inline-block;  
    width: 100%; /* 强制容器宽度与父元素相同 */  
  }  
</style>  
</head>  
<body>  
  
<ul>  
  <li>这是一个两端对齐的列表项，它包含足够的文本来显示两端对齐的效果。</li>  
  <li>另一个列表项，它也应该被两端对齐，但请注意，如果文本太短，两端对齐可能看起来不自然。</li>  
  <!-- 添加更多列表项进行测试 -->  
</ul>  
  
</body>  
</html>