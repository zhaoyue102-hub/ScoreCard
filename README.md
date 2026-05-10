# ScoreCard · 每日积分打卡

静态单页应用（`index.html`）：孩子积分规则、每日打卡、历史与周汇总；可选 [Firebase](https://firebase.google.com/) 云同步，多设备共用同一「家庭码」。

## 在线访问（GitHub Pages）

1. 本仓库 **Settings → Pages**
2. **Build and deployment**：Source 选 **Deploy from a branch**，Branch 选 **`main`**，文件夹 **`/ (root)`**，保存
3. 几分钟后可访问：**https://zhaoyue102-hub.github.io/ScoreCard/**

首次使用需在 `index.html` 中填写自己的 `FIREBASE_CONFIG`，并在 Firebase 控制台把授权网域加上 `zhaoyue102-hub.github.io`（详见页面内「云同步」说明）。

## 本地预览

```bash
python3 -m http.server 8080
```

浏览器打开 http://localhost:8080/ （勿用 `file://`，否则云同步可能不可用）。

## 仓库

https://github.com/zhaoyue102-hub/ScoreCard
