# Big Niu

一个 Python 项目模板

## 简介

Big Niu 是一个 Python 项目，旨在提供一个清晰、规范的项目结构和开发环境配置。

## 特性

- 🐍 基于 Python 3.x
- 📦 完善的依赖管理
- 🧪 单元测试支持
- 📝 代码规范检查
- 🔧 开发环境配置

## 安装

### 环境要求

- Python 3.8+
- pip 或其他 Python 包管理工具（如 poetry、pdm、uv 等）

### 安装依赖

使用 pip：

```bash
pip install -r requirements.txt
```

或使用 poetry：

```bash
poetry install
```

或使用 pdm：

```bash
pdm install
```

## 使用

```python
# 在这里添加使用示例
```

## 开发

### 环境配置

1. 克隆仓库：
```bash
git clone https://github.com/Lyshen/big-niu.git
cd big-niu
```

2. 创建虚拟环境：
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# 或
venv\Scripts\activate  # Windows
```

3. 安装开发依赖：
```bash
pip install -r requirements-dev.txt
```

### 代码规范

本项目使用以下工具保证代码质量：

- **Black**: 代码格式化
- **Ruff**: 代码检查和格式化
- **mypy**: 类型检查
- **pytest**: 单元测试

运行代码检查：

```bash
# 使用 Ruff 检查代码
ruff check .

# 使用 Black 格式化代码
black .

# 运行类型检查
mypy .
```

### 测试

运行测试：

```bash
pytest
```

运行测试并生成覆盖率报告：

```bash
pytest --cov=. --cov-report=html
```

## 项目结构

```
big-niu/
├── .gitignore          # Git 忽略文件配置
├── README.md           # 项目说明文档
├── requirements.txt    # 项目依赖
├── requirements-dev.txt # 开发依赖
├── pyproject.toml      # 项目配置文件
├── src/                # 源代码目录
│   └── __init__.py
└── tests/              # 测试目录
    └── __init__.py
```

## 贡献

欢迎贡献代码！请遵循以下步骤：

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 开启 Pull Request

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 联系方式

- 项目维护者: [@Lyshen](https://github.com/Lyshen)
- 项目地址: [https://github.com/Lyshen/big-niu](https://github.com/Lyshen/big-niu)

## 致谢

感谢所有为本项目做出贡献的开发者！
