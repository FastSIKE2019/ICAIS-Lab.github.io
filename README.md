# ICAIS-Lab.github.io

## Github 仓库Pull Request 流程

1. Fork 原仓库地址到个人账户, 

      <img src="images/fork.JPG" width=80%>

2. Clone fork仓库到本地
   ```
   git clone https://github.com/xxxx/ICAIS-Lab.github.io
   ``` 
3. 在本地仓库中链接原仓库
    ```
    git remote add upstream https://github.com/ICAIS-Lab/ICAIS-Lab.github.io
    ```
4. 新建分支, 修改本地文件
   ```
   git checkout -b <branchName>
   git status
   git add .
   git commit -m '描述'
   git push origin <branchName>
   ```
5. create pull request

      <img src="images/pull_req.JPG" width=80%>


## 内容修改指南
1. ./members:  存放实验室成员个人主页与图片; 
2. ./researches : 研究课题模板，可以参考添加个人内容;
3. 上述二者如有条目的增删，须在`./members.html`与`./research`中进行调整;
4. `./papers.html`中可以增加文章;
5. `./events.html`中可以增加活动内容;
6. 如有意见/需求，可提**issue**。