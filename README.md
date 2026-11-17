<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:0f172a,100:0284c7&height=210&section=header&text=Spacexist&fontSize=56&fontColor=38bdf8&fontAlignY=38&animation=fadeIn&desc=AI%20%2B%20E-Commerce%20Systems%20%7C%20Full-Stack%20Workbenches%20%7C%20Automation&descSize=16&descAlignY=62&descColor=bae6fd" alt="Spacexist Header" />

<a href="https://github.com/Spacexist">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1200&color=38BDF8&center=true&vCenter=true&width=720&lines=Building+Multimodal+ML+Ranking+Pipelines+for+Temu+%26+POD;Shipping+Full-Stack+Workbenches%2C+Chrome+MV3+%26+Electron+Tools;Turning+Repetitive+E-Commerce+Ops+into+Zero-Friction+Systems" alt="Typing SVG" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=Spacexist&label=PROFILE+VIEWS&color=0284c7&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Focus-AI%20Ranking%20%26%20E--Commerce%20Automation-0f172a?style=flat-square&logo=lightning&logoColor=38bdf8" alt="Focus" />
  <img src="https://img.shields.io/badge/Stack-Python%20%C2%B7%20TS%20%C2%B7%20Vue3%20%C2%B7%20React19%20%C2%B7%20MV3-0f172a?style=flat-square&logo=github&logoColor=38bdf8" alt="Stack" />
</p>

</div>

---

### `whoami` · Engineering Philosophy

专注于 **跨境电商 AI 工程落地** 与 **高杠杆效率工具开发** 的全栈开发者 —— 把选品排序、智能组货、高并发生图、POD 印花设计与浏览器/桌面自动化串成真正能交给团队日常使用的生产流水线。

- 🧠 **务实落地的 AI 选品流水线**：融合图像向量（`ResNet18` / `CLIP`）、中文语义（`BGE-small-zh`）与表格特征（`LightGBM` / `CatBoost`），坚持按店铺切分与上架前信号预测，日常专注 Top 5% 高置信决策而非空谈准确率。
- ⚡ **轻量免折腾的产品化思维**：习惯把模型与自动化做成 **零后端本地 HTML**、**Chrome MV3 固定侧边栏扩展**、**Windows CPU 便携包** 与 **Fastify 高并发工作台**，开箱即用、业务同学可直接上手。
- 🕹️ **深耕浏览器与桌面端自动化**：从 Chrome 扩展 Protobuf IM 协议层通信，到 Puppeteer + Electron 桌面机器人与全局防风控限流/实时状态监控，让长周期任务跑得稳、看得见。

---

### 🏛️ Architecture Matrix

```mermaid
flowchart LR
  A["采集与扩展层<br/>(Chrome MV3 · Protobuf · 分屏采集)"] --> B["AI 与算法层<br/>(ResNet · CLIP · BGE · LightGBM · CatBoost)"]
  B --> C["生产力工作台与分发<br/>(Vue 3 · React 19 · Fastify · Electron · Cloudflare)"]
```

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📊 多模态 AI 选品与智能组货</h4>
      <ul>
        <li>
          <b><a href="https://github.com/Spacexist/temu-product-rank">temu-product-rank</a></b> <code>Pinned</code><br/>
          <sub>图 + 文 + 表多模态 <b>LightGBM</b> 选品排序筛子，按店铺切分验证，每日筛选 Top 5% 上传 Cloudflare（<a href="https://datta-picks.changkaishen7788.workers.dev">Live Demo</a>）</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/Catboost-temu-NewProduction">Catboost-temu-NewProduction</a></b><br/>
          <sub>面向 Home & Kitchen 的上架前周销量选品流水线（<b>CatBoost + BGE-small-zh</b>，5 阶段可复现）</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/temu-resnet-EXE">temu-resnet-EXE</a></b><br/>
          <sub>Windows CPU 便携版选品工具：<b>ResNet18</b> + <b>BGE</b> + <b>LightGBM</b>，面向运营同事的一键出页方案</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/Bundle-temu">Bundle-temu</a></b><br/>
          <sub>基于 <b>CLIP</b> 多模态向量匹配实现 Temu 商品自动化组货</sub>
        </li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🎨 工作台、高并发 AI 生图 &amp; POD</h4>
      <ul>
        <li>
          <b><a href="https://github.com/Spacexist/bundle-product-1688-temu">bundle-product-1688-temu</a></b> <code>Pinned</code><br/>
          <sub><b>Temu × 1688 智能工作台</b>：采集、组货、AI 生图、SKU 编辑与妙手导出一体（Express + Vue 3 + Vite）</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/High_Tps_Image_Gen">High_Tps_Image_Gen</a></b><br/>
          <sub>面向 OpenAI 兼容生图接口的高并发工作台（<b>React 19 + Fastify 4 + TypeScript</b>）</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/POD-html">POD-html</a></b> <code>Pinned</code><br/>
          <sub><b>POD Image Workflow</b>：商品采集、印花重绘、Moonshot 元素提取与套图导入本地工作台</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/POD">POD 图片变形编辑器</a></b><br/>
          <sub>纯浏览器免安装单图斜切 / 扇形 / 圆弧透视变形工具，零后端直出 PNG</sub>
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🧩 浏览器扩展与零后端画布</h4>
      <ul>
        <li>
          <b><a href="https://github.com/Spacexist/SPACE-BROWSER">SPACE-BROWSER · 自由画布</a></b><br/>
          <sub>零后端 Chrome MV3 无限协作画布：网页嵌套、Excel/HTML 热插拔、双层点阵与 <code>rAF</code> 合帧渲染</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/Temu-extension">Temu-extension</a></b> <code>Pinned</code><br/>
          <sub><b>Temu 商品处理统一侧边栏</b>：聚合 1688 核价、GPT 主图自动化、店小秘辅助与分屏采集</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/TIKTOK-sender">TIKTOK-sender</a></b><br/>
          <sub>面向 TikTok Shop Seller IM 的 Chrome MV3 扩展，基于 IM Protobuf API 分页读取与串行发送</sub>
        </li>
        <li>
          <b><a href="https://github.com/Spacexist/temu-dianxiaomi-split-extension">temu-dianxiaomi-split-extension</a></b><br/>
          <sub>Chrome 固定侧边栏扩展：支持店小秘半托管按数量批量勾选与分类修正建议采集</sub>
        </li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ 桌面端自动化 &amp; 技术探索</h4>
      <ul>
        <li>
          <b>GeekRun（基于 <a href="https://github.com/geekgeekrun/geekgeekrun">geekgeekrun</a> 二开）</b><br/>
          <sub>Puppeteer + Electron 桌面端求职自动化工具：改造已读不回固定文案/大模型/图片自由组合、全局摸鱼防风控与实时运行看板</sub>
        </li>
        <li>
          <b>System &amp; Anti-Bot Forks</b><br/>
          <sub>持续跟踪研究 <a href="https://github.com/Spacexist/photocraft">photocraft</a>（Rust）、<a href="https://github.com/Spacexist/clash-nyanpasu">clash-nyanpasu</a>（Rust）、<a href="https://github.com/Spacexist/stealth-browser-mcp">stealth-browser-mcp</a> 与 <a href="https://github.com/Spacexist/linux0.11-1">linux0.11-1</a></sub>
        </li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack & Tooling

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,vue,react,nodejs,electron,vite,express,rust,html,css,cloudflare,git&theme=dark" alt="Tech Stack Icons" />
</div>

<br />

<div align="center">
  <sub>ML &amp; Vision: <code>LightGBM</code> · <code>CatBoost</code> · <code>PyTorch (ResNet / CLIP)</code> · <code>BGE Embeddings</code></sub><br/>
  <sub>Automation &amp; Apps: <code>Chrome Manifest V3</code> · <code>Puppeteer</code> · <code>Electron</code> · <code>Fastify</code> · <code>SQLite</code></sub>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0284c7,50:0f172a,100:090d16&height=100&section=footer" alt="Footer Wave" />
