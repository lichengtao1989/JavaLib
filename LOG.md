# 更新日志

格式：

```
:star: Feature

:bug: Bug
```

## v2.1.6

2021.12.08

:star: Feature

- 新增获取年的方法：DateTimeUtils.getYear()
- DateTimeUtils 转换成时间戳 增加对 `null` 的处理


## v2.1.5

2021.12.03

- 【新增】新增命名工具类，提供下划线和驼峰命名转换方法。
- 【新增】新增DateTimePattern常量类。
- 【新增】新增FormatterUtils工具类。
- 【新增】新增发布 `shell` 命令。
- 【修复】修复打包插件依赖报错的问题。
- 【优化】JsonUtils，优化对日期时间的规范化处理。
- 【升级】fasterxml.jackson -> 2.13.0。
- 【升级】google-thumbnailator -> 0.4.14。
- 【升级】transmittable-thread-local -> 2.12.2。
- 【升级】maven-source-plugin -> 3.2.1。
- 【升级】maven-javadoc-plugin -> 3.3.1。
- 【升级】maven-gpg-plugin -> 3.0.1。

## v2.1.4

2021.08.25

- 【新增】新增构造者接口：IBuilder
- 【优化】对README中功能列表部分进行了优化