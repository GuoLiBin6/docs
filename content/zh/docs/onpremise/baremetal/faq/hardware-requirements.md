---
title: "物理机硬件规格要求"
weight: 4
---

## 架构

x86 的服务器

## BIOS 主板

- 支持 Legacy(传统模式) 的 PXE 引导网络启动
- 支持 BMC IPMI 带外控制
- 如果设置了 PXE、硬盘启动的引导顺序，当 PXE 启动不成功的时候，会尝试磁盘启动

## 硬盘

硬盘支持 HDD(机械硬盘)、SSD(固态硬盘) 和 NVME SSD。

硬盘做 RAID 的话，支持以下的 RAID 控制器：

- MegaRaid
- HPSARaid
- Mpt2/3SAS
- AdaptecRaid
- MarvelRaid

NVME SSD 需要是内核中 **nvme** 或者 **nvme_core** 驱动的

## 网卡

网卡需要是以下内核驱动能支持的：

- ixgbe
- igb
- e1000, e100e
- tg3
- bnx2
- i40e
- bnx2x
- bnxt_en