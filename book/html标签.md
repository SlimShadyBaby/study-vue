# HTML标签

## 行内标签

1. 标题

    ``` html
        <h1> xxx </h1>
    ```

2. 组合行内元素

    ``` html
        <span> xxx </span>
    ```

3. 超链接
    target的4个值
    * _blank：浏览器总在新打开、未命名的窗口中载入目标文档
    * _self: 默认值,当前窗口打开
    * _parent: 父窗口打开，如果当前窗口是顶层，和_self效果一致
    * _top: 清楚所有，在当前浏览器窗口打开

    ``` html
        <a herf="xxx" target="_self"> xxx </a>
    ```
