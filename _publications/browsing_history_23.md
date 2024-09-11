---
title: "Your Browsing History May Cost You: A Framework for Discovering Differential Pricing in Non-Transparent Markets"
collection: publications
category: conferences
permalink: /conferences/browsing_history_23
excerpt: 'The prices of flights and hotels in an competitive online marketplace (Kayak) is influenced by browsing history and can be decomposed to 
differnetiation done by the seller as well as non-seller based differentiation.'
date: 2023-06-10
venue: 'ACM Conference on Fairness, Accountability, and Transparency (FAccT)'
slidesurl: 'http://adityakaran.github.io/files/FAccT_2023_Slides.pdf'
paperurl: 'http://academicpages.github.io/\files\Your_Browsing_History_May_Cost_You__1_.pdf'
citation: 'Karan, A., Balepur, N., & Sundaram, H. (2023, June). Your Browsing History May Cost You: A Framework for Discovering Differential Pricing in Non-Transparent Markets. In Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency (pp. 717-735).'
---

In many online markets we “shop alone” — there is no way for
us to know the prices other consumers paid for the same goods.
Could this lack of price transparency lead to diﬀerential pricing?
To answer this question, we present a generalized framework to
audit online markets for diﬀerential pricing using automated agents.
Consensus is a key idea in our work: for a successful black-box
audit, both the experimenter and seller must agree on the agents’
attributes. We audit two competitive online travel markets on kayak.
com (ﬂight and hotel markets) and construct queries representative
of the demand for goods. Crucially, we assume ignorance of the
sellers’ pricing mechanisms while conducting these audits. We
conservatively implement consensus with nine distinct profles
based on behavior, not demographics. We use a structural causal
model for price diﬀerences and estimate model parameters using
Bayesian inference. We can unambiguously show that many sellers
(but not all) demonstrate behavior-driven diﬀerential pricing. In
the ﬂight market, some profles are nearly 90% more likely to see
a worse price than the best performing profle, and nearly 60%
more likely in the hotel market. While the control profle (with
no browsing history) was on average oﬀered the best prices in
the ﬂight market, surprisingly, other profles outperformed the
control in the hotel market. The price diﬀerence between any pair
of profles occurring by chance is $ 0.44 in the ﬂight market and
$ 0.09 for hotels. However, the expected loss of welfare for any
profle when compared to the best profle can be as much as $ 6.00
for ﬂights and $ 3.00 for hotels (i.e., 15× and 33× the price diﬀerence
by chance respectively). This illustrates the need for new market
designs or policies that encourage more transparent market design
to overcome diﬀerential pricing practice