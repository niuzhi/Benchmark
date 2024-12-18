src/
├── application/                      # 应用层
│   ├── services/
│   │   ├── template_service.rs       # 模板渲染服务
│   │   ├── git_service.rs            # Git相关服务
│   │   └── token_service.rs          # Token计算服务
│   └── dto/
│       └── cli_args.rs               # CLI参数DTO
├── domain/                           # 领域层
│   ├── models/
│   │   ├── template.rs               # 模板领域模型
│   │   ├── git.rs                    # git领域模型
│   ├── repositories/
│   │   ├── template_repository.rs    # 模板仓储接口
│   │   └── git_repository.rs         # git仓储接口
│   └── services/                     # 服务
├── infrastructure/                   # 基础设施层
│   ├── git/
│   │   └── git_config.rs             # Git操作实现
│   ├── template/
│   │   └── handlebars_engine.rs      # Handlebars模板引擎实现
│   └── clipboard/
│       └── clipboard_manager.rs      # 剪贴板管理实现
├── interfaces/                       # 接口层
│   └── cli/                          # 命令行接口
│       ├── commands/                 # CLI命令
│       │   └── generate.rs           # 生成提示命令
└── templates/                        # 模版
└── main.rs                           # 程序入口
