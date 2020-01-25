# 服务器领地指令
## 基础指令  
* /res ? <页码>  
  展示领地命令帮助(英文)

## 选择指令  
* /res select <x y z>  
  使用选择工具(木斧)或将X，Y和Z指定为距您站立的中心点的那些轴上的距离，选择要保护的长方体区域("10 5 10"将选择一个区域 21宽 11高 21长)
* /res select chunk  
  选择整个区块进行保护
* /res select expand <距离>  
  朝着视线的方向扩展领地
* /res select size  
  展示选择的区域的大小
* /res select shift <距离>  
  将选择移向看的方向
* /res select vert  
  将选择范围从天空扩展到基岩

## 创建指令
* /res area [add/remove/replace] <领地名>  
  在领地中添加或删除区域。 这些可以与同一领地重叠
* /res create <领地名>  
  创建一个领地
* /res remove <领地名>  
  删除一个领地
* /res removeall  
  删除你所拥有的所有领地
* /res subzone <子领地名>  
  在领地中创建子领地，您必须是领地的所有者才能执行此操作

## 信息指令
* /res area list <领地名>  
  列出一个领地内的所有区域
* /res area listall <领地名>  
  列出领地及其坐标
* /res current  
  显示目前所在领地
* /res info  
  获取有关领地的信息，离开领地以查看有关您所站在的领地的信息
* /res list  
  显示拥有的所有领地
* /res listall  
  显示所有领地
* /res limits  
  列出所有重要限制
* /res sublist  
  列出当前领地的所有分领地

## 权限指令
* /res gset <组名> <权限> <true/false/remove>  
  给不同的组设置权限
* /res lset <blacklist/ignorelist> <方块>  
  向领地的黑名单/白名单添加/删除方块
* /res lset info  
  显示领地的黑名单/白名单设置
* /res pset <玩家名> <权限> <true/false/remove>  
  给不同的玩家设置不同的权限
* /res set <权限> <true/false/remove>  
  给领地设置权限

## 实用程序命令
* /res expand <数量>  
  将你所在的领地向视线方向扩展一定的数量
* /res contract <数量>  
  将你所在的领地向视线方向减少一定的数量
* /res default <领地名>  
  将领地权限重置为默认
* /res give <领地名> <玩家名>
  将领地给另一名玩家，另一位玩家必须在线
* /res lists  
  预定义的领地权限列表，执行命令查看更多信息
* /res message <领地名> <enter/leave> <消息>
  给领地设置进入/离开消息
* /res rename <旧名> <新名>  
  给一个领地重命名。对于子领地，旧名必须为全名，即`父领地.子领地`