# vue-cli（webpack）

## 版本概览

<table><thead><tr><th width="177">Vue Cli  Version</th><th width="171">NodeJS Version</th><th width="163">Vue Version</th><th>安装命令</th><th width="184">常用命令</th><th width="100">发布日期</th></tr></thead><tbody><tr><td>5.x</td><td></td><td>vue2/3</td><td>npm i @vue/cli -g</td><td>vue create</td><td>2022-07</td></tr><tr><td>4.x</td><td>v8.9 或更高版本 (推荐 v10 以上)</td><td><p>>=4.5  vue2/3</p><p>&#x3C;4.5  vue2</p></td><td>npm i @vue/cli -g</td><td>vue create</td><td>2019-10</td></tr><tr><td>3.x</td><td>v8.9 或更高版本 </td><td>vue2</td><td>npm i @vue/cli -g</td><td>vue create</td><td>2018-08</td></tr><tr><td>2.x</td><td>v4.x  (推荐v6以上)</td><td>vue2</td><td>npm i vue-cli -g</td><td>-V， --version<br>-h, --help<br>init/list/build/createhelp [cmd] </td><td></td></tr><tr><td>1.x</td><td>v4.x  (推荐v6以上)</td><td>vue2</td><td>npm i vue-cli -g</td><td></td><td></td></tr></tbody></table>



## 更新内容

#### Vue CLI 2.x

* **基本特性**：
  * 使用模板（templates）：通过 `vue init <template> <project-name>` 命令从预定义的模板创建项目。
  * 配置文件：项目配置和脚本大多基于 `.vue` 文件和 `webpack` 配置文件。
  * 简单且快速：适用于简单的 Vue.js 项目。

#### Vue CLI 3.x

* **重大变化**：
  * **插件化系统**：引入了插件系统，使用 `vue create <project-name>` 命令，插件可以动态添加和删除功能。
  * **零配置**：开箱即用的零配置，内置了现代化的开发工具（如 Babel、ESLint、TypeScript 等）。
  * **可扩展性**：通过 `vue.config.js` 进行配置扩展，允许用户对 webpack 配置进行复杂的自定义。
  * **GUI**：提供了图形用户界面（GUI），可以通过 `vue ui` 命令启动，方便进行项目管理。
  * **现代化构建**：内置现代化构建配置，支持多页应用、服务端渲染（SSR）等高级特性。

#### Vue CLI 4.x

* **进一步改进**：
  * **更快的构建速度**：通过优化配置和缓存机制，提升了构建速度和开发体验。
  * **改进的插件系统**：插件系统更稳定，支持更多的插件和功能。
  * **持续集成支持**：改进了对持续集成和持续部署（CI/CD）的支持。
  * **Vue 3 支持**：为 Vue 3 提供了更好的支持，尽管 Vue CLI 4.x 依然兼容 Vue 2.x。
  * **新功能和改进**：包括新的命令和选项，如 `vue add` 用于添加插件，`vue upgrade` 用于升级项目依赖等。

#### Vue CLI 5.x

* **最新改进**：
  * **Vue 3 的全面支持**：完全支持 Vue 3，同时保持对 Vue 2 的兼容性。
  * **现代化构建工具链**：集成了最新的构建工具，如 Vite，以提升开发和构建速度。
  * **改进的开发体验**：提供了更多的优化和改进，以提升开发者体验。
  * **更好的性能**：通过新的优化和改进，提高了应用的构建和运行性能。
  * **升级的依赖**：依赖库和工具链的升级，以利用最新的功能和性能改进。

#### 总结

* **Vue CLI 2.x**：简单且快速，适用于小型项目，依赖模板和手动配置。
* **Vue CLI 3.x**：引入插件系统和零配置理念，支持现代化开发需求，扩展性强。
* **Vue CLI 4.x**：优化性能和构建速度，改进插件系统和持续集成支持，为 Vue 3 提供良好支持。
* **Vue CLI 5.x**：全面支持 Vue 3，集成最新构建工具，提升性能和开发体验。
