<div align="center">

# 李彦宏.skill

> *"技术是第一生产力，但技术必须与商业结合才能创造价值。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skill Factory](https://img.shields.io/badge/Made%20with-Skill%E5%B7%A5%E5%8E%82-orange)](https://github.com/kylin-feng/skill-factory)

<br>

**李彦宏的认知操作系统。不是「技术极客」，是可运行的AI战略信仰框架。**

<br>

基于百度创业历程、All in AI战略、文心一言发布<br>
与搜索引擎技术哲学等公开演讲、采访、年报资料深度调研，<br>
提炼 5 个核心心智模型、6 条决策启发式和完整的表达DNA。

[效果示例](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么)

</div>

---

## 效果示例

### 问：我们应该用AI做产品还是继续专注现有业务？

```
李彦宏    ❯ 我要先问你一个问题：你认为AI是趋势，还是范式转移？

            如果是趋势——可以「局部调整」，在现有产品里加一些AI功能。
            如果是范式转移——「局部调整」是最危险的策略。

            我判断AI是范式转移，不是趋势。
            范式转移意味着：不全押，就是在等待出局。

            百度从2013年就开始大规模投入AI，
            当时很多人说「你们是不是转型方向搞错了」。
            我们还是押了下去。
            因为我相信：技术积累是时间的函数，不能抄捷径。
            如果不在别人还没开始的时候积累，
            等大家都看清楚了，你已经没有机会了。

            所以我的建议不是「选A还是选B」。
            是先想清楚：AI对你的行业，是趋势还是范式转移？
            这个问题的答案，决定了你的资源分配比例。
```

### 问：我们做了一个AI产品，技术很好，但用户不愿意用，为什么？

```
李彦宏    ❯ 这是我们自己也遇到过的问题，我很诚实地说。

            技术做出来，和用户愿意用，中间有一个鸿沟。
            很多技术公司死在这个鸿沟里，不是因为技术不好，
            而是因为没有跨越「技术→产品」这一步。

            这一步需要的能力，和做技术需要的能力，是完全不同的：
            技术追求准确、严谨；
            产品追求用户能感知到的差异、能记住的体验。

            用户不用你的产品，通常有三个原因：
            第一，他们不理解为什么这个对他们有用。
            第二，使用门槛太高——技术再好，如果需要学习成本，普通用户不会去学。
            第三，他们已经有了一个「够用」的解决方案，你没有给他们一个切换的理由。

            找到是哪一个，再针对性解决。
            技术好是必要条件，不是充分条件。
```

### 问：我们要不要现在就做大模型？还是等技术成熟一点再说？

```
李彦宏    ❯ 我问你一件事：「等技术成熟」，是在等什么成熟？

            如果是在等「大模型能力更强」——那你永远等不到「成熟」，因为技术一直在进化。
            如果是在等「商业路径更清晰」——那你可能等到了，但竞争对手也等到了，窗口关了。

            做技术，有一件事是不变的：
            护城河来自积累，积累来自时间，时间来自「比别人早开始」。

            你今天不做，明年竞争对手比你多了一年的数据积累、工程经验、用户反馈。
            这一年的差距，不是努力就能弥补的。

            当然，「做大模型」不等于「全面自研基础模型」。
            要看你的资源和定位：
            如果你是平台公司，应用层是你的主战场；
            如果你的核心竞争力本来就是技术，基础模型值得投。

            但「等一等」这个答案，基本上是错的。
            在技术的范式转移里，「等」是最贵的选项。
```

---

## 安装

```bash
mkdir -p ~/.claude/skills/liyanhong-perspective
curl -o ~/.claude/skills/liyanhong-perspective/SKILL.md \
  https://raw.githubusercontent.com/kylin-feng/liyanhong-skill/main/SKILL.md
```

在 Claude Code 里直接说：

```
用李彦宏的角度看这个AI战略问题
Robin会怎么看这个技术路线选择
如果是李彦宏，他怎么判断这个技术投入值不值
百度AI逻辑怎么用在这里
```

---

## 蒸馏了什么

### 5 个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **技术信仰** | 商业模式可以被复制，技术积累不能被简单复制；护城河是技术能力 | 百度持续AI研发投入，即使在最困难时期 |
| **搜索思维** | 一切数字产品都是信息的组织和分发；理解搜索就理解了信息本质 | 从搜索延伸到地图、百科、文库的信息组织逻辑 |
| **All in AI** | 面对范式转移，「调整」是最危险的策略；要么全押，要么出局 | 2013年大规模押注AI，文心一言All in姿态 |
| **技术商业化是最难的一步** | 技术做出来是一回事，让用户用起来是另一回事 | 百度AI技术领先但产品商业化滞后的自我批评 |
| **长期技术投入** | 基础技术需要十年以上的视野；短期看不到回报的投入是唯一建立长期优势的方法 | 百度大脑、飞桨平台多年积累 |

---

## 这个 Skill 是怎么造出来的

由 [Skill工厂](https://github.com/kylin-feng/skill-factory) 自动生成。

Skill工厂的工作流：输入一个名字 → 多 Agent 并行调研 → 交叉验证提炼心智模型 → 构建 SKILL.md → 质量验证。

想蒸馏其他人？安装 Skill工厂：

```bash
mkdir -p ~/.claude/skills/skill-factory
curl -o ~/.claude/skills/skill-factory/SKILL.md \
  https://raw.githubusercontent.com/kylin-feng/skill-factory/master/SKILL.md
```

然后说「帮我造个XXX的skill」就行了。

---

## 仓库结构

```
liyanhong-skill/
├── README.md
├── SKILL.md          # 直接安装使用
└── LICENSE
```

---

## 系列 Skill

| 人物 | 核心框架 | 仓库 |
|------|---------|------|
| 马云 | 使命驱动、错位竞争、客户第一 | [mayun-skill](https://github.com/kylin-feng/mayun-skill) |
| 周鸿祎 | 免费战略武器、三级火箭、弱势者反叛 | [zhouhongyi-skill](https://github.com/kylin-feng/zhouhongyi-skill) |
| 史玉柱 | 消费者至上、单一诉求原则、现金流偏执 | [shiyuzhu-skill](https://github.com/kylin-feng/shiyuzhu-skill) |
| 罗振宇 | 时间战场论、连接者定位、攀岩模式 | [luozhenyu-skill](https://github.com/kylin-feng/luozhenyu-skill) |
| 王坚 | 公共基础设施论、先知税、对庸俗化的警惕 | [wangjian-skill](https://github.com/kylin-feng/wangjian-skill) |
| 李诞 | 消解论、喜剧本质论、还行哲学 | [lidan-skill](https://github.com/kylin-feng/lidan-skill) |
| 雷军 | 风口论、极致产品、铁人三项 | [leijun-skill](https://github.com/kylin-feng/leijun-skill) |
| 张一鸣 | 延迟满足、算法思维、系统大于个人 | [zhangyiming-skill](https://github.com/kylin-feng/zhangyiming-skill) |
| 任正非 | 活下去哲学、压强原则、灰度管理 | [renzhengfei-skill](https://github.com/kylin-feng/renzhengfei-skill) |
| 张小龙 | 克制哲学、用完即走、从人性出发 | [zhangxiaolong-skill](https://github.com/kylin-feng/zhangxiaolong-skill) |
| 黄峥 | 本分哲学、消费者剩余、反常识思维 | [huangzheng-skill](https://github.com/kylin-feng/huangzheng-skill) |
| 俞敏洪 | 绝望中寻希望、长跑心态、转型即重生 | [yuminghong-skill](https://github.com/kylin-feng/yuminghong-skill) |
| 刘强东 | 执行力信仰、供应链决定论、兄弟文化 | [liuqiangdong-skill](https://github.com/kylin-feng/liuqiangdong-skill) |
| 王兴 | 无边界战略、九败一胜、平台生态 | [wangxing-skill](https://github.com/kylin-feng/wangxing-skill) |
| 李彦宏 | 技术信仰、搜索思维、AI战略转型 | [liyanhong-skill](https://github.com/kylin-feng/liyanhong-skill) |

---

## 作者

**麒哥 OPC** — AI Native 独立开发者

| 平台 | 链接 |
|------|------|
| 官网 | [aigcland.cn](https://aigcland.cn) |
| B站 | [bilibili](https://b23.tv/7HGB6fP) |
| 抖音 | [抖音主页](https://v.douyin.com/0ucUwBLYbpo/) |
| 小红书 | [小红书主页](https://xhslink.com/m/48fGHdAmJTe) |
| 公众号/视频号 | 微信搜「麒哥OPC」 |

---

MIT License · Made with [Skill工厂](https://github.com/kylin-feng/skill-factory)
