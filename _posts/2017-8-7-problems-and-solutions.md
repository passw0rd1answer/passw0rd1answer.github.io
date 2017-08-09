## 点击启动服务器没有没有界面出现
- **解决方案**

检查方案里面的路径和使用的套帐连接问题，之后去runtime目录下检查server.xml是不是为空

------------------


## 审核和反审核按钮不可操作
- **解决方案**

##### 将审核和反审核按钮的Enabled和Viable的属性设置为true

##### 然后重写onLoad（）方法，分别将this.actionAudit和actionUnAudit的setEnabled和setViable的属性设置为false**
-------------------
