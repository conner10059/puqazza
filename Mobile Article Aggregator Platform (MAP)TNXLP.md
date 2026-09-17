<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

gitlab.com/EHWGW/fxleljy/-/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%A8%E8%A7%A3%E8%AF%BB:%E7%99%BB1%E7%99%BB2%E7%99%BB3%E7%9A%87%E5%86%A0-%E7%A7%89%E7%9C%9F%E8%B4%A2%E7%BB%8F.md
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7fbc30297dc002f772410448720b63682cc0c179
<br>
gitlab.com/EHWGW/fxleljy/-/blob/main/2026%E5%AE%98%E6%96%B9%E5%85%A8%E8%A7%A3%E8%AF%BB:%E7%99%BB1%E7%99%BB2%E7%99%BB3%E7%9A%87%E5%86%A0-%E7%A7%89%E7%9C%9F%E8%B4%A2%E7%BB%8F.md?/837=236
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7fbc30297dc002f772410448720b63682cc0c179?/Ga=Hfw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7fbc30297dc002f772410448720b63682cc0c179?/HlF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4c6f2de72de75dea09db3f85f9bd69fba8cd866e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4c6f2de72de75dea09db3f85f9bd69fba8cd866e?/ub=2P9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4c6f2de72de75dea09db3f85f9bd69fba8cd866e?/Y2W
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f84cb2b3e52a1bf64ccf1017fb5172a34c97a9c6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f84cb2b3e52a1bf64ccf1017fb5172a34c97a9c6?/K4=bfn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f84cb2b3e52a1bf64ccf1017fb5172a34c97a9c6?/vPt
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9be7c66a49b76fb52cd9e7bfe7253377fd348aef
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9be7c66a49b76fb52cd9e7bfe7253377fd348aef?/mj=A4O
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9be7c66a49b76fb52cd9e7bfe7253377fd348aef?/gAe
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0217e2eb211dd3014d175cefb50be756a0cbe555
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0217e2eb211dd3014d175cefb50be756a0cbe555?/XU=PJd
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0217e2eb211dd3014d175cefb50be756a0cbe555?/vPt
<br>
gitlab.com/EHWGW/fxleljy/-/commit/19d07f598f805a161523ebbfa4deeccba6b22008
<br>
gitlab.com/EHWGW/fxleljy/-/commit/19d07f598f805a161523ebbfa4deeccba6b22008?/qN=xeY
<br>
gitlab.com/EHWGW/fxleljy/-/commit/19d07f598f805a161523ebbfa4deeccba6b22008?/gAe
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff1f079fc389411890fe8c09d1b34272cb3e84a2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff1f079fc389411890fe8c09d1b34272cb3e84a2?/mQ=kui
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff1f079fc389411890fe8c09d1b34272cb3e84a2?/xRv
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8050d15e21a90dc74ee89c8ec9ecad42cd9aaad5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8050d15e21a90dc74ee89c8ec9ecad42cd9aaad5?/Qq=k4i
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8050d15e21a90dc74ee89c8ec9ecad42cd9aaad5?/qKo
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f0bae11acce5381230590b81155180994a2d80b8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f0bae11acce5381230590b81155180994a2d80b8?/oO=YPd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f0bae11acce5381230590b81155180994a2d80b8?/b53
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3aecdb2c4e2690128c7e6b9e7d745bb006e60878
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3aecdb2c4e2690128c7e6b9e7d745bb006e60878?/ZA=Noi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3aecdb2c4e2690128c7e6b9e7d745bb006e60878?/qKo
<br>
gitlab.com/EHWGW/fxleljy/-/commit/14913354d62d62602969f835990c3e20627e6bed
<br>
gitlab.com/EHWGW/fxleljy/-/commit/14913354d62d62602969f835990c3e20627e6bed?/d1=Is2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/14913354d62d62602969f835990c3e20627e6bed?/bZ3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9970e70ca468af145ee499ec28f6fe442b897a98
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9970e70ca468af145ee499ec28f6fe442b897a98?/0U=SPJ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9970e70ca468af145ee499ec28f6fe442b897a98?/OsM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3b5710f786b638db4e4928ff2b5b60af84e1dc23
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3b5710f786b638db4e4928ff2b5b60af84e1dc23?/KE=YF9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3b5710f786b638db4e4928ff2b5b60af84e1dc23?/HlF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5748e4be2246885b28a186c22fcf47c4e52dca98
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5748e4be2246885b28a186c22fcf47c4e52dca98?/jJ=TKY
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5748e4be2246885b28a186c22fcf47c4e52dca98?/W0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/da6c73c2073d66d554a10bdc7f881e0d857a5155
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/da6c73c2073d66d554a10bdc7f881e0d857a5155?/Ry=YFc
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/da6c73c2073d66d554a10bdc7f881e0d857a5155?/HlF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0d268c7c15ac5832000b7b08539157f9eb623968
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0d268c7c15ac5832000b7b08539157f9eb623968?/53=xHR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0d268c7c15ac5832000b7b08539157f9eb623968?/W0U
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9ad4963df5b94e313a35372ad30953ab00cd177a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9ad4963df5b94e313a35372ad30953ab00cd177a?/Cw=wxU
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9ad4963df5b94e313a35372ad30953ab00cd177a?/JnH
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ddc2721c0163f4780d275c446947db5c3b13998b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ddc2721c0163f4780d275c446947db5c3b13998b?/Td=yC9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ddc2721c0163f4780d275c446947db5c3b13998b?/e8c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4860e0712486e70a6519f079377765e2ce277253
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4860e0712486e70a6519f079377765e2ce277253?/1y=PJd
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4860e0712486e70a6519f079377765e2ce277253?/vPt
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2626fea7e67c589339e8e0b45413c7679b15d820
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2626fea7e67c589339e8e0b45413c7679b15d820?/Zn=KO2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2626fea7e67c589339e8e0b45413c7679b15d820?/Ae8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c33ea4bf0715be326e479be3d17b0a4873efde72
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c33ea4bf0715be326e479be3d17b0a4873efde72?/XV=SMg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c33ea4bf0715be326e479be3d17b0a4873efde72?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e9a1b53363205a343683085f55aed9e77a420720
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e9a1b53363205a343683085f55aed9e77a420720?/nE=bMt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e9a1b53363205a343683085f55aed9e77a420720?/iCg
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9e92b1598f71d5d3ecf509c88295938bfa440711
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9e92b1598f71d5d3ecf509c88295938bfa440711?/2t=7bY
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9e92b1598f71d5d3ecf509c88295938bfa440711?/3X1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c84e8612905c880e839e0a0f1c3d9708a6786eb4
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c84e8612905c880e839e0a0f1c3d9708a6786eb4?/3e=rIC
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c84e8612905c880e839e0a0f1c3d9708a6786eb4?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9be04872183cb1d572c097c1cc13fcdad79f6e62
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9be04872183cb1d572c097c1cc13fcdad79f6e62?/It=6Xu
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9be04872183cb1d572c097c1cc13fcdad79f6e62?/Z3X
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4e3a2672329ca1bba2a76823575e9d523c4bd2bc
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4e3a2672329ca1bba2a76823575e9d523c4bd2bc?/tK=hyV
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4e3a2672329ca1bba2a76823575e9d523c4bd2bc?/KoI
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d415eb3de58bdd5fd86cbebda5a639842861f476
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d415eb3de58bdd5fd86cbebda5a639842861f476?/Mw=6xh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d415eb3de58bdd5fd86cbebda5a639842861f476?/d7b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/24a1ebec3b61032e652afc27996abf867750fcee
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/24a1ebec3b61032e652afc27996abf867750fcee?/Sp=6Ao
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/24a1ebec3b61032e652afc27996abf867750fcee?/wQu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/976ff9f4113afea159b661b3b91bd2fa418a9734
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/976ff9f4113afea159b661b3b91bd2fa418a9734?/pm=D7R
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/976ff9f4113afea159b661b3b91bd2fa418a9734?/jDh
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/53b5fcef7b616bee5ce1a0bed203284a65ef99e8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/53b5fcef7b616bee5ce1a0bed203284a65ef99e8?/64=1vF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/53b5fcef7b616bee5ce1a0bed203284a65ef99e8?/UyS
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d5d244d6c55e6ebbc1f3eface7bcaafa18f9cc69
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d5d244d6c55e6ebbc1f3eface7bcaafa18f9cc69?/uv=S2j
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d5d244d6c55e6ebbc1f3eface7bcaafa18f9cc69?/HlF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/00cb03f71723fb6e99bb88040a6490679c88b4d1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/00cb03f71723fb6e99bb88040a6490679c88b4d1?/FG=nO5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/00cb03f71723fb6e99bb88040a6490679c88b4d1?/a4Y
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9c28fa71a29d5e49c7cbd010ae7a16ecbb67ffc5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9c28fa71a29d5e49c7cbd010ae7a16ecbb67ffc5?/Ke=oft
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9c28fa71a29d5e49c7cbd010ae7a16ecbb67ffc5?/rLp
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/407c5b25fa03d065d4240700831a16a9617381a7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/407c5b25fa03d065d4240700831a16a9617381a7?/6N=x7y
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/407c5b25fa03d065d4240700831a16a9617381a7?/Ae8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7e122adc6967c6278d92d12cb61e97413a9eaef6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7e122adc6967c6278d92d12cb61e97413a9eaef6?/3U=vp9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7e122adc6967c6278d92d12cb61e97413a9eaef6?/RvP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2bb33195478554074623541323097b2c5218f9a2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2bb33195478554074623541323097b2c5218f9a2?/8v=WDd
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2bb33195478554074623541323097b2c5218f9a2?/CgA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/84ffac5cfe9a1e00ef99c4b1a3bd87a753d4ad69
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/84ffac5cfe9a1e00ef99c4b1a3bd87a753d4ad69?/da=1vF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/84ffac5cfe9a1e00ef99c4b1a3bd87a753d4ad69?/1Vz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/05d8a98e052a2af2ea257f443e6adf892c1c9bb7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/05d8a98e052a2af2ea257f443e6adf892c1c9bb7?/8M=Jja
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/05d8a98e052a2af2ea257f443e6adf892c1c9bb7?/mGk
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f67e82ceebef26ce6bca473e2a68a6dea135c11c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f67e82ceebef26ce6bca473e2a68a6dea135c11c?/DA=bzG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f67e82ceebef26ce6bca473e2a68a6dea135c11c?/bZ3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7b3c9b947088ecb713df44068978f887e0aae9cb
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7b3c9b947088ecb713df44068978f887e0aae9cb?/bi=wtK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7b3c9b947088ecb713df44068978f887e0aae9cb?/sMq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/850c47f5581525be67c8667de0bc81d12552f52b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/850c47f5581525be67c8667de0bc81d12552f52b?/P2=JNU
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/850c47f5581525be67c8667de0bc81d12552f52b?/9db
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a9be182b008f8a50bdce3029d042b9981208c083
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a9be182b008f8a50bdce3029d042b9981208c083?/OC=Ja7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a9be182b008f8a50bdce3029d042b9981208c083?/wQu
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0442efae4b10a84ce51c2ed2b065c4d8be16cb4a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0442efae4b10a84ce51c2ed2b065c4d8be16cb4a?/vS=2j6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0442efae4b10a84ce51c2ed2b065c4d8be16cb4a?/lFj
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d9eecb4cfe3cb2426adf83162fc3c7284e51e63b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d9eecb4cfe3cb2426adf83162fc3c7284e51e63b?/DH=RlS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d9eecb4cfe3cb2426adf83162fc3c7284e51e63b?/0Uy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/48c09b1dbee6a50604213c75170ec3a8fc3c910d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/48c09b1dbee6a50604213c75170ec3a8fc3c910d?/Ga=lbL
<br>
gitlab.com/EHWGW/fxleljy/-/commit/48c09b1dbee6a50604213c75170ec3a8fc3c910d?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/75717c032045461d7544ea948f0b3ace0f9e9690
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/75717c032045461d7544ea948f0b3ace0f9e9690?/Yv=Cjq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/75717c032045461d7544ea948f0b3ace0f9e9690?/2W0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d518d5d6e31975d4a33ec06527cc987b788684b2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d518d5d6e31975d4a33ec06527cc987b788684b2?/tn=bFW
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d518d5d6e31975d4a33ec06527cc987b788684b2?/rLp
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f3379f4fb06a7bf23c770aae38bc2072e9697660
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f3379f4fb06a7bf23c770aae38bc2072e9697660?/mE=eYs
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f3379f4fb06a7bf23c770aae38bc2072e9697660?/Ae8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e699a46b4af3ee4ebc00ce06ffc42f8379d78d89
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e699a46b4af3ee4ebc00ce06ffc42f8379d78d89?/5c=Ctn
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e699a46b4af3ee4ebc00ce06ffc42f8379d78d89?/vPt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b6903fd3e75359ad9ce0c9ab70755f34b986d967
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b6903fd3e75359ad9ce0c9ab70755f34b986d967?/yZ=Jqu
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b6903fd3e75359ad9ce0c9ab70755f34b986d967?/CgA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/febcafc82e8b422954e288efa66937ea4ab0acd7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/febcafc82e8b422954e288efa66937ea4ab0acd7?/n0=RLf
<br>
gitlab.com/EHWGW/fxleljy/-/commit/febcafc82e8b422954e288efa66937ea4ab0acd7?/xRv
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/694e355f5586912296d629c6755cb8039b4b02a7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/694e355f5586912296d629c6755cb8039b4b02a7?/XB=2Fg
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/694e355f5586912296d629c6755cb8039b4b02a7?/EiC
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/88457a21aa40cc2e1f1839ca0a7c30ac462247c0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/88457a21aa40cc2e1f1839ca0a7c30ac462247c0?/da=1vF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/88457a21aa40cc2e1f1839ca0a7c30ac462247c0?/X1V
<br>
gitlab.com/EHWGW/fxleljy/-/commit/548dd09a3239de1f585785ef4753567cc7aba331
<br>
gitlab.com/EHWGW/fxleljy/-/commit/548dd09a3239de1f585785ef4753567cc7aba331?/7B=IZ6
<br>
gitlab.com/EHWGW/fxleljy/-/commit/548dd09a3239de1f585785ef4753567cc7aba331?/vPt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d41d9ee1954945350d012dbc0cdd5abcf6749673
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d41d9ee1954945350d012dbc0cdd5abcf6749673?/nH=HHp
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d41d9ee1954945350d012dbc0cdd5abcf6749673?/Ae8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7ff255b1a61bf8bdc7720f7c62b3382c4b778c8e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7ff255b1a61bf8bdc7720f7c62b3382c4b778c8e?/0x=rBM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7ff255b1a61bf8bdc7720f7c62b3382c4b778c8e?/RvP
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/241e56da199c7f1603ef04587905b79c6e57c992
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/241e56da199c7f1603ef04587905b79c6e57c992?/DQ=NHc
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/241e56da199c7f1603ef04587905b79c6e57c992?/rpJ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/385d96925749bf5cb5ce4d8b046dde4219b3233a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/385d96925749bf5cb5ce4d8b046dde4219b3233a?/Ny=BcW
<br>
gitlab.com/EHWGW/fxleljy/-/commit/385d96925749bf5cb5ce4d8b046dde4219b3233a?/e8c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/708482ffe9919b21919d834994c9480d15ae800d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/708482ffe9919b21919d834994c9480d15ae800d?/4c=Ctn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/708482ffe9919b21919d834994c9480d15ae800d?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/75cac7bc4d112169f470b0cd25482d5a48e1a802
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/75cac7bc4d112169f470b0cd25482d5a48e1a802?/YI=nno
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/75cac7bc4d112169f470b0cd25482d5a48e1a802?/gAe
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6cab86cd2488cd8a19bfca81c62d5a24b8486309
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6cab86cd2488cd8a19bfca81c62d5a24b8486309?/s9=gnX
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6cab86cd2488cd8a19bfca81c62d5a24b8486309?/TxR
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ac0dc837bfc48dc7008912a84b17e3db71e4c7c9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ac0dc837bfc48dc7008912a84b17e3db71e4c7c9?/SV=dNO
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ac0dc837bfc48dc7008912a84b17e3db71e4c7c9?/GkE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f55db0471ccf944f50e65f4d588a8d3b6bb97abc
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f55db0471ccf944f50e65f4d588a8d3b6bb97abc?/IQ=Ahl
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f55db0471ccf944f50e65f4d588a8d3b6bb97abc?/3X1
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0fb031b6e4b2d77461fafdf8e42217ee3110354f
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0fb031b6e4b2d77461fafdf8e42217ee3110354f?/0b=lcM
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0fb031b6e4b2d77461fafdf8e42217ee3110354f?/ImG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/216d369353ee7883adca79c2f4e69ecbc87a63ee
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/216d369353ee7883adca79c2f4e69ecbc87a63ee?/hB=8ZT
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/216d369353ee7883adca79c2f4e69ecbc87a63ee?/b5Z
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/51d675d8acf7636d413ff7636b79592aec150fb9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/51d675d8acf7636d413ff7636b79592aec150fb9?/mT=uob
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/51d675d8acf7636d413ff7636b79592aec150fb9?/QuO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe92e394ad73adf8850a9e2127d0de1e5f6ed052
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe92e394ad73adf8850a9e2127d0de1e5f6ed052?/Ks=S9W
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe92e394ad73adf8850a9e2127d0de1e5f6ed052?/Bf9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/eb0db63ab740015adc7adce84e5019b4d78a66c0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/eb0db63ab740015adc7adce84e5019b4d78a66c0?/cD=NER
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/eb0db63ab740015adc7adce84e5019b4d78a66c0?/QuO
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a7da38832d6a2928f22e250020beb48443b4add2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a7da38832d6a2928f22e250020beb48443b4add2?/KL=szC
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a7da38832d6a2928f22e250020beb48443b4add2?/Bf9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5152fa0c1c45a1f91b7943ee1baa0890bb6c9d8e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5152fa0c1c45a1f91b7943ee1baa0890bb6c9d8e?/Mx=AbV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5152fa0c1c45a1f91b7943ee1baa0890bb6c9d8e?/d7b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/82ebf3d9a8d4d767c22fcd4f48d92f4596043e51
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/82ebf3d9a8d4d767c22fcd4f48d92f4596043e51?/Uy=zzW
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/82ebf3d9a8d4d767c22fcd4f48d92f4596043e51?/sMq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c2bc27481fbb4548d78c91a07edeafc19f431b96
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c2bc27481fbb4548d78c91a07edeafc19f431b96?/WJ=ubV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c2bc27481fbb4548d78c91a07edeafc19f431b96?/d7b
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8249cededf39d8f4241fa2e2473f73ce90df1816
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8249cededf39d8f4241fa2e2473f73ce90df1816?/sF=3AN
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8249cededf39d8f4241fa2e2473f73ce90df1816?/MqK
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d5ff0d9b4158f1453a400b618258671e34569383
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d5ff0d9b4158f1453a400b618258671e34569383?/JN=1Ly
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d5ff0d9b4158f1453a400b618258671e34569383?/7b5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9c78a0688ef43c988ff59097036461dc208dd8f2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9c78a0688ef43c988ff59097036461dc208dd8f2?/Do=1SM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9c78a0688ef43c988ff59097036461dc208dd8f2?/UyS
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0da32310c6398a95b23bee6e13f1d31ee9737088
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0da32310c6398a95b23bee6e13f1d31ee9737088?/Ii=ZnG
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0da32310c6398a95b23bee6e13f1d31ee9737088?/FjD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/803e3dd7efa0fe7d25a6e260631ee0eea1a2cab9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/803e3dd7efa0fe7d25a6e260631ee0eea1a2cab9?/Pg=HRI
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/803e3dd7efa0fe7d25a6e260631ee0eea1a2cab9?/UyS
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c24f64de1c1da07ebffef9413e4671fc1cead248
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c24f64de1c1da07ebffef9413e4671fc1cead248?/Fa=k7s
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c24f64de1c1da07ebffef9413e4671fc1cead248?/HlF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6298fb7f21c76733d018c28e486d5c5bd67a621e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6298fb7f21c76733d018c28e486d5c5bd67a621e?/wg=hiF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6298fb7f21c76733d018c28e486d5c5bd67a621e?/4Y2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fa5e66e71950b4b9b56428f2f5ff7d16e5e6ce53
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fa5e66e71950b4b9b56428f2f5ff7d16e5e6ce53?/lV=zTw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fa5e66e71950b4b9b56428f2f5ff7d16e5e6ce53?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2ac208eabb88cd3c6a2d41b91ef643d9270f9cd4
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2ac208eabb88cd3c6a2d41b91ef643d9270f9cd4?/tT=hcW
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2ac208eabb88cd3c6a2d41b91ef643d9270f9cd4?/e8c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b3bcf533e50f4a8a72bd2353855fa423c2a73239
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b3bcf533e50f4a8a72bd2353855fa423c2a73239?/eF=SPJ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b3bcf533e50f4a8a72bd2353855fa423c2a73239?/PtN
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6083e830ba271904138112e7e6faed37ba161d2e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6083e830ba271904138112e7e6faed37ba161d2e?/4H=E9z
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6083e830ba271904138112e7e6faed37ba161d2e?/CgA
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/47b2fa0a3bcad19cd0d356b23fe3afca47b08163
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/47b2fa0a3bcad19cd0d356b23fe3afca47b08163?/ip=3X0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/47b2fa0a3bcad19cd0d356b23fe3afca47b08163?/zTx
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7bd1161997c3633a718872b45764ce0df994c768
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7bd1161997c3633a718872b45764ce0df994c768?/QN=oi2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7bd1161997c3633a718872b45764ce0df994c768?/KoI
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b445513f11df0427c62168458180dba395ad8599
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b445513f11df0427c62168458180dba395ad8599?/2s=6Wu
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b445513f11df0427c62168458180dba395ad8599?/Z3X
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5699bb8486efc58d17c665253efe716549d5a735
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5699bb8486efc58d17c665253efe716549d5a735?/pD=U18
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5699bb8486efc58d17c665253efe716549d5a735?/KIm
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b6104803644b7a94c11fee2cdcbfaa85585e7221
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b6104803644b7a94c11fee2cdcbfaa85585e7221?/jg=71L
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b6104803644b7a94c11fee2cdcbfaa85585e7221?/d7b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/519c8a1f64679d7500f1c67c35516139ef7f05eb
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/519c8a1f64679d7500f1c67c35516139ef7f05eb?/An=4fp
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/519c8a1f64679d7500f1c67c35516139ef7f05eb?/OsM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f649043c28b9a23d62020c1e99ab5b39f7bc4aed
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f649043c28b9a23d62020c1e99ab5b39f7bc4aed?/qN=ye2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f649043c28b9a23d62020c1e99ab5b39f7bc4aed?/hBf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0fb3b96d6311bdf2d75946cbbd46271dc9c27e6a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0fb3b96d6311bdf2d75946cbbd46271dc9c27e6a?/YV=wqA
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0fb3b96d6311bdf2d75946cbbd46271dc9c27e6a?/SwQ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5a8aa4d1422e5fbb635368f2c084b3c6d5e284a3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5a8aa4d1422e5fbb635368f2c084b3c6d5e284a3?/sQ=0hb
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5a8aa4d1422e5fbb635368f2c084b3c6d5e284a3?/hBf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/555c72a21b39cbc56d2d7aa7b65af24c3081ed02
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/555c72a21b39cbc56d2d7aa7b65af24c3081ed02?/eb=2wG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/555c72a21b39cbc56d2d7aa7b65af24c3081ed02?/Y2W
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6f36499e05067fd4c1f702c1b71ad3bff63aa3a7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6f36499e05067fd4c1f702c1b71ad3bff63aa3a7?/pC=TXh
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6f36499e05067fd4c1f702c1b71ad3bff63aa3a7?/nHl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c912617564831fe629934e1c31d75bb9e40a9c62
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c912617564831fe629934e1c31d75bb9e40a9c62?/Mq=KoH
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c912617564831fe629934e1c31d75bb9e40a9c62?/DhB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c7971f704f7e681672c3848ba3bd13400fb1c6bc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c7971f704f7e681672c3848ba3bd13400fb1c6bc?/Uu=lVT
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c7971f704f7e681672c3848ba3bd13400fb1c6bc?/PtN
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/47ecddbc64688109da482bab340c12864d7a92a5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/47ecddbc64688109da482bab340c12864d7a92a5?/rr=Oz9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/47ecddbc64688109da482bab340c12864d7a92a5?/iCg
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/15a581a4f0d2e0e07ec7c9c306557e5553c4b90b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/15a581a4f0d2e0e07ec7c9c306557e5553c4b90b?/s8=fGx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/15a581a4f0d2e0e07ec7c9c306557e5553c4b90b?/zTx
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5e1867be6a01634f119842f5c1f6fb65fd2d3744
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5e1867be6a01634f119842f5c1f6fb65fd2d3744?/mg=0AV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5e1867be6a01634f119842f5c1f6fb65fd2d3744?/kEi
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时53分49秒
