### 第一天
#### git命令
   - 拉取远端代码 : git pull
   - 查看代码状态 : git status
   - 添加代码 : git add
   - 暂存 : git commit
   - 提交 : git push
### 事件代理（事件委托）
~~~ js
 //原生js写法
      var ul = document.getElementsByClassName('class-list')[0];
      ul.addEventListener('click',function(e){
        debugger
        if(e.target && e.target.nodeName.toUpperCase() == 'LI'){
          alert('li 被点击了');
        }
      })

      //jq的写法
      $(father).delegate('children','event',function(){
         
      })
~~~