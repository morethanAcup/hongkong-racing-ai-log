---
layout: post
title: "开篇：马照跑，与一个十亿美金的传说"
date: 2026-09-29
categories: [开篇]
---

在香港，赛马是一项深入市民生活的全民运动。1997 年香港回归、实行"一国两制"之际，邓小平那句"马照跑，舞照跳"（英文报道原文记作 *"Horse racing will continue, and the dancing parties will go on"*），恰恰是用赛马来象征这种"变与不变"的承诺——无论社会如何更迭，赛马照跑不误。"马照跑"三个字，道尽了赛马在这座城市的普及与分量。

而在今天，人工智能与大数据技术飞速发展，一个很自然的问题，浮现在许多人心中：既然数学、计算机、人工智能已经能下棋、能开车、能写文章，那它们能不能用来研究赛马、甚至预测赛马的结果？这往往是许多人心头挥之不去的一个疑问。

我们研究团队，正是从这样一个疑问出发，开始一段关于"用数学和人工智能研究赛马"的探索。在正式开始我们自己的研究之前，这一篇先把**历史**讲清楚——一段围绕一个名字展开的往事：Bill Benter（比尔·本特）。

---

## 他的故事

要谈"用数学模型研究赛马能不能赚钱"，有一个名字绕不过去：Bill Benter。

围绕他的传说很多：一个美国数学玩家，八十年代跑到香港，靠自建的模型和电脑，据说三十多年下来赢了将近十亿美金，成了博彩公司最不想见到的人之一。

但传说归传说。我们写这篇，不是要为这个人立传，而是想把这段历史的来龙去脉理清楚。下面讲的故事，全部来自一篇英文深度报道（原文链接见文末），而我们对其中的传奇成分，始终持**存疑**态度。

1979 年，Benter 22 岁，本在美国读物理。他读了一本书——《击败庄家》（Beat the Dealer），讲怎么用"算牌"在二十一点里战胜赌场。书看得他坐不住，干脆辍了学，买了一张灰狗巴士票，直奔拉斯维加斯。

在赌城，他白天在 7-Eleven 打工，一小时三美金，晚上拿工资去赌场算牌。几年下来，年收入做到了八万美金。代价是：他被写进了赌场界传说中的黑名单"格里芬名录"——各大赌场人手一份，看见他就赶。赌城，待不下去了。

他盯上了一个更大的市场——香港马会。

原因很简单：这曾是下注规模数一数二的投注市场，九十年代一年能到一百亿美金级别。但想从中赚钱，并不容易——马会抽水高达约 17%。也就是说，你要赢，不光得猜对哪匹马跑第一，还得跑赢这 17% 的"手续费"。无数职业赌徒都死在这一关。

Benter 不信邪。他自学统计、写软件，1985 年拖着三台笨重的 IBM 电脑飞到香港。

结果第一年：惨败。本金 15 万美金，输到只剩 3 万。

换一般人就认了。他没有。

他在惨败里找到一个别人都忽略的突破口：马会每天公开的赔率。

这些赔率，是全香港赌徒用真金白银投出来的。它本身就是一个极其聪明的"集体大脑"——大多数时候，它比任何单个人的判断都准。

Benter 的做法是：拿公开赔率当起点，再用自己的算法去修正它。别人看到的是"大家下注的结果"，他看到的是"这里的概率有没有算错"。就这一招，成了他整套系统里最核心的创新。

1990–91 赛季，他赢了约三百万美金。

真正被反复提起的，是 2001 年。那晚香港马会开出了史上最大的彩池——三 T（一种很难中的连赢组合），累积六期没人中，滚存奖池过亿港币。

Benter 砸了一百六十万港币，买了五万多注组合。结果，中了——实际派彩一千六百万港币。

你猜他干了什么？他看了看中奖的票，跟搭档说："把这钱领了，太不体面了吧？"然后，把彩票锁进保险柜，一分钱没领，任由这笔钱流向慈善机构。

## 故事，真真假假

听到这儿，是不是觉得这人简直神了？但故事越精彩，越要问一句：这事，是真的吗？

我们对此**始终存疑**。尤其要指出的是，原文报道为了增加戏剧性，刻意把 Benter 和马会的关系写成"对立"——仿佛马会曾想赶他走、又给他特殊优待、还视他为头号威胁。但这种写法经不起推敲：

- 马会本质是固定抽水（约 17%）的投注市场，靠成交量赚钱，做的是扩大投注量而非驱逐赢家，没有任何动机或机制去"赶走"一个下注的人；所谓"专用投注终端"不过是马会向所有大额客户提供的标准设施，并非只给他一人的优待；而即便按报道数字，他一个赛季赢约三百万美金，放在香港马会以百亿美金计的年投注总盘里并不突出，顶多算是优质客户之一，远称不上"最好的客户"或"最不想见到的人"。
- 那个"十亿美金"，口径多是"据说"——Benter 在报道里只含糊承认团队累计"接近十亿"，却说自己"不是亿万富翁"，既没有公开审计报告，也没有银行流水可查。
- 更微妙的是，他多年的搭档 Alan Woods，到死都坚持认为 Benter 根本没中那个 2001 年的头奖。合作几十年的合伙人都不信，蹊跷。
- 当然，故事里也有一份硬证据：Woods 2011 年去世后的遗嘱被公开，资产 9.39 亿澳元、负债 15.93 澳元（没错，十几块）。这是法律文件，做不了假——它至少证明，那个圈子里确实有人赚到了惊人的财富。

所以你看：搭档的财富是真的，Benter 本人的故事却真真假假，比想象中复杂。我们把这些讲出来，不是要你信，而是把材料摊开，交给时间。

## 七、故事之外：按图索骥的研究脉络

纠结故事真假意义有限，因为方法写在纸面上，而且可以追溯。

那篇报道里提到，Benter 罕见地把方法写成了一篇学术论文公开发表。而顺着这篇论文的参考文献，又能一路追到更早的研究——这正是"按图索骥"的乐趣：

- **Benter 的论文（1994 / 1995）**：《Computer-Based Horse Race Handicapping and Wagering Systems: A Report》。一个赢了钱的人，把系统白纸黑字公开，成了后来一整代"高科技赌徒"的操作手册。
- **Bolton & Chapman（1986）**：《Searching for Positive Returns at the Track: A Multinomial Logit Model for Handicapping Horse Races》，发表于 *Management Science* 32(8)。这篇比 Benter 早了整整八年，提出了后来被沿用的核心方法（多元逻辑回归模型），也最早指出"冷门的概率误差比热门大得多"。
- **报道本身（2018）**：把这段往事写成大众叙事，让"十亿美金"的传说广为流传。

从 1986 年的顶刊论文，到 1994 年的实战报告，再到 2018 年的媒体报道——一条知识的链条，跨越三十多年。

不过，对**这些历史研究本身**，我们同样持**保留态度**：它们证明了"这条路曾经被走过、被论证过"，但当年的数据、市场与今天已大不相同；它们得出的结论，是那个时代、那个市场下的观察，不等于今天依然成立。我们引用，但不背书。

## 八、把历史讲清楚，就到这里

到这里，这一段历史，我们讲清楚了：一个人、一篇报道、几篇论文，以及一条延续三十多年的研究脉络。

至于我们自己的研究，从下一篇开始。

---

*参考资料（故事全部出自以下报道，我们对传奇成分存疑）：*

1. Kit Chellel, **"The Gambler Who Cracked the Horse-Racing Code"**, Bloomberg Businessweek, 2018-05-03. 原文链接：https://www.bloomberg.com/news/features/2018-05-03/the-gambler-who-cracked-the-horse-racing-code
2. William Benter, **"Computer-Based Horse Race Handicapping and Wagering Systems: A Report"**, 1994 / 1995.
3. Ruth Bolton & Randall Chapman, **"Searching for Positive Returns at the Track: A Multinomial Logit Model for Handicapping Horse Races"**, *Management Science* 32(8): 1040–1060, 1986.

---

## 参考英文翻译附录（English Translation）

**Prologue — Horse Racing Goes On, and a Legend of a Billion Dollars**

*（本附录为英文自由改写，按英文读者习惯行文，非逐字翻译。）*

In Hong Kong, horse racing is a pastime woven deep into the life of the city. When Hong Kong returned to China in 1997 under "One Country, Two Systems," Deng Xiaoping's phrase — "Horse racing will continue, and the dancing parties will go on" — used the races as a symbol of that promise of change-within-continuity: no matter how society changed, the horses would keep running. Those three words, *the horses still run* (马照跑), say it all about how deeply the sport is rooted here.

Today, with artificial intelligence and big data advancing at speed, a natural question weighs on many minds: if math, computers, and AI can already play chess, drive cars, and write articles, could they also be used to study horse racing — even to predict its outcomes? It is a question many people quietly carry.

Our research team set out from exactly that question, on a journey to explore what math and AI can reveal about the sport. Before we turn to our own work, this piece lays out the history — a story that revolves around one name: Bill Benter.

### His Story

If you want to ask whether mathematical models can actually make money at the races, one name keeps coming up: Bill Benter.

The legends around him are many: an American math whiz who flew to Hong Kong in the 1980s, built his own models and machines, and supposedly won close to a billion dollars over three decades — becoming, by some accounts, one of the bettors bookmakers least wanted to see.

But legends are legends. We are not writing this to glorify the man; we want to untangle where the story came from. Everything below is drawn from a single in-depth English report (link at the end), and we remain skeptical of its more mythical elements.

In 1979, Benter, then 22, was studying physics in the United States. He read *Beat the Dealer*, a book on beating blackjack through card counting. It hooked him. He dropped out, bought a Greyhound bus ticket, and headed for Las Vegas.

In the casinos he worked days at a 7-Eleven for three dollars an hour and counted cards at night with his wages. Within a few years he was pulling in $80,000 a year — at the cost of landing on the "Griffin Book," the casinos' shared blacklist. Vegas was no longer an option.

He set his sights on a bigger market — the Hong Kong Jockey Club.

The reason was simple: it was then one of the largest betting pools in the world, reaching the ten-billion-dollar range annually by the 1990s. But making money from it was no easy task — the Club takes roughly a 17% cut. To win, you had not only to pick the winner but to beat that 17% "fee." Countless professional gamblers died on that hill.

Benter was undeterred. He taught himself statistics, wrote software, and in 1985 flew to Hong Kong with three bulky IBM computers.

Result, year one: a rout. Of $150,000 in capital, only $30,000 remained.

Most would have quit. He didn't.

In that failure he found an opening everyone else had missed: the Jockey Club's publicly posted odds.

Those odds are the collective judgment of every bettor in Hong Kong, each putting real money behind it. They are, in effect, a remarkably smart "crowd brain" — more often right than any single person.

Benter's trick was to take the public odds as a starting point, then correct them with his own algorithm. Where others saw "how the crowd bet," he saw "where the probabilities might be wrong." That one move became the core innovation of his entire system.

In the 1990–91 season, he won about $3 million.

What gets repeated most is 2001. That year the Hong Kong Jockey Club offered the largest jackpot the city had ever seen — the Triple Trio, a notoriously hard combination bet, rolled over six times with no winner, pushing the rolled-over pool past HK$100 million.

Benter sank HK$1.6 million into more than 50,000 combinations. And he hit — an actual payout of HK$16 million.

What did he do next? He looked at the winning ticket, told his partner it would be "rather undignified" to cash it, locked the ticket in a safe, and collected nothing — letting the money flow to charity.

### Truth and myth

By now you might think the man was a god. But the more dazzling the story, the more we should ask: is it true?

We remain skeptical. In particular, the original report, to heighten the drama, deliberately framed Benter's relationship with the Club as adversarial — as if the Club had wanted to drive him out, yet also granted him special privileges, and treated him as its number-one threat. That framing does not hold up:

- The Jockey Club is, at its core, a betting market that takes a fixed cut (~17%) and profits from volume; its business is to grow the pool, not expel winners, and it has no motive or mechanism to "drive away" a bettor. The so-called "dedicated betting terminal" was simply a standard facility the Club offers all high-volume customers, not a privilege reserved for him alone. And even by the report's own numbers, his ~$3 million seasonal win, set against the Club's annual turnover measured in tens of billions of dollars, is unremarkable — at best one of its quality customers, far from its "best customer" or "least wanted bettor."
- That "billion dollars" is mostly "supposedly" — in the report, Benter only vaguely conceded his operation made "close to a billion," while saying he was "not a billionaire," with no public audit and no bank statements to check.
- More tellingly, his longtime partner Alan Woods insisted to the end of his life that Benter never won that 2001 jackpot. When a decades-long partner doesn't believe it, something is off.
- To be fair, there is one hard piece of evidence: Woods' will, made public after his 2011 death, listed assets of A$939 million and liabilities of A$15.93 (yes, about sixteen dollars). A legal document can't be faked — at minimum it proves that someone in that circle did amass staggering wealth.

So you see: the partner's wealth was real, while Benter's own story is a mix of truth and myth, more complicated than it seems. We lay it out not so you'll believe it, but so the material is on the table, for time to judge.

### Beyond the story: following the paper trail

Arguing over the legend's truth has limited value, because the method is on paper — and traceable.

The report notes that Benter did something unusual: he published his method as an academic paper. And following that paper's references leads back to even earlier work — the real pleasure of "following the trail by the map":

- **Benter's paper (1994 / 1995):** *Computer-Based Horse Race Handicapping and Wagering Systems: A Report*. A man who had won money laid out his system in black and white, and it became the operating manual for a whole generation of "high-tech gamblers."
- **Bolton & Chapman (1986):** *Searching for Positive Returns at the Track: A Multinomial Logit Model for Handicapping Horse Races*, in *Management Science* 32(8). Published eight years before Benter, it proposed the core method later adopted (a multinomial logit model) and was first to note that the probability error on longshots is far larger than on favorites.
- **The report itself (2018):** turned the episode into a popular narrative, spreading the "billion-dollar" legend widely.

From a top journal paper in 1986, to a field report in 1994, to a media story in 2018 — a chain of knowledge spanning more than three decades.

Still, we treat **these historical studies themselves** with **reservation**: they prove this path was walked and argued before, but the data and markets of that era differ greatly from today's; their conclusions were observations of that time and market, not guarantees that hold now. We cite, but do not endorse.

### The history, told

Here, this piece of history is told: one man, one report, a few papers, and a research lineage stretching over thirty years.

As for our own research, starting with the next post.

*References:*

1. Kit Chellel, "The Gambler Who Cracked the Horse-Racing Code," *Bloomberg Businessweek*, 2018-05-03. https://www.bloomberg.com/news/features/2018-05-03/the-gambler-who-cracked-the-horse-racing-code
2. William Benter, "Computer-Based Horse Race Handicapping and Wagering Systems: A Report," 1994 / 1995.
3. Ruth Bolton & Randall Chapman, "Searching for Positive Returns at the Track: A Multinomial Logit Model for Handicapping Horse Races," *Management Science* 32(8): 1040–1060, 1986.
