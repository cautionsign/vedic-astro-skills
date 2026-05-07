# 报告打包规则

> 用途：当用户说"生成报告""打包""导出HTML"时执行

---

## 打包命令

```python
# 打包全部已有文件
python scripts/report_builder.py [工作目录] --lang cn

# 只打包core
python scripts/report_builder.py [工作目录] --include core --lang cn

# 只打包core + career
python scripts/report_builder.py [工作目录] --include core,career --lang cn
```

report_builder自动检测目录中存在哪些MD文件，只打包存在的。
`--include`参数可选择只打包特定部分。
