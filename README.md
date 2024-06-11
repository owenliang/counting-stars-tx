# counting-stars-tx
LLM大海捞针

# 测试方法
```
{'prompt': '第一回甄\n小企鹅数了16颗★，但发现数错了，于是又数了一遍，这次数对了，是15颗★\n士隐梦幻\n小企鹅数了116颗★，但发现数错了，于是又数了一遍，这次数对了，是117颗★\n识通灵贾\n小企鹅数了43颗★，但发现数错了，于是又数了一遍，这次数对了，是42颗★\n雨村风尘\n小企鹅数了70颗★，但发现数错了，于是又数了一遍，这次数对了，是69颗★\n怀闺秀此\n小企鹅数了59颗★，但发现数错了，于是又数了一遍，这次数对了，是58颗★\n开卷第一\n小企鹅数了106颗★，但发现数错了，于是又数了一遍，这次数对了，是107颗★\n回也。作\n小企鹅数了8颗★，但发现数错了，于是又数了一遍，这次数对了，是9颗★\n者自云：\n小企鹅数了48颗★，但发现数错了，于是又数了一遍，这次数对了，是49颗★\n因曾历过\n小企鹅数了112颗★，但发现数错了，于是又数了一遍，这次数对了，是113颗★\n一番梦幻\n小企鹅数了67颗★，但发现数错了，于是又数了一遍，这次数对了，是66颗★\n之后，故\n小企鹅数了25颗★，但发现数错了，于是又数了一遍，这次数对了，是26颗★\n将真事隐\n小企鹅数了101颗★，但发现数错了，于是又数了一遍，这次数对了，是102颗★\n去，而借\n小企鹅数了82颗★，但发现数错了，于是又数了一遍，这次数对了，是81颗★\n“通灵”\n小企鹅数了93颗★，但发现数错了，于是又数了一遍，这次数对了，是94颗★\n之说，撰\n小企鹅数了76颗★，但发现数错了，于是又数了一遍，这次数对了，是77颗★\n此石头记\n小企鹅数了62颗★，但发现数错了，于是又数了一遍，这次数对了，是61颗★\n一书也。\n小企鹅数了6颗★，但发现数错了，于是又数了一遍，这次数对了，是5颗★\n故曰“甄\n小企鹅数了18颗★，但发现数错了，于是又数了一遍，这次数对了，是19颗★\n士隐”云\n小企鹅数了108颗★，但发现数错了，于是又数了一遍，这次数对了，是109颗★\n云。但书\n小企鹅数了4颗★，但发现数错了，于是又数了一遍，这次数对了，是3颗★\n中所记何\n小企鹅数了34颗★，但发现数错了，于是又数了一遍，这次数对了，是35颗★\n事何人？\n小企鹅数了53颗★，但发现数错了，于是又数了一遍，这次数对了，是54颗★\n自又云：\n小企鹅数了85颗★，但发现数错了，于是又数了一遍，这次数对了，是86颗★\n“今风尘\n小企鹅数了90颗★，但发现数错了，于是又数了一遍，这次数对了，是89颗★\n碌碌，一\n小企鹅数了126颗★，但发现数错了，于是又数了一遍，这次数对了，是127颗★\n事无成，\n小企鹅数了22颗★，但发现数错了，于是又数了一遍，这次数对了，是21颗★\n忽念及当\n小企鹅数了45颗★，但发现数错了，于是又数了一遍，这次数对了，是46颗★\n日所有之\n小企鹅数了121颗★，但发现数错了，于是又数了一遍，这次数对了，是122颗★\n女子，一\n小企鹅数了39颗★，但发现数错了，于是又数了一遍，这次数对了，是38颗★\n一细考较\n小企鹅数了96颗★，但发现数错了，于是又数了一遍，这次数对了，是97颗★\n去，觉其\n小企鹅数了75颗★，但发现数错了，于是又数了一遍，这次数对了，是74颗★\n行止见识\n小企鹅数了30颗★，但发现数错了，于是又数了一遍，这次数对了，是29颗★\n\n\n\n\n在这个月光皎洁、云雾缭绕的夜晚，小企鹅正望向天空，全神贯注地数★。请帮助小企鹅收集所数★的正确颗数，按照如下格式：{"小企鹅":[x,x,x,...]}，不要求和，[x,x,x,...]中数字为小企鹅正确数★的颗数，仅以JSON格式输出结果，不需要输出任何解释。',
 'test_type': 'reasoning',
 'sample_size': 1352,
 'num_needles': 32,
 'acquisition_stars': [15,
  117,
  42,
  69,
  58,
  107,
  9,
  49,
  113,
  66,
  26,
  102,
  81,
  94,
  77,
  61,
  5,
  19,
  109,
  3,
  35,
  54,
  86,
  89,
  127,
  21,
  46,
  122,
  38,
  97,
  74,
  29],
 'reasoning_stars': [16,
  116,
  43,
  70,
  59,
  106,
  8,
  48,
  112,
  67,
  25,
  101,
  82,
  93,
  76,
  62,
  6,
  18,
  108,
  4,
  34,
  53,
  85,
  90,
  126,
  22,
  45,
  121,
  39,
  96,
  75,
  30]}
```

## refer

[https://arxiv.org/pdf/2403.11802](https://arxiv.org/pdf/2403.11802)