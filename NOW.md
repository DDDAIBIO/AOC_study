# NOW — 断点卡片

> 规则：开始前写「今天要做」，结束时改成「下次从…继续」。第二天不用回忆，直接开工。

## 今天要做（2026-10-16 · D1）

- [x] 建知识库骨架 + 首次提交
- [x] 仓库推送到 GitHub（远端现为 `oligo-kb-202610`，从 AOC_study 改名/迁移；首次 push 因远端 Initial commit 被拒，已用 merge -X ours 解决；D1 commit `b287930` 待 push，已切 origin 到新 URL）
- [x] Nusinersen（Spinraza）说明书已抓取整理 → `99_原料/Nusinersen_Spinraza_label_要点.md`
- [ ] 下载 Khvorova & Watts 2017 综述 PDF 到 `99_原料/`（PMC5517098）
- [ ] 读摘要 + Figure 1（10 min，不求全懂）
- [ ] 术语表记 3 条，commit 一次

## 今晚的 20 分钟（按这个顺序）

1. 浏览器打开 https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5517098/ → 存 PDF 到 `99_原料/Khvorova_2017_chemical-evolution.pdf`
2. 只读 **摘要 + Figure 1**（Figure 1 是寡核苷酸化学修饰的演化时间线，重点看修饰类型出现的先后顺序和它们解决的问题）
3. 术语表加 3 条（推荐起步：PS 硫代磷酸 / 2′-MOE / gapmer）
4. `git add -A && git commit -m "D1: 术语 + 材料"` → VSCode 点 Sync

## 下次从这继续（D2 · 周六 10-17 · ASO 机制，2h）

- 主读 Khvorova & Watts 2017 的 ASO 章节，搞清两条线：
  - **RNase H 降解（gapmer）**：为什么中间必须是 DNA gap、翼部必须是修饰 RNA
  - **剪接调控（立体位阻）**：Nusinersen 如何让 SMN2 带上 exon 7、产出全长 SMN 蛋白
- 案例拆解 1/3：Nusinersen —— 材料已在 `99_原料/Nusinersen_Spinraza_label_要点.md`
- 产出：`02_技术方案/ASO机制笔记_v0.md` + 对比表第 1 行

### D2 拆解时这几个数字值得自己先算一遍（label 里有）

- 分子式 `C234H323N61O128P17S17Na17`、MW 7501 Da → **P/S 各 17 个 → 18 个核苷酸**（nusinersen 是 18-mer）
- CSF 半衰期 **135–177 天**、血浆 63–87 天 → 说明为什么维持期是 **每 4 个月** 一次
- 化学：2′-O-2-methoxyethyl（2′-MOE）+ 全长硫代磷酸（PS）
- 靶点：SMN2 **exon 7 下游内含子**的特异序列（不是外显子本身）——想想为什么
- 安全性：血小板减少 + 肾毒性（尿蛋白 58% vs 对照 34%）
