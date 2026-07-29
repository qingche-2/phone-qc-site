# 手机回收质检判责逻辑库

在线问答站点：手机/平板/笔记本/耳机/手表/相机/镜头/游戏机/手写笔 判责标准查询

## 访问地址

https://<你的用户名>.github.io/phone-qc-site/

## 本地运行

```bash
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 部署

```bash
git add .
git commit -m "初始化判责逻辑库站点"
git remote add origin https://github.com/<你的用户名>/phone-qc-site.git
git push -u origin main
# 然后在 GitHub 仓库 Settings → Pages 中启用 GitHub Pages（Source: main 分支）
```
