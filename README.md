中文 / [English](README.en.md)

## 关于

neatlogic-parent用于管理整个neatlogic项目各个包的引用版本。

为了同时兼容生产环境和开发环境的引用，neatlogic-parent永远只有release版本，每次修改pom文件都需要提升一次小版本号，刷新maven缓存。

pom文件中自带develop和release两个profile，调试时根据需要调整。