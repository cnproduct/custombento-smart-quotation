# 耐科便当盒全品类智能选型与外贸阶梯报价平台
## Naike Tableware Smart Bento CPQ Platform & Tiered Quotation Engine

[![GitHub Pages Deployment](https://github.com/cnproduct/custombento-smart-quotation/actions/workflows/deploy.yml/badge.svg)](https://github.com/cnproduct/custombento-smart-quotation/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-008290?style=flat&logo=googlechrome)](https://cnproduct.github.io/custombento-smart-quotation/)
[![Factory Partner](https://img.shields.io/badge/Factory-Naike%20Tableware-0ea5b6)](https://www.custombentofactory.com)
[![Audits](https://img.shields.io/badge/Audits-Disney%20FAMA%20%7C%20Coca--Cola%20SGP%20%7C%20Sedex-10b981)](#)

专门为 **晋江市耐克礼品玩具有限公司 (Naike Tableware / [www.custombentofactory.com](https://www.custombentofactory.com))** 打造的企业级 B2B 智能选型与外贸阶梯报价平台（CPQ 工业软件前端）。

---

## 🌐 在线体验地址 (Live Demo)

- **GitHub Pages 演示地址**：[https://cnproduct.github.io/custombento-smart-quotation/](https://cnproduct.github.io/custombento-smart-quotation/)
- **耐科官方出海独立站**：[https://www.custombentofactory.com](https://www.custombentofactory.com)
- **大厂验厂资质**：Disney FAMA (`W128-4829-1`) · Coca-Cola SGP (`ZC421894101`) · Sedex 4-Pillar SMETA · ISO 9001:2015 · 厦门港 60km 快速集港

---

## 🏗️ 6 大核心核价模块架构

```
┌────────────────────────────────────────────────────────────────────────┐
│             耐科便当盒全品类智能选型报价平台 (B2B CPQ 闭环架构)            │
├───────┬──────────────────────┬─────────────────────────────────────────┤
│ 模块  │ 功能名称             │ 业务输入与制造输出                      │
├───────┼──────────────────────┼─────────────────────────────────────────┤
│ M1    │ 参数标准化与补全     │ 客户自然语言询盘 → 确定性工程规格表     │
│ M2    │ 图形化方案与结构透视 │ 2D 截面剖视工程图 + 铂金硅胶气密槽标注  │
│ M3    │ 选型与 BOM 清单生成  │ 原辅料清单 (PP/钢/硅胶/彩盒) + ERP 拉价 │
│ M4    │ 工艺路线与工时工费   │ 高速注塑/LSR/超声波组装/跌落抽检节拍   │
│ M5    │ 成本核算与阶梯报价   │ FOB 厦门阶梯报价 (1k/3k/5k/10k) + 手工微调│
│ M6    │ 外贸技术响应包导出   │ 英文外贸报价邮件草稿 + 形式发票 (PI) PDF│
└───────┴──────────────────────┴─────────────────────────────────────────┘
```

---

## ✨ 核心功能亮点与工程特性

### 1. 🍱 预置耐科 9 大主力品类现模外箱与工程数据
覆盖海外主流商超采购的完整产品矩阵：
1. **儿童 5 格防漏便当盒 (Bentgo 同款销冠)** · `NK-KB5-001` (215×165×50mm, 24 pcs/箱)
2. **可注水保冷便当盒 (带冷凝托盘)** · `NK-CHL-002` (220×170×55mm, 16 pcs/箱)
3. **黑科技可微波 304 不锈钢便当盒** · `NK-MSS-008` (220×155×60mm, 24 pcs/箱)
4. **日式双层手提成人便当盒** · `NK-STK2-004` (185×105×110mm, 24 pcs/箱)
5. **天然小麦秸秆环保三格盒** · `NK-WS3-006` (205×130×70mm, 36 pcs/箱)
6. **重装 304 不锈钢三格盒** · `NK-SS3-003` (230×175×55mm, 20 pcs/箱)
7. **TikTok 爆款八格便携零食盒** · `NK-SNK-007` (310×235×65mm, 12 pcs/箱)
8. **54oz 超大容量沙拉保鲜大碗** · `NK-SLD-005` (195×195×115mm, 18 pcs/箱)
9. **600D rPET 环保保温便当包** · `NK-BAG-010` (260×200×95mm, 40 pcs/箱)

### 2. 🧠 自然语言智能提取 (NLP Parser)
- 业务员直接粘贴客户邮件或 WhatsApp 原话（如：“*定制 3000 套儿童 5 格盒，Pantone 320C 薄荷绿，丝印白色 Logo，单套独立彩盒，FOB 厦门港*”）。
- 系统自动解析提取品类、容量、分格数、材质、数量、Pantone 色号及印刷方式，并在参数表中清晰标注来源（买家输入 / AI模具推荐 / 耐科标准 / 必填缺失）。

### 3. 📐 动态 2D SVG 截面工程图 (SVG Blueprint)
- 实时绘制便当盒剖面图，包含：
  - 外壳与内胆结构
  - 独立干湿分离分格隔断
  - LSR 液态铂金硅胶气密槽（-50kPa 真空气密试验合格）
  - TPE 加厚防摔护角（2 米水泥地面抗摔）
  - 双侧加宽人体工学锁扣与中心 Logo 印刷区域
  - 长度、高度红线工程尺寸标注

### 4. 🔗 实时 BOM 与模拟 ERP 联动
- 包含 PP 树脂、SUS 304 卷板、LSR 铂金硅胶、TPE 包胶、Pantone 定制色母、单套瓦楞彩盒、防尘内袋、5 层加硬外销纸箱。
- 业务员可实时在表格中修改原辅料单价，总成本与最终报价瞬间自动联动更新。

### 5. ⏱️ 真实注塑车间工艺工时估算
- 包含注塑成型、液态硅胶密封注塑、冲压拉伸、Logo 丝印/激光、锁扣装配、负压抽检与彩盒包装。
- 支持换型准备时间与单件循环节拍（秒/只）人工微调与一键重算。

### 6. 💰 阶梯核价与业务员成本手动微调
- 按照 1,000 / 3,000 / 5,000 / 10,000 套阶梯核算 FOB 厦门港 USD 与 CNY 单价。
- 提供外贸利润率滑块（12% ~ 35%）。
- 设有业务员手动成本调整面板（材料、工时、管理费、集港运杂费），可自由覆盖系统预估值。

### 7. ✉️ 响应包与单证一键导出
- **英文外贸报价邮件**：一键复制完整正文、一键调起邮件客户端、一键下载标准 `.eml` 邮件文件。
- **形式报价单 (Proforma Quotation Sheet)**：内置耐科工厂信头、迪士尼验厂号、产品工程规格、阶梯价格表与付款交期条款，支持调起浏览器打印并另存为高质量 PDF。

---

## 🛠️ 本地运行开发

纯前端架构，零外部依赖，极速秒开：

```bash
# 克隆仓库
git clone https://github.com/cnproduct/custombento-smart-quotation.git
cd custombento-smart-quotation

# 启动本地服务器
python3 -m http.server 8080

# 打开浏览器体验
open http://localhost:8080
```

---

## 🏭 工厂联系方式 (Naike Tableware)

- **企业名称**：晋江市耐克礼品玩具有限公司 (Jinjiang Naike Gifts Co., Ltd.)
- **官方独立站**：[https://www.custombentofactory.com](https://www.custombentofactory.com)
- **业务邮箱**：`info@naikegroup.com`
- **业务电话 / WhatsApp**：`+86 135 9922 0505`
- **工厂地址**：中国福建省泉州晋江市内坑镇紫东工业区 18 号 (距厦门港 60 公里)
