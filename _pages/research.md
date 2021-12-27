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

### [Related-Party Trades in Vertical Integration](https://www.dropbox.com/s/k73xlgquec0tn0h/Hong_Draft.pdf?raw=1) (Job Market Paper) [[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3983336)]

Despite the importance of vertical trade in theories of the firm, an empirical literature using proxy-measures has documented little such trade. I revisit this conclusion using economy-wide firm-level data from South Korea, where related-party trades are directly observable. I show that the true prevalence and volume of intra-party trade is much higher than previous measures indicate. Past proxies, which rely heavily on economy-wide input-output tables, dramatically underestimate related-party trade, capturing only 17.6% of related parties that trade and 32.6% of their sales volume. Using supervised machine-learning, I propose alternatives to relying solely on input-output tables to infer trade.

### Trade Credit as a Contract Enforcement Device: Evidence from Related-Party Trades

A large literature has documented a seeming inefficiency in trade credit practices: smaller firms provide credit to their larger trade partners that have lower external financing costs. This paper presents empirical evidence supporting the hypothesis that larger firms utilize trade credit as a contract enforcement device. By utilizing a novel firm-level data on related-party trades in Korea, I show that in trades where one side of the buyer-supplier relationship completely controls the other, financing cost prevails as the determinant of trade credit provision. As the degree of ownership decreases, contract enforcement concerns become stronger: smaller firms, as well as firms in countries with weaker enforcement or in more relationship-specific industries provide trade credit.
