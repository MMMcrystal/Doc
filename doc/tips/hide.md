## 单行元素多余隐藏

    white-space: nowrap;
    text-overflow:ellipsis;
    overflow:hidden;

## 多行元素多余隐藏

    overflow : hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 1;/_第一行不换行_/
    -webkit-box-orient: vertical;
