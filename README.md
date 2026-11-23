# pairwise-texture-residency

## 领域

游戏、图形与多媒体

## 主题

纹理驻留与淘汰

## 说明

引用计数、代际校验与去重上传。

初始状态下 `graphics/texture_residency.py` 中所有函数抛出 `NotImplementedError`，测试全部失败。
修复实现后运行：

```bash
python -m pytest -q
```

期望全部通过。
