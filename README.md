# xhs_watermark_remover

小红书去广告 Loon 插件（搜索修复版）。

基于 RuCu6 / fmz200 开源基线重建，移除了会导致搜索失败的`移除搜索页广告`脚本
（该脚本改写 `/v10/search/notes` 返回，小红书更新接口格式后会清空搜索结果）。
其余去广告、去水印功能完整保留。

## 安装

Loon → 插件 → 右上角 + → 从链接导入：

```
https://raw.githubusercontent.com/LK1105/xhs_watermark_remover/main/RedPaper_nosearch.plugin
```
