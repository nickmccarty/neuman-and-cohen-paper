# Identifying Social Norms Using GPT3, NLI-based Zero Shot Text Classifcation and Automatic Rule Discovery

This repo is dedicated to replication of the workflow described in Neuman and Cohen's "[AI for identifying social norm
violation](https://www.nature.com/articles/s41598-023-35350-x)" (2023).

## Overview

This research seems to provide evidence "that even complex social situations can be functionally analyzed through modern computational tools." The authors describe their workflow as follows:

* First, using zero-shot classification, we tested our ability to automatically identify social emotions in short
textual data.

* Next, we used GPT-3 for generating synthetic data and identifying violated social norms through human
domain expertise.

* Relying on the outcome of GPT-3, we identifed a high-level taxonomy of norms represented by ten top-level
categories.

* In the third phase, we used a massive dataset of textual data, and measured social emotions and norm
violations. We used features measuring social emotions, norm violation, and two other simple features for
automatic rule discovery.

* Using this approach, we identifed seven simple models (i.e., mathematical functions/rules) that can be used
for classifying cases involving norm violation/conformation.

* In the two major experiments, we used simple models and applied them to classify norm violations in two
other massive datasets. Finally, we test our ability to identify which norm has been violated.

<a href="https://colab.research.google.com/drive/1M-J2uF8CJ4SwgBB35G1RQPK9aQdBCS7G?usp=sharing#offline=true&sandboxMode=true">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
<br>
<p>☝🏼 Initial exploratory work</p>
