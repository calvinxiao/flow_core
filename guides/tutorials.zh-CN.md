使用指南
====

## 要求

- Rails 6.0+
- Ruby 2.5+
- ActiveRecord 支持的关系型数据库

## 安装

### 添加依赖到 `Gemfile`

在项目的 `Gemfile` 里添加：

```ruby
gem "flow_core"
```

或者使用最新的开发版本：

```ruby
gem 'flow_core', github: 'rails-engine/flow_core'
```

然后执行 `bundle` 更新项目依赖

### 复制数据库迁移文件

执行

```
$ bin/rails role_core:install:migrations
```

拷贝 FlowCore 需要的数据库表的迁移文件

然后执行迁移

```
$ bin/rails db:migrate
```

## 为业务模型添加 TaskExecutable

WIP

## 编写任务的触发器

WIP

## 编写分支比较器

WIP
