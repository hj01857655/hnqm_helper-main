# 自动刷课程序


## 项目说明
 - 本项目由[csmu241965](https://github.com/hj01857655)开发
 - 本项目是基于项目[JesterHey](https://github.com/JesterHey/hnqm_helper)的修改

这是一个自动化的刷课程序，能够自动登录、刷课、交作业和考试。该程序使用 Python 编写，并依赖于 DrissionPage 库来进行浏览器自动化操作。

## 功能
- 自动登录到hnnmgc学习平台
- 自动学习课程,包括必修课和选修课
- 自动提交作业和考试
- 自动评分

## 目录结构

- `main.py`：程序的主入口，负责初始化和执行刷课流程。
- `get_info.py`：负责获取课程信息和登录操作。
- `initialization.py`：初始化模块。
- `kill_course.py`：负责执行刷课操作。
- `info.json`：存储用户的账号信息。
- `requirements.txt`：项目依赖的Python库。
- `README.md`：项目说明文件。

## 使用方法

1. **安装依赖**：确保你已经安装了 Python 3.12，并使用以下命令安装项目依赖：

   ```bash
   pip install -r requirements.txt
   ```windows
   pip install -r requirements.txt

   **安装Chrome浏览器**：
   ```bash
   # 安装Chrome浏览器
   sudo apt-get install chromium-browser
   ```windows
   https://www.google.com/chrome/

2. **配置账号信息**：在 `get_info.py` 中直接设置你的账号和密码。

3. **运行程序**：在命令行中运行 `main.py`：

   ```bash
   python main.py
   ```

## 常见问题

- 请确保你的浏览器路径已正确配置，并且浏览器可以正常启动。
- 该程序仅供学习和研究使用，请勿用于任何违反法律法规的用途。

## TODO
-
## 贡献
欢迎对本项目进行贡献！如果你有任何建议或改进，请提交 Pull Request(https://github.com/hj01857655) 或 Issue。

## 许可证

本项目采用 MIT 许可证。

## 致谢
- 感谢[JesterHey](https://github.com/JesterHey/hnqm_helper)提供的项目基础

## 免责声明
- 本项目仅供学习和研究使用，请勿用于任何违反法律法规的用途。
- 本项目不承担任何法律责任。
- 本项目不保证学习的稳定性，不保证学习的成功率。
- 使用程序即代表你同意以上条款,原作者对使用本程序造成的任何后果不承担任何责任。

