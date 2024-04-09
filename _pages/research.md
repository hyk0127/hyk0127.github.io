---
layout: archive
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Papers

### [Related-Party Trades in Vertical Integration](https://www.dropbox.com/s/qi2nyc90av0op15/Hong_RPTVI_230412.pdf?raw=1) [[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3983336)]

Despite the importance of vertical trade in theories of the firm, an empirical literature using proxy-measures has documented little such trade. I revisit this conclusion using economy-wide firm-level data from South Korea, where related-party trades are directly observable. I show that the true prevalence and volume of intra-party trade is much higher than previous measures indicate. Past proxies, which rely heavily on economy-wide input-output tables, dramatically underestimate related-party trade, capturing only 17.6% of related parties that trade and 32.6% of their sales volume. Using supervised machine-learning, I propose alternatives to relying solely on input-output tables to infer trade.

### [It Takes a Village: How Business Groups Help Out Member Firms in Distress](https://www.dropbox.com/scl/fi/wo6ok5jubi0bsms3oozsa/Hong_village_web.pdf?rlkey=3suz3ypl59bmbb9q9z4f7woj2&raw=1)

This paper provides the first empirical evidence that intra-business group capital markets support the survival of `zombie' member firms, using a novel dataset of detailed related-party transactions from Korea. Group-affiliated zombie firms show significantly stronger survival rates but worse recovery rates from zombie status, signaling that selection into groups is not the main driver of better survival. I show that while a group-affiliated firm's external debts shrink rapidly following the formalization of its zombie status, internal debts remain at their peak level reached at zombification for an extended period. The same difference is documented for group-affiliated firms nearing closure. Such life-sustaining internal debts arise mostly from parent firms, while debts from subsidiaries or weakly connected related parties behave more similarly to external debts. 

## Works in Progress

### Trade Credit as a Contract Enforcement Device: Evidence from Related-Party Trades

A large literature has documented a seeming inefficiency in trade credit practices: smaller firms provide credit to their larger trade partners that have lower external financing costs. This paper presents empirical evidence supporting the hypothesis that larger firms utilize trade credit as a contract enforcement device. By utilizing a novel firm-level data on related-party trades in Korea, I show that in trades where one side of the buyer-supplier relationship completely controls the other, financing cost prevails as the determinant of trade credit provision. As the degree of ownership decreases, contract enforcement concerns become stronger: smaller firms, as well as firms in countries with weaker enforcement or in more relationship-specific industries provide trade credit.

## Policy research reports (in Korean)

기업집단 내부거래의 한계기업 지원양상 분석과 정책시사점, 2023

기업투자에 대한 조세지원제도의 효과성 연구(연구책임자: 김빛마로, 공동연구자: 홍병진), 2023

지역노동수요충격이 지역경제 및 재정에 끼친 영향(연구책임자: 이환웅, 공동연구자: 고창수), 2023
