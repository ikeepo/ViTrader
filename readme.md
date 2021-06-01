# TextTrader操作手册

​       版本1.0
   krenx@qq.com

### 移动命令（所有窗口通用）： 

​	上下左右：j、k、h、l及四个方向键
​	翻页：f、b、u、d，支持上下翻页键，同时也支持^f、^b、^u、^d，即按住Control键
​	上下行滚动：y、e，同时也支持^y、^e，即按住Control键
​	屏幕顶部、中间、底部：H、M、L
​	列表的开头、结尾：gg、G

### 选择合约：/

​	主窗口及下单窗口下，按/键将在右下方显示合约选择窗口
​	输入合约号，会自动匹配，按Enter键确认
​	可按ESC键取消，其它见小窗口命令

### 调整列显示：v

​	主窗口下按’v’键进入列调整窗口，可通过’j’、’k’键上下定位列，按空格键显示或取消显示列，按’+’、’-‘键调整列位置
​	按ESC键返回主窗口

### 显示合约交易参数：空格

​	主窗口下按空格键进入选定合约交易参数显示窗口 
​	按ESC键返回主窗口

### 小窗口命令：

​	上下移动：^p、^n、方向键
​	删除：^h 或者 BackSpace 都可以删除输入字符

### 窗口切换（支持F1~F9功能键，F2、F3暂保留）：

​	主窗口：1gt及F1
​	下单窗口：Enter回车键、4gt、F4进入光标所在行的合约下单窗口
​	持仓窗口：5gt、F5
​	资金窗口：6gt、F6
​	订单窗口：7gt、F7
​	成交窗口：8gt、F8
​	日志窗口：9gt、F9

### 下单操作：下单界面

​	买卖方向选择：h、l及左右方向键，即左右移动到买/卖列
​	价格选择：j、k及上下方向键及翻页键等，即上下移动相应价格格子
​	下单：i（限价单），I（大写i为市价单）
​	撤单：u（撤消所在格子的订单，同方向相同报价的所有订单都将被撤消）
​	全部撤消：U（撤消当前商品的全部挂单）
​	改单：x==>p（先将光标移动到订单位置，按x键，然后移动到新价格，再按p键即可，中间可按ESC键取消操作）
​	反手（多空方向转换）：r（以对手价反手）、R（以涨跌停价反手）

### 多次执行：

​	一次向下移动多行：数值+j，如先按3，再按j，表示向下移动3行。
​	一次下单N手：数值+i，如先按5，再按i，表示报入5手。
​	大多数命令都可以这么用：数值+操作