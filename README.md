# bigfatfishsuperagent

Repository for the dsh-superagent deployment.

Ask the agent for work by commenting `@superbigfatfish <request>` on an issue here.

## 本地开发

本仓库用于 dsh-superagent 的部署；源码和可构建的工程在
[dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype)。

### 环境要求

- Node.js 22.19+ 或 24+
- pnpm 11.7（版本固定在源码仓库 `package.json` 的 `packageManager`）
- git 2.32+

### 安装依赖

```sh
git clone https://github.com/deepseek-ai/dsh-superagent-prototype.git
cd dsh-superagent-prototype
pnpm install
```

### 运行构建

```sh
pnpm build
```

构建产物输出到 `lib/`。提交前运行完整检查（类型检查、测试和构建）：

```sh
pnpm check
```

部署与配置步骤见源码仓库的
[SETUP.md](https://github.com/deepseek-ai/dsh-superagent-prototype/blob/main/SETUP.md) 和
[docs/006-deployment.md](https://github.com/deepseek-ai/dsh-superagent-prototype/blob/main/docs/006-deployment.md)。
