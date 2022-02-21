---
title: "探测免密登录"
date: 2022-01-06T16:38:32+08:00
weight: 50
description: >
    探测虚拟机能否被 var_oem_name 平台免密登录
---

该功能用于探测虚拟机是否能被平台免密登录。

**探测免密登录**

1. 在左侧导航栏，选择 **_"主机/主机/虚拟机"_** 菜单项，进入虚拟机页面。
2. 单击虚拟机右侧操作列 **_"更多"_** 按钮，选择 **_"密码密钥-探测免密登录"_** 菜单项，弹出探测免密登录对话框。
2. 开始探测免密登录，并支持在操作列表查看不可免密登录的原因。
    - 如报错原因中提示“none publickey”，可通过设置免密登录功能，将虚拟机设置为免密登录状态。
    - 如报错原因中提示“network error”，则需要先将该虚拟机通过绑定EIP或NAT网关以及SSH代理等方式，使其与平台网络可通。

**批量探测免密登录**

1. 在虚拟机列表中选择一个或多个虚拟机，单击列表上方 **_"批量操作"_** 按钮，选择下拉菜单 **_"密码密钥-探测免密登录"_** 菜单项，弹出探测免密登录对话框。
2. 开始探测免密登录，并支持在操作列表查看不可免密登录的原因。
    - 如报错原因中提示“none publickey”，可通过设置免密登录功能，将虚拟机设置为免密登录状态。
    - 如报错原因中提示“network error”，则需要先将该虚拟机通过绑定EIP或NAT网关以及SSH代理等方式，使其与平台网络可通。