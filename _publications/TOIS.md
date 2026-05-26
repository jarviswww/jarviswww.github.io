---
title: "From Trade-off to Synergy: Rethinking the Long-tail Session-based Recommendation Via Dual Constraints of Hybrid Intent"
collection: publications
permalink: '-'
excerpt: 'Authors: Xiao Wang, Ke Qin, Dongyang Zhang, Xiurui Xie, Shuang Liang'
date: 2026-5-6
venue: 'ACM Transactions on Information Systems (CCF-A)'
paperurl: '-'
citation: '-'
---
Session-based recommendation (SBR) predicts the next interaction of anonymous users based on their session data. In practical scenarios, low-exposure tail items constitute the majority of interactions, leading to the biased recommendation whereby a small set of high-exposure head items is preferentially recommended. Existing solutions focus on promoting those tail items but with a sacrifice in recommendation accuracy. We attribute such trade-off to session-irrelevant noise within the tail items, which existing long-tail approaches fail to identify and constrain effectively. To resolve this fundamental conflict, we propose HID (Hybrid Intent-based Dual Constraint Framework), a plug-and-play framework that converts the traditional trade-off between long-tail performance and accuracy into a synergistic relationship by introducing hybrid intent-based dual constraints. HID incorporates two key innovations: (i) Hybrid Intent Learning, which reformulates intent extraction through attribute-aware spectral clustering and discriminates session-irrelevant noise by assigning target and noise intents to each session, and (ii) Intent Constraint Loss, which introduces two constraints—diversity and accuracy—to regulate item and session representation learning. These two objectives are unified into a single training loss through rigorous theoretical derivation. To handle ambiguous user intent in real-world, we also propose a slack version of HID. Extensive experiments show that HID enhances both long-tail performance and accuracy, establishing new state-of-the-art performance in long-tail recommender systems. The implementation code is available at: https://github.com/jarviswww/Code4TradeSynergy.
