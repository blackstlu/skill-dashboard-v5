# Skill Dashboard v5 專案指南

## 專案概述
這是一個技能儀表板專案，用於管理和展示多個 GitHub 工作流程技能。

## 目錄結構
```
skill-dashboard-v5/
├── data.js              # 技能數據配置
├── index.html           # 主頁面
├── claude.md            # 專案指南（本檔案）
├── .git/                # Git 版本控制
└── skills/              # 技能模組目錄
    ├── create-branch-v2/       # 建立分支技能
    ├── create-commit-v2/       # 建立提交技能
    ├── create-pages/           # 建立頁面技能
    ├── create-repo/            # 建立倉庫技能
    ├── merge-pr/               # 合併 PR 技能
    ├── open-pr/                # 開啟 PR 技能
    ├── setup-dashboard/        # 設置儀表板技能
    └── write-workflow/         # 編寫工作流程技能
```

## 技能模組
每個技能模組都包含 `SKILL.md` 檔案，描述該技能的功能和使用方法。

### 已集成的技能
1. **create-branch-v2** - 建立 Git 分支
2. **create-commit-v2** - 建立 Git 提交
3. **create-pages** - 建立頁面
4. **create-repo** - 建立倉庫
5. **merge-pr** - 合併 Pull Request
6. **open-pr** - 開啟 Pull Request
7. **setup-dashboard** - 設置儀表板
8. **write-workflow** - 編寫 GitHub 工作流程

## 開發指南

### 環境要求
- Node.js (推薦版本 16 以上)
- Git
- 現代網頁瀏覽器

### 本地開發
```bash
# 啟動本地伺服器
npx http-server

# 或使用 Python
python3 -m http.server 8000
```

### Git 工作流程
```bash
# 檢查狀態
git status

# 新增檔案
git add <檔案>

# 提交變更
git commit -m "描述性訊息"

# 推送到遠端
git push origin <分支名稱>
```

## 編碼約定
- 使用 UTF-8 編碼
- JavaScript 遵循 ES6+ 標準
- HTML 使用語義化標記
- CSS 使用有意義的類名和組織

## 常見任務

### 新增技能
1. 在 `skills/` 目錄中建立新資料夾
2. 在其中建立 `SKILL.md` 檔案
3. 更新 `data.js` 中的技能清單
4. 提交變更

### 更新技能
1. 編輯對應技能中的 `SKILL.md`
2. 測試功能是否正常
3. 提交變更

### 部署
按照部署文件中的指示進行部署（如適用）。

## 相關文件
- `data.js` - 技能數據配置
- `index.html` - UI 主頁面

## 支援
如有問題，請檢查相應技能的 `SKILL.md` 檔案或提交 Issue。

## 版本歷史
- **v5** - 當前版本，包含 8 個技能模組
