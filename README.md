# Citations and References

A citation is a mention of an external source in the body of a paper ('in-text' or 'inline'). This is a very common citation style: [1] This is another: (Kraiser, 2011). However, there are [many citation styles](https://connect.ebsco.com/s/article/Where-can-I-find-formatted-examples-of-different-Citation-styles?language=en_US), and for a published paper, its citation style is usually dictated by the publisher.

A reference is a more full textual description of an external source, designed to allow the reader to obtain the referenced item as a primary source. References are typically collected in a list in a References or Bibliography section toward the end of the paper. Usually, every reference must have been cited somewhere in the paper, and usually every citation has a corresponding reference. However, there are many reference styles, and, for example in [APA Style](https://apastyle.apa.org/), cited personal correspondence that was private and is not accessible to the reader does not need a corresponding reference. The reference style is typically defined as part of the citation style.

## The Citation Graph

Whatever their format, citations and/or references act as edges in a vast knowledge graph, known as The Citation Graph. In this context, work A is said to cite work B, if work A contains a citation or reference to paper B. The citation graph is a directed graph, since the act of work A citing work B does not imply that work B cites work A. i.e. citation is an asymmetric relation between works. 

The citation graph is for the most part acyclic - most papers only cite papers published before them. But some publication processes take time and allow a paper to be updated between being accepted and finally published (the so-called 'camera ready' version), allowing a published paper to cite papers published in parallel, and even for two papers to cite one another. This is rare, and usually not an issue unless you are writing algorithms to do analysis on the citation graph.

The Citation Graph has been called "[one of humankind's most important intellectual achievements](https://boingboing.net/2018/04/14/open-graphs.html)" (by Dario Taraborelli (@readermeter), the Director of Research at the @Wikimedia Foundation).

## Citation Graph Visualization

There are a number of free tools that can visualize portions of the citation graph in different ways:

* https://proto-knowledge.blogspot.com/2015/02/tools-to-visualize-connections-between.html

They are, however, in various states of disrepair, and generally have the feel of experiments. While we share the author's disappointment that there are no better visual tools to explore and discover connections between publications, it is perfectly possible to mine the citation graph without the help of such tools. This undoubtedly explains why there are no tools (at least free tools) that have made it past this stage.

That said, if you feel like working on such a tool, please contact Jon Currey to discuss possible features.

# Research Discovery

## Research Paper Search and Recommendation Sites

There are a number of websites which index, cross-reference and rank research papers. To get the most out of them, create an account and star/like/follow etc. people and papers you have found insightful or helpful. Then the site will recommend related work to you, often with uncanny accuracy! 

Some of the best:

* https://scholar.google.com
* https://www.semanticscholar.org
* http://www.arxiv-sanity.com/
* https://www.researchgate.net/

Even without creating an acccount, Google Scholar has some very useful features. Click on the title of a paper and look for a link of the form "Cited by nnn" where nnn is the number of papers that cite this paper. Clicking on that link will bring up links to each of those papers. You can sort the papers by the date of their publication, or by Google's assessment of their relevance. You can also search just within these publications, to further narrow your search.

## Curated Research Discovery and Discussion

There are many academics, engineers and other interested individuals who publish personal selections of research that are relevant to their specialism or interests. Some of the ones HashiCorp consults most frequently are:

* [The Morning Paper (TMP)](https://blog.acolyer.org)
  * Follow [Adrian on Twitter](https://twitter.com/adriancolyer)
* [Papers We Love (PWL)](https://paperswelove.org/)
  * [Curated collection of papers grouped by research topic](https://github.com/papers-we-love/papers-we-love)
  * [List of local chapters that meet in person](https://github.com/papers-we-love/papers-we-love/blob/master/README.md)
  * [Partial collection of videos](https://www.youtube.com/user/PapersWeLove). 
  * Follow [PWL on Twitter](https://twitter.com/papers_we_love?lang=en) and check the Meetup histories of specific chapters to see if there is a video of a talk on paper you find in the repo that isn't found by the above methods.
* [The Paper Trail](https://www.the-paper-trail.org/)
* [My Biased Coin](http://mybiasedcoin.blogspot.com/)
* [ACM Queue](https://queue.acm.org/)
* [USENIX Conference Bests Papers](https://www.usenix.org/conferences/best-papers)

You can also find lists of papers relevant to a topic by doing a web search for the topic (or combinations of key words releated to the topic) and adding "bibliograpy", "reading list" or "survey" to the end. Many of these bibliographies and surverys were themselves published via peer-reviewed publication, which means multiple reviewers should have reviewed them and decided they are a decent representation of work in that space.

There is even a [website that curates lists of bibliopgraphies](https://liinwww.ira.uka.de/bibliography/index.html) by research topic.

## Associations and Professional Bodies

* ACM
  * [Preferred Employer Program](https://www.acm.org/membership/preferred-employer) [Current members](https://www.acm.org/membership/preferred-employers-list)
* IEEE
  * Local chapters for members
* USENIX
  * [Corporate memberships and sponsorships](https://www.usenix.org/supporters)

All of them sponsor and/or run a number of conferences on different areas of computer science.

## Conference Tracking Sites

There are many sites that use different methodologies to rank academic conferences (often based on some measure of 'impact'), including computer science conferences. For example:

* [Top Computer Science Conferences](http://www.guide2research.com/topconf/)

Other sites focus on tracking the deadlines for submission to upcoming conferences. For example:

* [Computer Science CFPs](http://www.wikicfp.com/cfp/call?conference=computer%20science)

Any of these can be used to discover conferences you were not previously aware of.

## Open Access

Digitization has lowered the material cost of distributing academic papers, just has it has other forms of media. There is an active debate going on about the extent to which organizations can and should be allowed to charge for access to content. Conferences and the review process still have high costs. Should this be subsizided by charging for access to papers, or by other means? HashiCorp is committed to open access. Please educate yourself and make an informed decision regarding paying for access to academic content.

* https://en.wikipedia.org/wiki/The_Cost_of_Knowledge
* https://en.wikipedia.org/wiki/Serials_crisis
* https://www.enago.com/academy/why-researchers-should-use-pre-print-repositories/
* https://www.theguardian.com/science/political-science/2018/jun/29/elsevier-are-corrupting-open-science-in-europe
* https://www.enago.com/academy/move-boycott-elsevier-journals-deal-near-dead/

# Reading and Evaluating Research

## How to Read a Paper

There are many good guides on how to read academic papers. You will develop your own method, but each of them can give you good suggestions to try. Some good places to start:

* https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf
* https://www.eecs.harvard.edu/~michaelm/postscripts/ReadPaper.pdf

Advice on how to write a good paper also gives you insight into how to read (and evaluate) a paper:

* [How (and How Not) to Write a Good Systems Paper](http://msrsvc.org/roylevin/How%20(and%20How%20Not)%20to%20Write%20a%20Good%20Systems%20Paper.htm)

## Known Dangers and Biases (aka Here Be Dragons)

* Mistaking correlation for causality
  * [Chocolate Consumption, Cognitive Function,
and Nobel Laureates](http://www.biostat.jhsph.edu/courses/bio621/misc/Chocolate%20consumption%20cognitive%20function%20and%20nobel%20laurates%20(NEJM).pdf)
  * [Simpson's Paradox](https://en.wikipedia.org/wiki/Simpson's_paradox)
  * [The Book of Why](http://bayes.cs.ucla.edu/WHY/) by Judea Pearl, who won the Turing Award for his work on Causality.
    * [A good summary of the key points](https://medium.com/datadriveninvestor/goodbye-correlation-say-hello-to-the-era-of-causal-inference-f238065c156b) 
    * [Another good summary](https://bigthink.com/errors-we-live-by/judea-pearls-the-book-of-why-brings-news-of-a-new-science-of-causes)
* Fixating on relative improvements
  * [Scalability! But at what COST?](https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf) [TMP](https://blog.acolyer.org/2015/06/05/scalability-but-at-what-cost/)
* Lack of reproducibility
  * This issue is wide-spread in science. Luckily many individuals and professional bodies are committed to addressing it. DevOps principles and tools, such as immutabiliy through versioning, can and should be part of the solution :-)
  * [A paper framing the problem in Computer Science](https://vaibhavbajpai.com/documents/papers/proceedings/reproducibility-sigcomm-workshop-2017.pdf)
  * [ACM SigArch's Reproducibility Manifesto](https://www.sigarch.org/a-checklist-manifesto-for-empirical-evaluation-a-preemptive-strike-against-a-replication-crisis-in-computer-science/)
  * [ACM SigPlan's Empirical Evaluation Guidelines](https://www.sigplan.org/Resources/EmpiricalEvaluation/)
  * [Cross-Conference Artifcat Evaluation](https://www.artifact-eval.org/)

## Places to Discuss Research

In Real Life
* [Papers We Love](https://paperswelove.org/)
  * [List of local chapters that meet in person](https://github.com/papers-we-love/papers-we-love/blob/master/README.md)
  * They have a conference too. [PWLConf](https://pwlconf.org/)
* [The Recurse Center (NYC)](https://www.recurse.com/)
  * Primarily a location for educational programming retreats, they do periodicalyy host talks and other events. Check them out on Twitter [@recursecenter](https://twitter.com/recursecenter) and/or sign up for email notification.

On-Line
* [Dist Syst Slack](https://www.the-paper-trail.org/page/dist-sys-slack/)

# Keeping Track of It All

## Techniques

* [Bill Gates on how to remember what you read](https://www.cnbc.com/2019/03/21/how-bill-gates-remembers-what-he-reads.html)

## Tools

Tools are very personal, and actually not the key issue. However, some tools offer some nice features.

* Pen and paper
  * The act of writing and/or drawing is widely reported to improve information retention.
  * Never has an outage (unless you spill your drink on it!)
* Google Docs
  * Collaborative editing
  * Search within your Google Drive account
* Evernote
  * Web clippers from Chrome and Firefox. Will clip PDFs as well as web pages.
  * Premium vertsion OCRs all images (including whole pages in scanned PDFs)
  * Indexes everything. Shows top 3 related items from your personal corpus each time you clip something.
* Papers app
* https://orgmode.org/
* Jupyter Notebooks (formerly IPython Notebooks)
  * No longer restricted to Python, these allow you to embed experiments with notes. An increasing number of cloud providers offer them for free. Or you can host your own.
  * [JupyterHub](https://tljh.jupyter.org/en/latest/) For setting up your own installation in a public cloud or elsewhere.
  * [Azure Notebooks](https://notebooks.azure.com/)
  * [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)

# HashiCorp's Experience Applying Research to Production

* [Armon Dadgar at PWL SF on Vivaldi: Decentralized Network Coordinate System](https://youtu.be/AszPoJjWK9Q?)
* [Preventing Security Incidents By Automating Policy Optimization](https://youtu.be/C7AHGPxkMh0)
* [Using Randomized Communication for Robust, Scalable Systems](https://www.infoq.com/presentations/randomized-communication-hashicorp-consul/)
* [From the first photocopy to modern failure detection in distributed systems](https://youtu.be/4moHicXPXfA)

# Backlog

A [backlog](https://en.wikipedia.org/wiki/Scrum_(software_development)#Product_backlog) is a great way to decompose a large, daunting project into small, achievable tasks. This technique can be applied to the discovery and evaluation of academic research. We will use one for this resource too.

The current backlog of resources to evaluate and potentiall integrate into this document:

* https://arxiv.org/pdf/1310.8224.pdf
* https://github.com/anniecherk/sweetpea
* https://twitter.com/emeryberger
* https://arstechnica.com/science/2019/07/study-playing-minecraft-could-boost-your-creativity-with-some-caveats/
* http://issi-society.org/media/1325/reproducibility_schneider.pdf
* https://www.frontiersin.org/articles/10.3389/fninf.2018.00020/full
* https://www.nature.com/collections/prbfkwmwvz
* https://www.usenix.org/conferences/best-papers
* https://en.m.wikipedia.org/wiki/Benchmark_(computing)

