---
title: Mac 
weight: 3
---

### 安裝
------

打開 .dmg 文件並將 `RustDesk` 拖到 `應用程序`，如下所示。

![](/docs/en/manual/mac/images/dmg.png)

確保您已退出所有正在運行的 RustDesk。還要確保退出托盤上顯示的 RustDesk 服務。

![](/docs/en/manual/mac/images/tray.png)

### 允許 RustDesk 運行

| 解鎖改變 | 點擊"App Store and identified developers"  |
| ---- | ---- |
|![](/docs/en/manual/mac/images/allow2.png)|![](/docs/en/manual/mac/images/allow.png)|

### 啟用權限

{{% notice note %}}
Due to MacOS security policy change, our api which captures input on local side does not work any
more. You have to enable "Input Monitoring" permission on local Mac side.
Please follow this
[https://github.com/rustdesk/rustdesk/issues/974#issuecomment-1185644923](https://github.com/rustdesk/rustdesk/issues/974#issuecomment-1185644923)

It seems no quick fix, we need to fix together with our Flutter version.
{{% /notice %}}

為了獲得捕獲屏幕的能力，您需要授予 `RustDesk` **輔助功能** 權限和 **屏幕錄製** 權限。 RustDesk 將引導您進入設置窗口。

| RustDesk 窗口 |設置窗口 |
| ---- | ---- |
|![](/docs/en/manual/mac/images/acc.png)|![](/docs/en/manual/mac/images/acc3.png)|

如果您在設置窗口中啟用了它，但 RustDesk 仍然會發出警告。請通過 `-` 按鈕從設置窗口中刪除 RustDesk，然後單擊 `+` 按鈕，在 `/Applications` 中選擇 RustDesk。

| `-` 和 `+` 按鈕 |選擇 RustDesk |
| ---- | ---- |
|![](/docs/en/manual/mac/images/acc2.png)|![](/docs/en/manual/mac/images/add.png)|

請按照上面相似步驟設置*屏幕錄製**權限。

![](/docs/en/manual/mac/images/screen.png)
