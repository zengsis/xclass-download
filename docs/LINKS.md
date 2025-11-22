# 应用下载中心 - 访问链接列表

## 📋 主应用选择页面

**访问链接：**
```
https://zengsis.github.io/xclass-download/
```

**说明：** 可以选择应用（XClass 或 授课助手）

---

## 🔗 XClass 应用链接

### 主选择页面
```
https://zengsis.github.io/xclass-download/xclass/
```

### 各版本直接访问链接

#### 1. 内测版
```
https://zengsis.github.io/xclass-download/xclass/beta/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 2. 海外正式域名公测版
```
https://zengsis.github.io/xclass-download/xclass/overseas-official/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 3. 海外测试域名公测版
```
https://zengsis.github.io/xclass-download/xclass/overseas-test/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 4. 国内正式域名公测版
```
https://zengsis.github.io/xclass-download/xclass/domestic-official/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 5. 国内测试域名公测版
```
https://zengsis.github.io/xclass-download/xclass/domestic-test/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

---

## 🔗 授课助手 应用链接

### 主选择页面
```
https://zengsis.github.io/xclass-download/teacher-assistant/
```

### 各版本直接访问链接

#### 1. 内测版
```
https://zengsis.github.io/xclass-download/teacher-assistant/beta/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 2. 海外正式域名公测版
```
https://zengsis.github.io/xclass-download/teacher-assistant/overseas-official/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 3. 海外测试域名公测版
```
https://zengsis.github.io/xclass-download/teacher-assistant/overseas-test/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 4. 国内正式域名公测版
```
https://zengsis.github.io/xclass-download/teacher-assistant/domestic-official/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

#### 5. 国内测试域名公测版
```
https://zengsis.github.io/xclass-download/teacher-assistant/domestic-test/
```
**iOS下载链接：** `待填写`  
**Android下载链接：** `待填写`

---

## 📝 使用说明

1. **主应用选择页面：** 用户访问主链接，选择应用（XClass 或 授课助手）
2. **应用版本选择：** 选择应用后，选择需要的版本类型
3. **直接访问版本：** 每个版本都有独立链接，访问后根据iOS/Android自动跳转
4. **自动跳转：** 移动设备访问版本链接时会自动跳转到对应的下载页面

---

## ⚙️ 配置下载链接

请在以下文件中替换 `TODO` 注释中的下载链接：

### XClass 应用
- `docs/xclass/beta/index.html`
- `docs/xclass/overseas-official/index.html`
- `docs/xclass/overseas-test/index.html`
- `docs/xclass/domestic-official/index.html`
- `docs/xclass/domestic-test/index.html`

### 授课助手 应用
- `docs/teacher-assistant/beta/index.html`
- `docs/teacher-assistant/overseas-official/index.html`
- `docs/teacher-assistant/overseas-test/index.html`
- `docs/teacher-assistant/domestic-official/index.html`
- `docs/teacher-assistant/domestic-test/index.html`

每个文件中有3处需要替换：
- iOS设备跳转链接（2处）
- Android设备跳转链接（1处）
- 手动下载按钮链接（2处，iOS和Android各1处）

---

## 📁 文件结构

```
docs/
├── index.html                    # 主应用选择页面
├── logo.png                      # Logo图片
├── xclass/                       # XClass应用
│   ├── index.html               # XClass版本选择页面
│   ├── logo.png
│   ├── beta/
│   ├── overseas-official/
│   ├── overseas-test/
│   ├── domestic-official/
│   └── domestic-test/
└── teacher-assistant/            # 授课助手应用
    ├── index.html               # 授课助手版本选择页面
    ├── logo.png
    ├── beta/
    ├── overseas-official/
    ├── overseas-test/
    ├── domestic-official/
    └── domestic-test/
```
