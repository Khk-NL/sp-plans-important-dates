# Plans & Important Dates for Super Productivity

> 🗓️ A long-term planning and important date management plugin for [Super Productivity](https://github.com/johannesjo/super-productivity).

Manage long-term goals, milestones, deadlines, and important dates in one dedicated planning view.

[English](#english) | [中文](#中文)

---

## English

### ✨ Features

#### Long-term plans
- Create and manage long-term goals
- Track:
  - Goal area
  - Status
  - Progress
  - Stages
  - Target date
  - Linked Super Productivity projects

#### Important dates
- Create and manage important dates such as:
  - Exams
  - Registration dates
  - Deadlines
  - Milestones
  - Personal events
- Organize dates into:
  - Today
  - Upcoming
  - Past
  - Archived

#### Linking
- Link important dates to:
  - Super Productivity projects
  - Long-term goals
  - Courses
- Keep plans, dates, and related work connected in one place

#### Planning actions
- Create
- Edit
- Complete
- Archive
- Restore
- Delete

#### Integration
- English and Chinese translations
- Automatically follows the Super Productivity language
- Uses synced plugin storage for planning data and display settings
- Opens in a dedicated full-page planning view

---

### 📦 Installation

1. Go to **GitHub Releases**.
2. Download:

   `sp-plans-important-dates.zip`

3. Open Super Productivity.
4. Go to:

   `Settings → Plugins`

5. Import the ZIP file.
6. Restart Super Productivity if requested.
7. Open **Plans & Important Dates** from the plugin entry.

### Compatibility

Requires:

```text
Super Productivity >= 18.21.2
```

---

### 🔐 Data & Permissions

The plugin:

- Reads Super Productivity project names for optional linking
- Stores only its own planning data and display settings
- Opens a dedicated full-page planning interface
- Shows confirmation and status messages

The plugin does **not**:

- Modify Super Productivity tasks
- Delete Super Productivity tasks
- Modify projects
- Delete projects

---

### 🛠 Development & Packaging

This is a dependency-free iframe plugin.

The release ZIP should contain the following files at its root:

```text
manifest.json
index.html
icon.svg
i18n/
```

Example packaging command:

```powershell
Compress-Archive `
  -Path manifest.json,index.html,icon.svg,i18n `
  -DestinationPath sp-plans-important-dates.zip
```

---

## 中文

### ✨ 功能

#### 长期规划
- 创建和管理长期目标
- 可记录：
  - 目标领域
  - 状态
  - 进度
  - 阶段
  - 目标日期
  - 关联的 Super Productivity 项目

#### 重要日期
可记录考试、报名、截止日期、里程碑等重要节点。

支持按以下状态分类查看：

- 今天
- 即将到来
- 已过去
- 已归档

#### 关联
重要日期可以关联到：

- Super Productivity 项目
- 长期规划
- 课程

方便将计划、日期与具体任务或课程组织在一起。

#### 规划操作
支持：

- 新建
- 编辑
- 完成
- 归档
- 恢复
- 删除

#### 集成
- 支持中文和英文
- 自动跟随 Super Productivity 的语言设置
- 使用 SP 插件同步存储保存规划数据和显示设置
- 使用独立全页面规划界面

---

### 📦 安装

1. 前往 GitHub **Releases**
2. 下载：

   `sp-plans-important-dates.zip`

3. 打开 Super Productivity
4. 进入：

   `设置 → 插件`

5. 导入 ZIP 插件
6. 如有提示，重启 Super Productivity
7. 从插件入口打开 **Plans & Important Dates**

### 兼容性

需要：

```text
Super Productivity >= 18.21.2
```

---

### 🔐 数据与权限

插件会：

- 读取 Super Productivity 项目名称，用于可选关联
- 保存插件自身的规划数据和显示设置
- 打开独立的全页面规划界面
- 显示确认与状态提示

插件不会：

- 修改 Super Productivity 任务
- 删除任务
- 修改项目
- 删除项目

---

### 🛠 开发与打包

该插件为无外部依赖的 iframe 插件。

发布 ZIP 根目录应包含：

```text
manifest.json
index.html
icon.svg
i18n/
```

打包示例：

```powershell
Compress-Archive `
  -Path manifest.json,index.html,icon.svg,i18n `
  -DestinationPath sp-plans-important-dates.zip
```

---

## 📄 License

[MIT](LICENSE)
