# PhyTA
Phylogenetic tree analysis on Windows

采用极简主义中的"One Step", 基于16S rDNA序列采用最大似然算法在 windows 系统平台中进行系统发育分析

## **>> Just One Step <<**

- 初衷 -- **不想重复性地 coding! 不想重复性地 coding! 不想重复性地 coding!**

- **解放双手 ==>> To Think!!!**

1 序列对齐处理有两种选择: [mafft](https://mafft.cbrc.jp/alignment/software/) & [muscle](https://www.mybiosoftware.com/muscle-3-8-31-multiple-sequence-alignment.html)

2 修剪对齐序列: [trimAl](http://trimal.cgenomics.org/trimal)

3 最大似然法系统发育分析有两种选择: [IQTree](http://www.iqtree.org/) & [RAxML](https://github.com/stamatak/standard-RAxML/blob/master/WindowsExecutables_v8.2.10/)

4 系统发育树形的进一步美化, 可至 [iTOL](https://itol.embl.de/)

---

- 为了便于流程的顺畅处理, 待分析的 fasta 格式序列文件统一使用 Input.fasta 进行命名, 因此需要将序列复制到 Input.fasta 文件中; 

- 序列对齐的 fasta 结果文件统一使用 Align.fasta 进行命名;

! 需要有 R语言 编译环境(提前安装R包: install.packages("parallel"))
