# 🏢 Enterprise Python Project Template

[![CI](https://github.com/lijiahao1996/enterprise-python-template/actions/workflows/ci.yml/badge.svg)](https://github.com/USERNAME/enterprise-python-template/actions)

> 🚀 一套企业级 Python 项目模板，包含自动化测试、代码规范检查、CI/CD 流程和预提交钩子。

---

```bash
## 📦 安装依赖
pip install -r requirements.txt

## ▶️ 运行主程序
python src/main.py

## 🧪 运行测试
pytest

## 🧰 代码检查
flake8 src tests
black src tests

## ⚙️ GitHub Actions
该项目默认启用 CI/CD 工作流，每次推送代码时将自动执行：
✅ 安装依赖
✅ 运行 flake8 和 black 检查
✅ 执行 pytest 单元测试
构建状态徽章会自动更新为 ✅ passing 或 ❌ failing。
请记得将上方徽章中的 USERNAME 替换为你的 GitHub 用户名。
