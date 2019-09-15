---
layout: default
---

Citations: <a href="https://scholar.google.com/citations?hl=en&user=ifD1gh0AAAAJ">Google scholar</a>,
 <a href="https://www.researchgate.net/profile/Rim_El_Ballouli2">Research gate</a>

<h3>Credibility Analysis:</h3>

Data generated on Twitter has become a rich source for various data mining tasks.
Those data analysis tasks that are dependent on the tweet semantics, such as sentiment analysis, emotion mining, and rumor detection among others, suffer considerably if the tweet is not credible, not
real, or spam. In this paper, we perform an extensive analysis on credibility of Arabic content on Twitter. We
also build a classification model (CAT) to
automatically predict the credibility of a
given Arabic tweet. Of particular originality is the inclusion of features extracted directly or indirectly from the author’s profile and timeline. To train and
test CAT, we annotated for credibility a
data set of 9, 000 Arabic tweets that are
topic independent. CAT achieved consistent improvements in predicting the credibility of the tweets when compared to
several baselines and when compared to
the state-of-the-art approach with an improvement of 21% in weighted average Fmeasure. We also conducted experiments
to highlight the importance of the userbased features as opposed to the contentbased features. We conclude our work
with a feature reduction experiment that
highlights the best indicative features of
credibility.

<h3>Self-configuring Architectures:</h3>

Modern systems are pressured to adapt in response to their constantly changing
environment to remain useful. Traditionally, this adaptation has been handled at
down times of the system. there is an increased demand to automate this process
and achieve it whilst the system is running. Self-adaptive systems were introduced
as a realization of continuously adapting systems. Self-adaptive systems
are able to modify at runtime their behavior and/or structure in response to their
perception of the environment, the system itself, and their requirements. The focus
of this work is on realizing self-configuration, a key and essential property of
self-adaptive systems. Self-configuration is the capability of reconfiguring automatically
and dynamically in response to changes. This may include installing,
integrating, removing and composing/decomposing system elements.
This thesis introduces the Dr-BIP framework, an extension of the BIP framework
for modeling self-configuring systems that relies on a model-based and component
& connector approach to prescribe systems. The combination of both of
these approaches exploits the benefits of each.


A Dr-BIP system model is a runtime model which captures the running system
at three different levels of abstraction namely behavior, configuration, and
configuration variants. The system’s configuration is captured by component and
connectors. In a component and connector system, self-configuration can have
three different levels of granularity which includes the ability to add or remove
connectors, add or remove components, and add or remove subsystems. Dr-BIP
supports explicit addition and removal of both components and subsystems, but
implicit addition and removal of connectors. The main advantage of relying on
an implicit addition and removal of connectors is the ability to guarantee by construction
specific configuration topologies.


To capture the three levels of abstraction, we introduce motifs as primary
structures to prescribe a self-configuring Dr-BIP system. A motif defines a set
of components that evolve according to interaction and reconfiguration rules. A
system is composed of multiple motifs that possibly share components and evolve
together. Interaction rules dictate how components composing the system can
interact and reconfiguration rules dictate how the system configuration can evolve
over time. Finally, we show that the proposed framework is both minimal and
expressive by modeling four different self-configuring systems. Last but not least,
we propose a modeling language to codify the framework concepts and provision
an interpreter implementation.