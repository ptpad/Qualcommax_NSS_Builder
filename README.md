# Qualcommax NSS Builder
上游：https://github.com/JuliusBairaktaris 
原因：
闪存总容量（UBI 管理部分）：约 232.5 MiB（符合 256MB 闪存扣除坏块管理的空间）。
逻辑卷划分（MTD / UBI Layout）：kernel 卷：5.3 MiBrootfs 卷（存储底层只读系统）：10.1 MiB
其实是stock 官方原厂分区表布局的u-boot
现在修复它
