Kore.aiのボット管理者においてボットのタスクをすべてアンチェックする

ブックマークレットはこちら
```javascript
javascript:Array.from(document.getElementsByClassName("items__list")[0].children).forEach((list)=>{list.querySelectorAll('label')[0].classList.remove('checked');list.querySelectorAll('input')[0].value=false;});
```