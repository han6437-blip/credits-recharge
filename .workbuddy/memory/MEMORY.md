# Credits 充值申请系统

## 项目信息
- 技术栈: 纯静态 HTML/CSS/JS + Supabase 后端
- Supabase 项目: `iajpcsbebjjtaaspmwws`
- 管理员账号: `admin@enter.pro`（Supabase Auth）
- 数据库表: `public.applications`

## 文件结构
```
├── index.html          # 学员充值申请表单
├── result.html         # 申请结果查询页
├── config.js           # Supabase 连接配置
└── admin/
    ├── login.html      # 管理员登录
    └── dashboard.html  # 工单管理后台
```

## 关键约定
- 工单列表按 created_at 降序排列
- 分页：每页 20 条
- 工单状态：pending / approved / rejected
- 驳回必须填写理由
