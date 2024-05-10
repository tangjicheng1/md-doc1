# md-doc1

测试github page, 使用mk docs

## 如何设置github pages
在repo的setting里面，设置Pages  

- 设置Source为：deploy from a branch
- 选择gh-pages，/(root)

## 如何设置github action
拷贝ci.yml，在github action中添加即可。

## mkdocs的命令

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## 项目结构

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## 测试代码

```python
from sqlalchemy import create_engine, Column, Integer, String, Sequence
from sqlalchemy.ext.declarative import declarative_base
from sqlalchemy.orm import sessionmaker

# 定义一个基类
Base = declarative_base()

# 定义一个映射类
class User(Base):
    __tablename__ = 'users'

    id = Column(Integer, Sequence('user_id_seq'), primary_key=True)
    name = Column(String(50))
    age = Column(Integer)

    def __repr__(self):
        return f"<User(name={self.name}, age={self.age})>"

# 创建数据库引擎
# 格式：'postgresql://用户名:密码@主机地址/数据库名'
```