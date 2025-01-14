# contactPutianHospital

<div align="center">
    <a href="https://github.com/ehnait/contactPutianHospital/releases" target="_blank">
        <img alt="GitHub release (with filter)"
             src="https://img.shields.io/github/v/release/ehnait/contactPutianHospital"></a>
    <a href="https://github.com/ehnait/contactPutianHospital/issues" target="_blank">
        <img alt="GitHub issues" src="https://img.shields.io/github/issues/ehnait/contactPutianHospital"></a>
    <a href="https://github.com/ehnait/contactPutianHospital/issues?q=is%3Aissue+is%3Aclosed" target="_blank">
        <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/ehnait/contactPutianHospital?color=%23A400C8"></a>
    <a href="https://shields.io/" target="_blank">
        <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/ehnait/contactPutianHospital"></a>
</div>

## 说明

本项目通过在百度上爬取「莆田系医院」这一营销组件的企业的网址, 然后模拟浏览器将目标手机号发送给企业，让企业销售给目标联系人打电话。

- 此项目借鉴[callPhoneBoom](https://github.com/olyble/callPhoneBoom)
  ，使用[DrissionPage](http://g1879.gitee.io/drissionpagedocs/)简化浏览器操作流程并对边界情况进行了处理。
- 重写catch.py脚本，获取api更丝滑了，[api列表更新](api.txt)

## Feature

主动帮助坏蛋蛋联系 **莆田系医院** 并留下电话号码。此举深藏功与名，每联系一次都会使你 **功德+1**

1. **main.py**：通过程序模拟浏览莆田系医院网址，自动发送目标手机号给企业 。
2. **scheduler.py**:设置定时任务
3. **catch.py**:批量爬取莆田系医院网址

## 使用教程

1. 克隆或下载你的代码到本地。
2. 创建一个新的虚拟环境（可选）。
3. 在终端或命令提示符下进入项目目录，并激活虚拟环境（如果有）。
4. 运行以下命令来安装依赖项：
   ```
   pip install -r requirements.txt
   ```
5. 查看 **main.py**的注释， 确保配置正确 ，运行 **main.py**

## 更新记录

[👉看这里👈](https://github.com/ehnait/contactPutianHospital/releases)

## 运行截图

![](imgs/img1.png)

## 免责声明

1. 若使用者滥用本项目,本人 **无需承担** 任何法律责任.
2. 本程序仅供娱乐,源码全部开源,**禁止滥用** 和二次 **贩卖盈利**.  **禁止用于商业用途**.
