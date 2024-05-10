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
