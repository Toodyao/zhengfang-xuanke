# 说明
由 https://github.com/xiaohuanshu/zhengfang-xuanke fork而来

在此基础上修改了xuanke.py，适应本校教务系统

pingjia.py等下次评教的时候再改

原版本只支持Python 2.7

内网下使用


感谢原作者

# 依赖库
* PyQuery
* PIL/Pillow

# 修改内容
* host为本校网址
* 修改错位问题
* 取消教材的爬取
* 部分交互优化

# 已知问题
* 只能抓取200个课程
* 可能会有乱码

------

欢迎提issue或fork

------

---以下为原README---

```
# zhengfang-xuanke
正方教务系统刷课/评价工具

# 自动刷课xuanke.py目前功能
* 自动刷课
* 验证码登录
* 课程信息查询
* 失败重试
* 是否选择教材

# 自动评价pingjia.py目前功能
* 自动评价
* 将一个评价设为『比较满意』其余为『非常满意』从而防止全部相同而无法保存
 
# 使用方法
* 安装pquery(pip install pquery)
* 验证码显示需要安装pillow,没安装jp2a的在根目录找二维码
* 编辑修改host为正方教务系统地址
* 如果登录时报错，尝试更改loginpage为default5.aspx或者default3.aspx
```
