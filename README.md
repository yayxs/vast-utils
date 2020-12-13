## 克隆

```sh
# 克隆项目（vast-utils）
git clone https://github.com/yayxs/vast-utils
```


## Use in vue project

1. 安装`vast-utils`
```sh
yarn add vast-utils
```
2. 在项目中导入

```js
import { firstTestUtil } from 'vast-utils'
```
3. 使用

```js
 data() {
      return {
        utilsResult: false,
      }
    },
    mounted() {
      this.utilsResult = firstTestUtil()
    },
```

## Git 提交规范


  - `feat` 增加新功能
  - `fix` 修复问题/BUG
  - `style` 代码风格相关无影响运行结果的
  - `perf` 优化/性能提升
  - `refactor` 重构
  - `revert` 撤销修改
  - `test` 测试相关
  - `docs` 文档/注释
  - `chore` 依赖更新/脚手架配置修改等
  - `workflow` 工作流改进
  - `ci` 持续集成
  - `types` 类型定义文件更改
  - `wip` 开发中
