# 离开当前标签时, 改变标签的内容
### 离开时
![blur](https://github.com/NLxs/title_content_change/blob/main/blur.png)
### 返回时
![focus](https://github.com/NLxs/title_content_change/blob/main/focuss.png)
### 代码内容
```
let title = document.title;
window.addEventListener("blur", ()=> {
  document.title = "我会等你回来的~";
});
window.addEventListener("focus", ()=> {
  document.title = title;
});
```
