# NOW — 断点卡片

> 规则：开始前写「今天要做」，结束时改成「下次从…继续」。第二天不用回忆，直接开工。

## ✅ D1 已完成（2026-10-16）

- [x] 建知识库骨架 + 首次提交
- [x] 仓库推送到 GitHub（远端 `oligo-kb-202610`，origin 已切换）
- [x] Nusinersen（Spinraza）说明书抓取整理 → `99_原料/Nusinersen_Spinraza_label_要点.md`
- [x] Khvorova & Watts 2017 综述 PDF 下载 → `99_原料/nihms874289.pdf`
- [x] 读摘要 + Figure 1（**Figure 1 = dianophore / pharmacophore 解耦图**，全篇题眼）
- [x] 术语表 +6 条（RNase H1 / 药效团 / 分布团 / 信息药物 / PS / 2′-MOE / gapmer）

**D1 核心收获（一句话版）**：寡核苷酸是"信息药物"——**药效团由序列定（打谁）**，**分布团由化学修饰定（去哪）**，两者可独立优化。这是它能快速平台化成药的根本原因。

---

## 🔵 D2 进行中（ASO 机制 · 2h，提前启动）

> 两个机制的讲解图已给过，笔记骨架已建好：**`02_技术方案/ASO机制笔记_v0.md`**

- [x] 骨架笔记 + 案例拆解 + 对比表第 1 行 + 自检答案（已入库）
- [ ] **主读** Khvorova & Watts 2017 的 ASO 章节，核验笔记里标【待核验】的两条
- [ ] 对照 Nusinersen label 自己算一遍 3 个数字（18-mer / 半衰期 / 7.5 kDa）
- [ ] 回答"为什么靶点是内含子而不是 exon 7"（自检第 4 题）
- [ ] 术语表补 2 条（建议：ISS-N1 / 立体位阻 steric block）
- [ ] commit + Sync

### D2 拆解时这几个数字值得自己先算一遍（label 里有）

- 分子式 `C234H323N61O128P17S17Na17`、MW 7501 Da → **P/S 各 17 个 → 18 个核苷酸**（nusinersen 是 18-mer）
- CSF 半衰期 **135–177 天**、血浆 63–87 天 → 说明为什么维持期是 **每 4 个月** 一次
- 化学：2′-O-2-methoxyethyl（2′-MOE）+ 全长硫代磷酸（PS）
- 靶点：SMN2 **exon 7 下游内含子**的特异序列（不是外显子本身）——想想为什么
- 安全性：血小板减少 + 肾毒性（尿蛋白 58% vs 对照 34%）

---

## 未完成的 D1 收尾（有空补）

- [ ] 把 `99_原料/nihms874289.pdf` 改名为 `Khvorova_2017_chemical-evolution.pdf`（统一命名）
- [ ] commit 术语表 + 本卡片更新，VSCode 点 Sync
