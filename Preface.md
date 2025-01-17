# Preface

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Evolutionary-Intelligence.ECAMP-Preface)

As was shown by [Frances H. Arnold](http://fhalab.caltech.edu/), Prof. of California Institute of
Technology, in her Nobel Lecture, "[Responsible for adaptation, optimization, and innovation in
the living world, evolution executes a simple algorithm of diversification and natural selection,
an algorithm that works at all levels of complexity from single protein molecules to whole
ecosystems.](https://www.nobelprize.org/uploads/2018/10/arnold-lecture.pdf)" Some of **fundamental
principles** (e.g., natural selection) of biological evolution originated from [Alfred Russel
Wallace](https://tinyurl.com/yvwmuv9b) and [Charles Robert Darwin](https://tinyurl.com/5ywts76r).
These principles, however, *can be* and *have been* employed to solve many (not all) **complex**
computational (e.g., [evolutionary algorithms](https://tinyurl.com/y57b2r96)), design (e.g.,
[artificial life](https://direct.mit.edu/artl)), modelling, and engineering (e.g., [directed
evolution](http://fhalab.caltech.edu/)) problems, *often* (though *not always*) with practically
promising or satisfactory performance. In this open book, we will focus on **computational
(rather biological) evolution** for modeling, optimization, learning, and design from both the
*historical* and *modern* perspective.

Although initially (especially at the beginning stage) so-called **biological evolution-based**
[inspirations](https://www.nature.com/articles/s42256-020-00278-8) (in the form of
[metaphors](https://tinyurl.com/mtmwez9h)) are an *attractive and interesting* point to many
readers, researchers, and practitioners, undoubtedly its **increasingly solid mathematical
foundations, very flexbile algorithmic frameworks, widely available implementation software,
and various application successes (i.e., practical usefulness)**, which are of our great
interest, play cornerstone roles in the growing maturity of the [Evolutionary
Computation/Computing (EC)](https://tinyurl.com/48r89bv2) field, including but not limited to
**Evolutionary Algorithms** ([EAs]()).

Our modest goal for this open book is to provide modern information regarding to EC and some
(*not all*) advanced EC topics, in order to help *perplexed* novices foster the desirable
ability of judging whether or not it is a [good](https://tinyurl.com/msxvdkfb) research
practice on EC, which we think is very crucial for *perplexed* novices in the [explosion of
metaphor-centred methods](https://publications.aston.ac.uk/id/eprint/44574/1/ALIFE_LLCS.pdf)
and the rise of [Large Language Models (LLMs)](https://chat.openai.com/). Our main focus on
EC **is and should be** **general principles and techniques** of designing and analyzing EC
(that is, *whether, when, why, and how to employ EC*) and also their **real-world
applications**, rather than only their biological metaphors (though some metaphors played an
interesting and important role in their early formation stage). In fact, these two key aspects
(i.e., [theories](https://link.springer.com/book/10.1007/978-3-642-17339-4) and
[practices]()) have been often asked to ourselves and our colleagues. In this sense, we argue
that this open book is one (not necessarily perfect yet worthwhile to explore) answer to these
often-asked questions (*whether, when, why, and how to employ and study EC*).

Although we believe there may be more or less [opportunities](https://tinyurl.com/mpdhne4f)
to extend it (such as [Quality-Diversity](https://tinyurl.com/3c5bzumz)) significantly, most of
its **fundamentally** algorithmic structures have been fixed/unchanged over the past 20 years,
to some extents. For effectiveness and efficiency, ["leveraging (or learning) the statistical
and computational structure of problem"](https://www.nowpublishers.com/article/Details/MAL-070)
no matter *explicitly* or *implicitly* is now one of main research goals when desiging different
EA versions, variants, extensions, and improvements for different kinds of **hard** problems
(such as, [FunSearch](https://www.nature.com/articles/s41586-023-06924-6),
[Persistent ES](https://icml.cc/virtual/2021/poster/10175),
[OpenAI-ES](https://openai.com/index/evolution-strategies/),
[Population-Based Training (PBT)](https://tinyurl.com/428mrb4f),
[Surrogate Models](),
[NES](https://www.jmlr.org/papers/volume15/wierstra14a/wierstra14a.pdf),
[CMA-ES](https://jmlr.org/papers/volume18/14-467/14-467.pdf),
[EDA](https://jmlr.org/papers/volume24/22-0628/22-0628.pdf),
just to name a few).

First, an important-yet-difficult research question to be answered is the underlying assumptions
behind [EAs](https://www.nature.com/articles/nature14544). Since the **black-box** (or more
generally, **complex**) nature of hard (e.g., NP-hard) problems tackled **approximately** by EAs,
it is very difficult, if not impossible, to mathematically quantitize these (typically *implicit*)
assumptions behind different EAs, and also their working principles (e.g., **from first
principles**). In this open book, we will first discuss the hard-to-clarify relationships between
underlying assumptions and black-box applications. Note that in practice, the level of black-boxes
vary on different classes of complex problems.

Up to now, there have been several *wonderful* books devoted to EC, such as [[Eiben&Smith, 2015]](https://link.springer.com/book/10.1007/978-3-662-44874-8), [[De Jong, 2006]](https://ieeexplore.ieee.org/book/6267245), [[Fogel, 2006]](https://ieeexplore.ieee.org/book/5237910)/[[Fogel, 1998]](https://ieeexplore.ieee.org/book/5263042), [[Mitchell, 1998]](https://direct.mit.edu/books/book/4675/An-Introduction-to-Genetic-Algorithms), [[Back, 1996]](https://academic.oup.com/book/40791), [[Koza, 1990]](http://infolab.stanford.edu/pub/cstr/reports/cs/tr/90/1314/CS-TR-90-1314.pdf), to name a few. Furthermore, there have been a number of *well-written* review/survey/perspective papers for EC or one particular class of EAs: e.g., [[Miikkulainen&Forrest, 2021, Nature MI]](https://www.nature.com/articles/s42256-020-00278-8), [[Lehman et al., 2020, ALJ]](https://direct.mit.edu/artl/article/26/2/274/93255/The-Surprising-Creativity-of-Digital-Evolution-A), [[Eiben&Smith, 2015, Nature]](https://www.nature.com/articles/nature14544), [[Schoenauer, 2015]](https://link.springer.com/chapter/10.1007/978-94-017-9014-7_28), [[De Jong&Fogel&Schwefel, 1997]](https://www.taylorfrancis.com/chapters/edit/10.1201/9781482268713-13/history-evolutionary-computation), [[Koza, 1994]](), [[Forrest, 1993, Science]](https://www.science.org/doi/10.1126/science.8346439), just to name a few. Undoubtedly, all of these above works provide multiple *good* starting points to learn EAs or one particular algorithm class for practice and to enter the EC research community.

With the renaissance of [neural networks](https://www.sciencedirect.com/science/article/abs/pii/S0893608014002135) (now also called [deep learning](https://www.nature.com/articles/nature14539)) for AI/ML, the interesting interactions between **learning and evolution** (e.g., [[Hinton&Nowlan, 1987]](https://www.cs.toronto.edu/~hinton/absps/baldwin.pdf), [[Maynard Smith, 1987, Nature]](https://www.cs.toronto.edu/~hinton/absps/maynardsmith.pdf)) are worthwhile to be further investigated. [in its infancy](https://link.springer.com/article/10.1023/A:1008973931182)

Finally, we thank very much for Prof. Shi and Prof. Yao which have provided
our Ph.D. and/or research opportunities to study AI/ML and in particular EC.
We also acknowledge all the authors () and reviewers () from each relatively
independent chapters.

************** *** **************
Written/Edited by Qiqi Duan (@HIT&SUSTech, Shenzhen, China),
Qi Zhao (@SUSTech, Shenzhen, China),
Yijun Yang (@Tencent AI Lab, Shenzhen, China), and
Yuhui Shi (@SUSTech, Shenzhen, China).

From 2023 to 2027.
************** *** **************

## Some Well-Written Books Which Have Inspired this Open Book

* [https://probml.github.io/pml-book/](https://probml.github.io/pml-book/):
  This **very popular** book (**Machine Learning: A Probabilistic Perspective**)
  directly motivated the name of our open-access book.
* [https://aima.cs.berkeley.edu/](https://aima.cs.berkeley.edu/):
  This **very popular** book (**Artificial Intelligence: A Modern Approach**)
  directly motivated the name of our open-access book.
* [Eiben, A.E.]() and [Smith, J.E.](), 2015.
  [Introduction to evolutionary computing](https://link.springer.com/book/10.1007/978-3-662-44874-8).
  Springer.
* [Fogel, D.B.](), 2006.
  [Evolutionary computation: Toward a new philosophy of
  machine intelligence](https://tinyurl.com/yc2b2hau).
  John Wiley & Sons.
  [David B. Fogel: [IEEE Evolutionary Computation Pioneer Award
  2008](https://tinyurl.com/ya8s24d9)]
* [De Jong, K.A.](), 2006.
  [Evolutionary computation: A unified approach]().
  MIT Press.
  [[[GECCO-2017]](https://dl.acm.org/doi/abs/10.1145/3067695.3067715),
  [[GECCO-2015]](https://dl.acm.org/doi/abs/10.1145/2739482.2756576),
  [[GECCO-2009]](https://dl.acm.org/doi/abs/10.1145/1570256.1570404),
  [[GPME-2007]](https://link.springer.com/article/10.1007/s10710-007-9035-9),
  [[ALJ-2007]](https://direct.mit.edu/artl/article-abstract/13/4/423/2573/Evolutionary-Computation-A-Unified-Approach)]
  (This classical book for EC directly motivated the name of
  this open-access book.)
  [Kenneth De Jong: [IEEE Evolutionary Computation Pioneer Award
  2005](https://tinyurl.com/ya8s24d9)]
* [Mitchell, M.](), 1998.
  [An introduction to genetic algorithms]().
  MIT Press.
* [Bäck, T.](), [Fogel, D.B.]() and Michalewicz, Z., 1997.
  [Handbook of evolutionary computation]().
  Oxford University Press.
  [Thomas Bäck: [IEEE Evolutionary Computation Pioneer Award
  2015](https://tinyurl.com/ya8s24d9); David B. Fogel:
  [IEEE Evolutionary Computation Pioneer Award
  2008](https://tinyurl.com/ya8s24d9)]
* [Back, T.](), 1996.
  [Evolutionary algorithms in theory and practice: evolution strategies,
  evolutionary programming, genetic algorithms]().
  Oxford University Press.
  [Thomas Bäck: [IEEE Evolutionary Computation Pioneer Award
  2015](https://tinyurl.com/ya8s24d9)]
* [Schwefel, H.P.](), 1993.
  [Evolution and optimum seeking: The sixth generation]().
  John Wiley & Sons.
  [Hans-Paul Schwefel: [IEEE Frank Rosenblatt Award 2011]() +
  [IEEE Evolutionary Computation Pioneer Award
  2002 (with Ingo Rechenberg)](https://tinyurl.com/ya8s24d9)]
* [Holland, J.H.](), 1992.
  [Adaptation in natural and artificial systems: An introductory analysis
  with applications to biology, control, and artificial intelligence]().
  MIT Press.
  [John H. Holland: [IEEE Evolutionary Computation Pioneer Award
  2003](https://tinyurl.com/ya8s24d9)]
* [Koza, J.R.](https://www.genetic-programming.org/), 1990.
  [Genetic programming: A paradigm for genetically breeding populations of
  computer programs to solve problems](https://tinyurl.com/wxy2n6vy).
  Technical Report, Department of Computer Science, Stanford University.
  [John Koza: [IEEE Evolutionary Computation Pioneer Award
  2024](https://tinyurl.com/ya8s24d9)]
* [Goldberg, D.E.](), 1989.
  [Genetic algorithms in search, optimization and machine learning]().
  Pearson Education.
  [David E. Goldberg: [IEEE Evolutionary Computation Pioneer Award 2010
  (with John Greffenstette)](https://tinyurl.com/ya8s24d9)]

![visitors](https://visitor-badge.laobi.icu/badge?page_id=Evolutionary-Intelligence.ECAMP)
