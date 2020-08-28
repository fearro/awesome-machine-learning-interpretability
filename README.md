# awesome-machine-learning-*interpretability* [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but probably biased and incomplete, list of awesome machine learning interpretability resources.

If you want to contribute to this list (*and please do!*) read over the [contribution guidelines](contributing.md), send a pull request, or contact me [@jpatrickhall](https://twitter.com/jpatrickhall).

**An incomplete, imperfect blueprint for a more human-centered, lower-risk machine learning.** The resources in this repository can be used to do many of these things today. *The resources in this repository should not be considered legal compliance advice.*
![alt-text](https://github.com/h2oai/mli-resources/blob/master/blueprint.png)
</br>Image credit: H2O.ai Machine Learning Interpretability team, https://github.com/h2oai/mli-resources.


## Table of Contents

* [Comprehensive Software Examples and Tutorials](https://github.com/jphall663/awesome-machine-learning-interpretability#comprehensive-software-examples-and-tutorials)
* Explainability- or Fairness-Enhancing Software Packages
  * [Browser](https://github.com/jphall663/awesome-machine-learning-interpretability#browser)
  * [Python](https://github.com/jphall663/awesome-machine-learning-interpretability#python)
  * [R](https://github.com/jphall663/awesome-machine-learning-interpretability#r)
* [Free Books](https://github.com/jphall663/awesome-machine-learning-interpretability#free-books)
* [Government and Regulatory Documents](https://github.com/jphall663/awesome-machine-learning-interpretability#government-and-regulatory-documents)
* [Other Interpretability and Fairness Resources and Lists](https://github.com/jphall663/awesome-machine-learning-interpretability#other-interpretability-and-fairness-resources-and-lists)
* [Review and General Papers](https://github.com/jphall663/awesome-machine-learning-interpretability#review-and-general-papers)
* [Teaching Resources](https://github.com/jphall663/awesome-machine-learning-interpretability#teaching-resources)
* Interpretable ("Whitebox") or Fair Modeling Packages
  * [C/C++](https://github.com/jphall663/awesome-machine-learning-interpretability#cc)
  * [Python](https://github.com/jphall663/awesome-machine-learning-interpretability#python-1)
  * [R](https://github.com/jphall663/awesome-machine-learning-interpretability#r-1)
* [AI Incident Tracker](https://github.com/jphall663/awesome-machine-learning-interpretability/blob/master/README.md#ai-incident-tracker)

## Comprehensive Software Examples and Tutorials

* [COMPAS Analysis Using Aequitas](https://github.com/dssg/aequitas/blob/master/docs/source/examples/compas_demo.ipynb)
* [Explaining Measures of Fairness with SHAP](https://github.com/slundberg/shap/blob/master/notebooks/general/Explaining%20Quantitative%20Measures%20of%20Fairness.ipynb)
* [Getting a Window into your Black Box Model](http://projects.rajivshah.com/inter/ReasonCode_NFL.html)
* [From GLM to GBM Part 1](https://www.h2o.ai/blog/from-glm-to-gbm-part-1/)
* [From GLM to GBM Part 2](https://www.h2o.ai/blog/from-glm-to-gbm-part-2/)
* [IML](https://mybinder.org/v2/gh/christophM/iml/master?filepath=./notebooks/tutorial-intro.ipynb)
* [Interpretable Machine Learning with Python](https://github.com/jphall663/interpretable_machine_learning_with_python)
* [Interpreting Machine Learning Models with the iml Package](http://uc-r.github.io/iml-pkg)
* [Interpretable Machine Learning using Counterfactuals](https://docs.seldon.io/projects/alibi/en/v0.2.0/examples/cf_mnist.html)
* [Machine Learning Explainability by Kaggle Learn](https://www.kaggle.com/learn/machine-learning-explainability)
* [Model Interpretability with DALEX](http://uc-r.github.io/dalex)
* Model Interpretation series by Dipanjan (DJ) Sarkar:
  * [The Importance of Human Interpretable Machine Learning](https://towardsdatascience.com/human-interpretable-machine-learning-part-1-the-need-and-importance-of-model-interpretation-2ed758f5f476)
  * [Model Interpretation Strategies](https://towardsdatascience.com/explainable-artificial-intelligence-part-2-model-interpretation-strategies-75d4afa6b739)
  * [Hands-on Machine Learning Model Interpretation](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
  * [Interpreting Deep Learning Models for Computer Vision](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
* [Partial Dependence Plots in R](https://journal.r-project.org/archive/2017/RJ-2017-016/)
* [Saliency Maps for Deep Learning](https://medium.com/@thelastalias/saliency-maps-for-deep-learning-part-1-vanilla-gradient-1d0665de3284)
* [Visualizing ML Models with LIME](http://uc-r.github.io/lime)
* [Visualizing and debugging deep convolutional networks](https://rohitghosh.github.io/2018/01/05/visualising-debugging-deep-neural-networks/)
* [What does a CNN see?](https://colab.research.google.com/drive/1xM6UZ9OdpGDnHBljZ0RglHV_kBrZ4e-9)

## Explainability- or Fairness-Enhancing Software Packages

### Browser

* [manifold](https://github.com/uber/manifold)
* [TensorBoard Projector](http://projector.tensorflow.org)
* [What-if Tool](https://pair-code.github.io/what-if-tool/index.html#about)

### Python

* [acd](https://github.com/csinva/hierarchical_dnn_interpretations)
* [aequitas](https://github.com/dssg/aequitas)
* [AI Fairness 360](http://aif360.mybluemix.net)
* [AI Explainability 360](https://github.com/IBM/AIX360)
* [ALEPython](https://github.com/blent-ai/ALEPython)
* [allennlp](https://github.com/allenai/allennlp)
* [algofairness](https://github.com/algofairness)
* [Alibi](https://github.com/SeldonIO/alibi)
* [anchor](https://github.com/marcotcr/anchor)
* [BlackBoxAuditing](https://github.com/algofairness/BlackBoxAuditing)
* [casme](https://github.com/kondiz/casme)
* [captum](https://github.com/pytorch/captum)
* [causalml](https://github.com/uber/causalml)
* [contextual-AI](https://github.com/SAP/contextual-ai)
* [ContrastiveExplanation (Foil Trees)](https://github.com/MarcelRobeer/ContrastiveExplanation)
* [DeepExplain](https://github.com/marcoancona/DeepExplain)
* [deeplift](https://github.com/kundajelab/deeplift)
* [deepvis](https://github.com/yosinski/deep-visualization-toolbox)
* [DiCE](https://github.com/microsoft/DiCE)
* [DoWhy](https://github.com/microsoft/dowhy)
* [eli5](https://github.com/TeamHG-Memex/eli5)
* [fairml](https://github.com/adebayoj/fairml)
* [fairness-comparison](https://github.com/algofairness/fairness-comparison)
* [fairness_measures_code](https://github.com/megantosh/fairness_measures_code)
* [foolbox](https://github.com/bethgelab/foolbox)
* [Grad-CAM](https://github.com/topics/grad-cam) (GitHub topic)
* [iNNvestigate neural nets](https://github.com/albermax/innvestigate)
* [Integrated-Gradients](https://github.com/ankurtaly/Integrated-Gradients)
* [interpret_with_rules](https://github.com/clips/interpret_with_rules)
* [Keras-vis](https://github.com/raghakot/keras-vis)
* [keract](https://github.com/philipperemy/keract/)
* [L2X](https://github.com/Jianbo-Lab/L2X)
* [lime](https://github.com/marcotcr/lime)
* [LiFT](https://github.com/linkedin/LiFT)
* [lit](https://github.com/pair-code/lit)
* [lofo-importance](https://github.com/aerdem4/lofo-importance)
* [lrp_toolbox](https://github.com/sebastian-lapuschkin/lrp_toolbox)
* [microsoft/interpret](https://github.com/Microsoft/interpret)
* [MLextend](http://rasbt.github.io/mlxtend/)
* [ml-fairness-gym](https://github.com/google/ml-fairness-gym)
* [OptBinning](https://github.com/guillermo-navas-palencia/optbinning)
* [parity-fairness](https://pypi.org/project/parity-fairness/)
* [PDPbox](https://github.com/SauceCat/PDPbox)
* [pyBreakDown](https://github.com/MI2DataLab/pyBreakDown)
* [PyCEbox](https://github.com/AustinRochford/PyCEbox)
* [pymc3](https://github.com/pymc-devs/pymc3)
* [pytorch-innvestigate](https://github.com/fgxaos/pytorch-innvestigate)
* [rationale](https://github.com/taolei87/rcnn/tree/master/code/rationale)
* [responsibly](https://github.com/ResponsiblyAI/responsibly)
* [robustness](https://github.com/MadryLab/robustness)
* [RISE](https://github.com/eclique/RISE)
* [SALib](https://github.com/SALib/SALib)
* [scikit-fairness](https://github.com/koaning/scikit-fairness)
* [shap](https://github.com/slundberg/shap)
* [Skater](https://github.com/datascienceinc/Skater)
* [tensorfow/cleverhans](https://github.com/tensorflow/cleverhans)
* [tensorflow/lucid](https://github.com/tensorflow/lucid)
* [tensorflow/model-analysis](https://github.com/tensorflow/model-analysis)
* [tensorflow/privacy](https://github.com/tensorflow/privacy)
* [tensorflow/tcav](https://github.com/tensorflow/tcav)
* [tensorfuzz](https://github.com/brain-research/tensorfuzz)
* [TensorWatch](https://github.com/microsoft/tensorwatch)
* [TextFooler](https://github.com/jind11/TextFooler)
* [tf-explain](https://github.com/sicara/tf-explain)
* [Themis](https://github.com/LASER-UMASS/Themis)
* [themis-ml](https://github.com/cosmicBboy/themis-ml)
* [treeinterpreter](https://github.com/andosa/treeinterpreter)
* [woe](https://github.com/boredbird/woe)
* [xai](https://github.com/EthicalML/xai)
* [xdeep](https://github.com/datamllab/xdeep)
* [yellowbrick](https://github.com/DistrictDataLabs/yellowbrick)

### R
* [aif360](https://cran.r-project.org/web/packages/aif360/index.html)
* [ALEPlot](https://cran.r-project.org/web/packages/ALEPlot/index.html)
* [breakDown](https://pbiecek.github.io/breakDown/index.html)
* [DrWhyAI](https://github.com/ModelOriented/DrWhy)
* [DALEX](https://github.com/pbiecek/DALEX)
* [DALEXtra](https://cran.r-project.org/web/packages/DALEXtra/index.html)
* [EloML](https://github.com/ModelOriented/EloML)
* [ExplainPrediction](https://github.com/rmarko/ExplainPrediction)
* [fastshap](https://github.com/bgreenwell/fastshap)
* [fairness](https://cran.r-project.org/web/packages/fairness/index.html)
* [fairmodels](https://github.com/ModelOriented/fairmodels)
* [featureImportance](https://github.com/giuseppec/featureImportance)
* [forestmodel](https://cran.r-project.org/web/packages/forestmodel/index.html)
* [fscaret](https://cran.r-project.org/web/packages/fscaret/)
* [ICEbox](https://cran.r-project.org/web/packages/ICEbox/index.html)
* [iml](https://github.com/christophM/iml)
* [lightgbmExplainer](https://github.com/lantanacamara/lightgbmExplainer)
* [lime](https://github.com/thomasp85/lime)
* [live](https://cran.r-project.org/web/packages/live/index.html)
* [mcr](https://github.com/aaronjfisher/mcr)
* [modelDown](https://cran.r-project.org/web/packages/modelDown/index.html)
* [modelOriented](https://github.com/ModelOriented)
* [modelStudio](https://github.com/ModelOriented/modelStudio)
* [pdp](https://bgreenwell.github.io/pdp/index.html)
* [shapFlex](https://github.com/nredell/shapFlex)
* [shapleyR](https://github.com/redichh/ShapleyR)
* [shapper](https://cran.r-project.org/web/packages/shapper/index.html)
* [smbinning](https://cran.r-project.org/web/packages/smbinning/index.html)
* [vip](https://github.com/koalaverse/vip)
* [xgboostExplainer](https://github.com/AppliedDataSciencePartners/xgboostExplainer)

## Free Books

* [An Introduction to Machine Learning Interpretability](https://www.h2o.ai/wp-content/uploads/2019/08/An-Introduction-to-Machine-Learning-Interpretability-Second-Edition.pdf)
* [Fairness and Machine Learning](http://fairmlbook.org/)
* [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)

## Government and Regulatory Documents

* [12 CFR Part 1002 - Equal Credit Opportunity Act (Regulation B)](https://www.consumerfinance.gov/policy-compliance/rulemaking/regulations/1002/)
* [AI Principles: Recommendations on the Ethical Use of Artificial Intelligence by the Department of Defense](https://media.defense.gov/2019/Oct/31/2002204458/-1/-1/0/DIB_AI_PRINCIPLES_PRIMARY_DOCUMENT.PDF)
* [Algorithmic Accountability Act of 2019](https://www.wyden.senate.gov/imo/media/doc/Algorithmic%20Accountability%20Act%20of%202019%20Bill%20Text.pdf)
* [ALGORITHM CHARTER FOR AOTEAROA NEW ZEALAND](https://data.govt.nz/assets/data-ethics/algorithm/Algorithm-Charter-2020_Final-English-1.pdf)
* [Artificial Intelligence (AI) in the Securities Industry](https://www.finra.org/sites/default/files/2020-06/ai-report-061020.pdf)
* [Article 22 EU GDPR](https://www.privacy-regulation.eu/en/article-22-automated-individual-decision-making-including-profiling-GDPR.htm)
* [Assessment List for Trustworthy Artificial Intelligence (ALTAI) for self-assessment - Shaping Europe’s digital future - European Commission](https://ec.europa.eu/digital-single-market/en/news/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment)
* [Audit of Governance and Protection of Department of Defense Artificial Intelligence Data and Technology](https://media.defense.gov/2020/Jul/01/2002347967/-1/-1/1/DODIG-2020-098.PDF)
* [A Primer on Artificial Intelligence in Securities Markets](https://www.cftc.gov/media/2846/LabCFTC_PrimerArtificialIntelligence102119/download)
* [Booker Wyden Health Care Letters](https://www.scribd.com/document/437954989/Booker-Wyden-Health-Care-Letters#download)
* [California Consumer Privacy Act (CCPA)](https://oag.ca.gov/privacy/ccpa)
* [Consultation on the OPC’s Proposals for ensuring appropriate regulation of artificial intelligence](https://www.priv.gc.ca/en/about-the-opc/what-we-do/consultations/consultation-ai/pos_ai_202001/)
* [Directive on Automated Decision Making](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32592)
* [Facial Recognition and Biometric Technology Moratorium Act of 2020](https://drive.google.com/file/d/1gkTcjFtieMQdsQ01dmDa49B6HY9ZyKr8/view)
* [General principles for the use of Artificial Intelligence in the financial sector](https://www.dnb.nl/binaries/General%20principles%20for%20the%20use%20of%20Artificial%20Intelligence%20in%20the%20financial%20sector_tcm46-385055.pdf)
* [Gouvernance des algorithmes d’intelligence artificielle dans le secteur financier (French)](https://acpr.banque-france.fr/sites/default/files/medias/documents/20200612_gouvernance_evaluation_ia.pdf)
* [Innovation spotlight: Providing adverse action notices when using AI/ML models](https://www.consumerfinance.gov/about-us/blog/innovation-spotlight-providing-adverse-action-notices-when-using-ai-ml-models/)
* [Office of Management and Budget Draft Guidance for Regulation of Artificial Intelligence Applications](https://www.whitehouse.gov/wp-content/uploads/2020/01/Draft-OMB-Memo-on-Regulation-of-AI-1-7-19.pdf)
* [On Artificial Intelligence - A European approach to excellence and trust](https://ec.europa.eu/info/sites/info/files/commission-white-paper-artificial-intelligence-feb2020_en.pdf)
* [Opinion of the German Data Ethics Commission](https://www.bmjv.de/SharedDocs/Downloads/DE/Themen/Fokusthemen/Gutachten_DEK_EN.pdf?__blob=publicationFile&v=2)
* [Principles of Artificial Intelligence Ethics for the Intelligence Community](https://www.intel.gov/principles-of-artificial-intelligence-ethics-for-the-intelligence-community)
* [Questions and Answers to Clarify and Provide a Common Interpretation of the Uniform Guidelines on Employee Selection Procedures](https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines)
* [RE: Use of External Consumer Data and Information Sources in Underwriting for Life Insurance](https://www.dfs.ny.gov/industry_guidance/circular_letters/cl2019_01)
* [Singapore Personal Data Protection Commission (PDPC) Model Artificial Intelligence Governance Framework](https://www.pdpc.gov.sg/Help-and-Resources/2020/01/Model-AI-Governance-Framework)
* [SUPERVISORY GUIDANCE ON MODEL RISK MANAGEMENT](https://www.federalreserve.gov/supervisionreg/srletters/sr1107a1.pdf)
* [U.K. Information Commissioner's Office (ICO) AI Audting Framework (overview series)](https://ico.org.uk/about-the-ico/news-and-events/ai-blog-an-overview-of-the-auditing-framework-for-artificial-intelligence-and-its-core-components/)
* [U.S FDA Proposed Regulatory Framework for Modifications to Artificial Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device (SaMD)](https://www.fda.gov/media/122535/download?mod=article_inline)
* [Using Artificial Intelligence and Algorithms](https://www.ftc.gov/news-events/blogs/business-blog/2020/04/using-artificial-intelligence-algorithms)


## Other Interpretability and Fairness Resources and Lists

* [8 Principles of Responsible ML](https://ethical.institute/principles.html)
* [ACM FAT* 2019 Youtube Playlist](https://www.youtube.com/playlist?list=PLXA0IWa3BpHk7fE8IH6wXNEfAZyr3A5Yb)
* [AI Ethics Guidelines Global Inventory](https://algorithmwatch.org/en/project/ai-ethics-guidelines-global-inventory/)
* [AI Incident Database](http://aiid.partnershiponai.org/)
* [AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models](http://sameersingh.org/files/papers/allennlp-interpret-demo-emnlp19.pdf)
* [Algorithms and prejudice](https://www.thesaturdaypaper.com.au/news/politics/2019/12/07/algorithms-and-prejudice/15756372009195)
* [Awesome interpretable machine learning](https://github.com/lopusz/awesome-interpretable-machine-learning) ;)
* [Awesome machine learning operations](https://github.com/EthicalML/awesome-machine-learning-operations)
* [Awful AI](https://github.com/daviddao/awful-ai)
* [algoaware](https://www.algoaware.eu/)
* [BIML Interactive Machine Learning Risk Framework](https://berryvilleiml.com/interactive/)
* [Beyond Explainability: A Practical Guide to Managing Risk in Machine Learning Models](https://go.immuta.com/beyond-explainability-white-paper)
* [criticalML](https://github.com/rockita/criticalML)
* [Debugging Machine Learning Models (ICLR workshop proceedings)](https://debug-ml-iclr2019.github.io/)
* [Decision Points in AI Governance](https://cltc.berkeley.edu/wp-content/uploads/2020/05/Decision_Points_AI_Governance.pdf)
* [Deep Insights into Explainability and Interpretability of Machine Learning Algorithms and Applications to Risk Management](https://ww2.amstat.org/meetings/jsm/2019/onlineprogram/AbstractDetails.cfm?abstractid=303053)
* [Distill](https://distill.pub)
* [Fairness, Accountability, and Transparency in Machine Learning (FAT/ML) Scholarship](https://www.fatml.org/resources/relevant-scholarship)
* [From Principles to Practice: An interdisciplinary framework to operationalise AI ethics](https://www.ai-ethics-impact.org/resource/blob/1961130/c6db9894ee73aefa489d6249f5ee2b9f/aieig---report---download-hb-data.pdf)
* [How will the GDPR impact machine learning?](https://www.oreilly.com/radar/how-will-the-gdpr-impact-machine-learning/)
* [Machine Learning Ethics References](https://github.com/radames/Machine-Learning-Ethics-References)
* [Machine Learning Interpretability Resources](https://github.com/h2oai/mli-resources)
* [Machine Learning: Considerations for fairly and transparently expanding access to credit](http://info.h2o.ai/rs/644-PKX-778/images/Machine%20Learning%20-%20Considerations%20for%20Fairly%20and%20Transparently%20Expanding%20Access%20to%20Credit.pdf)
* [MIT AI Ethics Reading Group](https://mitaiethics.github.io/)
* [On the Responsibility of Technologists: A Prologue and Primer](https://algo-stats.info/2018/04/15/on-the-responsibility-of-technologists-a-prologue-and-primer/)
* [private-ai-resources](https://github.com/OpenMined/private-ai-resources)
* [Problems with Shapley-value-based explanations as feature importance measures](https://arxiv.org/pdf/2002.11097v1.pdf)
* [Real-World Model Debugging Strategies](https://medium.com/@jphall_22520/strategies-for-model-debugging-aa822f1097ce)
* [ResponsibleAI](https://romanlutz.github.io/ResponsibleAI/)
* [Sample AI Incident Response Checklist](https://bnh-ai.github.io/resources/)
* [Ten Questions on AI Risk](https://fpf.org/wp-content/uploads/2020/06/Ten-Questions-on-AI-Risk-FPF.pdf)
* [Testing and Debugging in Machine Learning](https://developers.google.com/machine-learning/testing-debugging)
* [Troubleshooting Deep Neural Networks](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf)
* [Warning Signs: The Future of Privacy and Security in an Age of Machine Learning](https://fpf.org/wp-content/uploads/2019/09/FPF_WarningSigns_Report.pdf)
* [XAI Resources](https://github.com/pbiecek/xai_resources)
* [You Created A Machine Learning Application Now Make Sure It's Secure](https://www.oreilly.com/ideas/you-created-a-machine-learning-application-now-make-sure-its-secure)

## Review and General Papers

* [50 Years of Test (Un)fairness: Lessons for Machine Learning](https://arxiv.org/pdf/1811.10104.pdf)
* [A Comparative Study of Fairness-Enhancing Interventions in Machine Learning](https://arxiv.org/pdf/1802.04422.pdf)
* [A Survey Of Methods For Explaining Black Box Models](https://arxiv.org/pdf/1802.01933.pdf)
* [A Marauder’s Map of Security and Privacy in Machine Learning](https://arxiv.org/pdf/1811.01134.pdf)
* [Challenges for Transparency](https://arxiv.org/pdf/1708.01870.pdf)
* [Closing the AI Accountability Gap](https://arxiv.org/pdf/2001.00973.pdf)
* [Explaining Explanations: An Overview of Interpretability of Machine Learning](https://arxiv.org/pdf/1806.00069.pdf)
* [Explanation in Human-AI Systems: A Literature Meta-Review, Synopsis of Key Ideas and Publications, and Bibliography for Explainable AI](https://arxiv.org/abs/1902.01876v1)
* [Interpretable Machine Learning: Definitions, Methods, and Applications](https://arxiv.org/abs/1901.04592)
* [Limitations of Interpretable Machine Learning](https://compstat-lmu.github.io/iml_methods_limitations/)
* [Machine Learning Explainability in Finance](https://www.bankofengland.co.uk/-/media/boe/files/working-paper/2019/machine-learning-explainability-in-finance-an-application-to-default-risk-analysis)
* [On the Art and Science of Machine Learning Explanations](https://arxiv.org/pdf/1810.02909.pdf)
* [Please Stop Explaining Black Box Models for High-Stakes Decisions](https://arxiv.org/pdf/1811.10154.pdf)
* [The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490.pdf)
* [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/pdf/1702.08608.pdf)
* [Toward Trustworthy AI Development: Mechanisms for Supporting Verifiable Claims](https://arxiv.org/pdf/2004.07213.pdf)
* [The Security of Machine Learning](https://people.eecs.berkeley.edu/~adj/publications/paper-files/SecML-MLJ2010.pdf)
* [Techniques for Interpretable Machine Learning](https://arxiv.org/pdf/1808.00033.pdf)
* [Trends and Trajectories for Explainable, Accountable and Intelligible Systems: An HCI Research Agenda](https://dl.acm.org/citation.cfm?id=3174156)

## Teaching Resources

* [An Introduction to Data Ethics](https://www.scu.edu/ethics/focus-areas/technology-ethics/resources/an-introduction-to-data-ethics/)
* [Fairness in Machine Learning](https://fairmlclass.github.io/)
* [Fast.ai Data Ethics course](http://ethics.fast.ai/syllabus/#lesson-2-bias--fairness)
* [Human-Center Machine Learning](http://courses.mpi-sws.org/hcml-ws18/)
* [Introduction to Responsible Machine Learning](https://jphall663.github.io/GWU_rml/)
* [Trustworthy Deep Learning](https://berkeley-deep-learning.github.io/cs294-131-s19/)

## Interpretable ("Whitebox") or Fair Modeling Packages

### C/C++

* [Certifiably Optimal RulE ListS](https://github.com/nlarusstone/corels)

### Python

* [Bayesian Case Model](https://users.cs.duke.edu/~cynthia/code/BCM.zip)
* [Bayesian Ors-Of-Ands](https://github.com/wangtongada/BOA)
* [Bayesian Rule List (BRL)](https://users.cs.duke.edu/~cynthia/code/BRL_supplement_code.zip)
* [Explainable Boosting Machine (EBM)/GA2M](https://github.com/Microsoft/interpret)
* [fair-classification](https://github.com/mbilalzafar/fair-classification)
* [Falling Rule List (FRL)](https://users.cs.duke.edu/~cynthia/code/falling_rule_list.zip)
* H2O-3
  * [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlinearestimator)
  * [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogradientboostingestimator)
  * [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlowrankestimator)
* [Optimal Sparse Decision Trees](https://github.com/xiyanghu/OSDT)
* [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/)
* [Multilayer Logical Perceptron (MLLP)](https://github.com/12wang3/mllp)
* [pyGAM](https://github.com/dswah/pyGAM)
* [pySS3](https://github.com/sergioburdisso/pyss3)
* [Risk-SLIM](https://github.com/ustunb/risk-SLIM)
* Scikit-learn
  * [Decision Trees](http://scikit-learn.org/stable/modules/tree.html)
  * [Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html)
  * [Sparse Principal Components](http://scikit-learn.org/stable/modules/decomposition.html#sparse-principal-components-analysis-sparsepca-and-minibatchsparsepca)
* [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys)
* [skope-rules](https://github.com/scikit-learn-contrib/skope-rules)
* [Super-sparse Linear Integer models (SLIMs)](https://github.com/ustunb/slim-python)
* [tensorflow/lattice](https://github.com/tensorflow/lattice)
* [This Looks Like That](https://github.com/cfchen-duke/ProtoPNet)

### R

* [arules](https://cran.r-project.org/web/packages/arules/index.html)
* [Causal SVM](https://github.com/shangtai/githubcausalsvm)
* [elasticnet](https://cran.r-project.org/web/packages/elasticnet/index.html)
* [gam](https://cran.r-project.org/web/packages/gam/index.html)
* [glm2](https://cran.r-project.org/web/packages/glm2/)
* [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html)
* H2O-3
  * [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glm.html)
  * [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.gbm.html)
  * [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glrm.html)
* [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/)
* [quantreg](https://cran.r-project.org/web/packages/quantreg/index.html)
* [rpart](https://cran.r-project.org/web/packages/rpart/index.html)
* [RuleFit](http://statweb.stanford.edu/~jhf/R_RuleFit.html)
* [Scalable Bayesian Rule Lists (SBRL)](https://users.cs.duke.edu/~cynthia/code/sbrl_1.0.tar.gz)

## AI Incident Tracker

* [Mar 1988 - A blot on the profession](https://www.bmj.com/content/296/6623/657)
* [Jul 2015 - Google says sorry for racist auto-tag in photo app](https://www.theguardian.com/technology/2015/jul/01/google-sorry-racist-auto-tag-photo-app)
* [Mar 2016 - Here Are the Microsoft Twitter Bot’s Craziest Racist Rants](https://gizmodo.com/here-are-the-microsoft-twitter-bot-s-craziest-racist-ra-1766820160)
* [Jun 2016 - Google faulted for racial bias in image search results for black teenagers](https://www.washingtonpost.com/news/morning-mix/wp/2016/06/10/google-faulted-for-racial-bias-in-image-search-results-for-black-teenagers/)
* [Oct 2016 - 'Rogue' Algorithm Blamed for Historic Crash of the British Pound](https://gizmodo.com/rogue-algorithm-blamed-for-historic-crash-of-the-britis-1787523587)
* [Oct 2016 - Crime-prediction tool PredPol amplifies racially biased policing, study shows](https://www.mic.com/articles/156286/crime-prediction-tool-pred-pol-only-amplifies-racially-biased-policing-study-shows)
* [May 2017 - Houston Schools Must Face Teacher Evaluation Lawsuit](https://www.courthousenews.com/houston-schools-must-face-teacher-evaluation-lawsuit/)
* [Jun 2017 - When a Computer Program Keeps You in Jail](https://www.nytimes.com/2017/06/13/opinion/how-computers-are-harming-criminal-justice.html)
* [Feb 2018 - Study finds gender and skin-type bias in commercial artificial-intelligence systems](http://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212)
* [Mar 2018 - Self-Driving Uber Car Kills Pedestrian in Arizona, Where Robots Roam](https://www.nytimes.com/2018/03/19/technology/uber-driverless-fatality.html)
* [Mar 2018 - AI-Assisted Fake Porn Is Here and We're All F***ed](https://www.vice.com/en_us/article/bj5and/ai-assisted-fake-porn-is-here-and-were-all-fucked)
* [Jul 2018 - Amazon’s Face Recognition Falsely Matched 28 Members of Congress With Mugshots](https://www.aclu.org/blog/privacy-technology/surveillance-technologies/amazons-face-recognition-falsely-matched-28)
* [Oct 2018 - Amazon scraps 'sexist AI' recruiting tool that showed bias against women](https://www.telegraph.co.uk/technology/2018/10/10/amazon-scraps-sexist-ai-recruiting-tool-showed-bias-against/)
* [Dec 2018 - AI start-up that scanned babysitters halts launch following Post Report](https://www.washingtonpost.com/technology/2018/12/14/ai-start-up-that-scanned-babysitters-halts-launch-following-post-report/)
* [Jan 2019 - Cambridge Analytica’s parent pleads guilty to breaking UK data law](https://techcrunch.com/2019/01/09/cambridge-analyticas-parent-pleads-guilty-to-breaking-uk-data-law/)
* [May 2019 - Investor Sues After an AI’s Automated Trades Cost Him $20 Million](https://futurism.com/investing-lawsuit-ai-trades-cost-millions)
* [May 2019 - 
Millions of people uploaded photos to the Ever app. Then the company used them to develop facial recognition tools.](https://www.nbcnews.com/tech/security/millions-people-uploaded-photos-ever-app-then-company-used-them-n1003371)
* [Jun 2019 - Google and the University of Chicago Are Sued Over Data Sharing](https://www.nytimes.com/2019/06/26/technology/google-university-chicago-data-sharing-lawsuit.html)
* [Sep 2019 - The viral selfie app ImageNet Roulette seemed fun – until it called me a racist slur](https://www.theguardian.com/technology/2019/sep/17/imagenet-roulette-asian-racist-slur-selfie)
* [Sep 2019 - Scammer Successfully Deepfaked CEO's Voice To Fool Underling Into Transferring $243,000](https://gizmodo.com/scammer-successfully-deepfaked-ceos-voice-to-fool-under-1837835066)
* [Oct 2019 - Oh dear... AI models used to flag hate speech online are, er, racist against black people](https://www.theregister.com/2019/10/11/ai_black_people/)
* [Oct 2019 - Dissecting racial bias in an algorithm used to manage the health of populations](https://science.sciencemag.org/content/366/6464/447)
* [Nov 2019 - 
NY regulator investigating Apple Card for possible gender bias](https://www.nbcnews.com/tech/apple/ny-regulator-investigating-apple-card-possible-gender-bias-n1079581)
* [Nov 2019 - Chinese-style facial recognition technology is trialled in Australian schools to register pupils - sparking major privacy concerns](https://www.dailymail.co.uk/news/article-7642411/Australian-schools-trial-facial-recognition-technology-attendance.html)
* [Dec 2019 - Tenants sounded the alarm on facial recognition in their buildings. Lawmakers are listening](https://www.msn.com/en-us/news/politics/tenants-sounded-the-alarm-on-facial-recognition-in-their-buildings-lawmakers-are-listening/ar-BBYnaqB)
* [Dec 2019 - Researchers bypass airport and payment facial recognition systems using masks](https://www.engadget.com/2019-12-16-facial-recognition-fooled-masks.html)
* [Feb 2020 - An Indian politician is using deepfake technology to win new voters](https://www.technologyreview.com/2020/02/19/868173/an-indian-politician-is-using-deepfakes-to-try-and-win-voters/)
* [Feb 2020 - Suckers List: How Allstate’s Secret Auto Insurance Algorithm Squeezes Big Spenders](https://themarkup.org/allstates-algorithm/2020/02/25/car-insurance-suckers-list)
* [Feb 2020 - Tesla Autopilot gets tricked into accelerating from 35 to 85 mph with modified speed limit sign](https://electrek.co/2020/02/19/tesla-autopilot-tricked-accelerate-speed-limit-sign/)
* [Mar 2020 - Netherlands: Court Prohibits Government’s Use of AI Software to Detect Welfare Fraud](https://www.loc.gov/law/foreign-news/article/netherlands-court-prohibits-governments-use-of-ai-software-to-detect-welfare-fraud/)
* [Apr 2020 - Google apologizes after its Vision AI produced racist results](https://algorithmwatch.org/en/story/google-vision-racism/)
* [May 2020 - Researchers find major demographic differences in speech recognition accuracy](https://www.biometricupdate.com/202003/researchers-find-major-demographic-differences-in-speech-recognition-accuracy)
* [May 2020 - Access Denied: Faulty Automated Background Checks Freeze Out Renters](https://themarkup.org/locked-out/2020/05/28/access-denied-faulty-automated-background-checks-freeze-out-renters)
* [May 2020 - A.C.L.U. Accuses Clearview AI of Privacy ‘Nightmare Scenario’](https://www.nytimes.com/2020/05/28/technology/clearview-ai-privacy-lawsuit.html)
* [May 2020 - Walmart Employees Are Out to Show Its Anti-Theft AI Doesn't Work](https://www.wired.com/story/walmart-shoplifting-artificial-intelligence-everseen/)
* [May 2020 - Robodebt removed humans from Human Services, and the Government is facing the consequences](https://www.abc.net.au/news/2020-05-30/robodebt-stuart-robert-scott-morrison/12303322)
* [Jun 2020 - Government’s Use of Algorithm Serves Up False Fraud Charges](https://undark.org/2020/06/01/michigan-unemployment-fraud-algorithm/)
* [Jun 2020 - Microsoft's robot editor confuses mixed-race Little Mix singers](https://www.theguardian.com/technology/2020/jun/09/microsofts-robot-journalist-confused-by-mixed-race-little-mix-singers)
* [Jun 2020 - Tweet: "This algorithm probably made this mistake ..." (President Obama de-blurred into white male)](https://twitter.com/kareem_carr/status/1274462329653137419)
* [Jun 2020 - Detroit Police Chief: Facial Recognition Software Misidentifies 96% of the Time](https://www.vice.com/en_us/article/dyzykz/detroit-police-chief-facial-recognition-software-misidentifies-96-of-the-time)
* [Jun 2020 - Wrongfully Accused by an Algorithm](https://www.nytimes.com/2020/06/24/technology/facial-recognition-arrest.html)
* [Jun 2020 - An Algorithm that "Predicts" Criminality Based on a Face Sparks a Furor](https://www.wired.com/story/algorithm-predicts-criminality-based-face-sparks-furor/)
* [Jun 2020 - PwC facial recognition tool criticised for home working privacy invasion](https://www.personneltoday.com/hr/pwc-facial-recognition-tool-criticised-for-home-working-privacy-invasion/)
* [Jul 2020 - ISIS 'still evading detection on Facebook', report says](https://www.bbc.com/news/technology-53389657)
* [Jul 2020 - Meet the Secret Algorithm That's Keeping Students Out of College](https://www.wired.com/story/algorithm-set-students-grades-altered-futures/)
* [Jul 2020 - Rite Aid deployed facial recognition systems in hundreds of U.S. stores](https://www.reuters.com/investigates/special-report/usa-riteaid-software/)
* [Jul 2020 - Tweet: "Oh, dear ..." (GPT-3 anti-semitism)](https://mobile.twitter.com/jsellenberg/status/1289018551806894081)
* [Jul 2020 - Google Ad Portal Equated “Black Girls” with Porn](https://themarkup.org/google-the-giant/2020/07/23/google-advertising-keywords-black-girls)
* [Jul 2020 - Facial biometrics training dataset leads to BIPA lawsuits against Amazon, Alphabet and Microsoft](https://www.biometricupdate.com/202007/facial-biometrics-training-dataset-leads-to-bipa-lawsuits-against-amazon-alphabet-and-microsoft)
* [Aug 2020 - Police use of facial recognition unlawfully breached privacy rights, says Court of Appeal ruling](https://news.sky.com/story/police-use-of-facial-recognition-unlawfully-breached-privacy-rights-says-court-of-appeal-ruling-12047012)
* [Aug 2020 - There is nothing 'fair' about judging A-levels by algorithm](https://www.telegraph.co.uk/opinion/2020/08/12/nothing-fair-judging-a-levels-algorithm/)
* [Aug 2020 - When algorithms define kids by postcode: UK exam results chaos reveal too much reliance on data analytics](https://www.zdnet.com/article/when-algorithms-define-kids-by-postcode-uk-exam-results-chaos-reveal-too-much-reliance-on-data-analytics/)
* [Aug 2020 - Macy’s hit with privacy lawsuit over alleged use of controversial facial recognition software](https://www.chicagotribune.com/business/ct-biz-macys-lawsuit-clearview-facial-recognition-20200811-mstcyf7wufdjvbanpv6ehjtvni-story.html)
* [Aug 2020 - Google’s Advertising Platform Is Blocking Articles About Racism](https://slate.com/technology/2020/08/googles-ad-exchange-blocking-articles-about-racism.html) 
* [Aug 2020 - Home Office drops 'racist' algorithm from visa decisions](https://www.bbc.com/news/technology-53650758)
* [Aug 2020 - De Blasio Will Reassess NYPD's Use Of Facial Recognition Tech After Protester Arrest](https://gothamist.com/news/de-blasio-will-reassess-nypds-use-facial-recognition-tech-after-protester-arrest)
* [Aug 2020 - Facebook algorithm recommending Holocaust denial and fascist content, report finds](https://www.independent.co.uk/news/uk/home-news/facebook-holocaust-denial-fascist-right-wing-algorithm-report-a9673171.html)
* [Aug 2020 - Report: AI Company Leaks Over 2.5M Medical Records](https://www.pcmag.com/news/report-ai-company-leaks-over-25m-medical-records)
* [Aug 2020 - Watchdog investigates Barclays for spying on staff](https://www.advisen.com/tools/fpnproc/fpns/articles_new_5/P/374532561.html)
* [Aug 2020 - PopID’s face-based payments pose privacy and security risks](https://venturebeat.com/2020/08/27/popids-face-based-payments-pose-privacy-and-security-risks/)
* [Aug 2020 - Tinder charges older people more](https://www.choice.com.au/electronics-and-technology/internet/using-online-services/articles/tinder-plus-costs-more-if-youre-older)
* [Aug 2020 - Uber and Lyft pricing algorithms charge more in non-white areas](https://www.newscientist.com/article/2246202-uber-and-lyft-pricing-algorithms-charge-more-in-non-white-areas/)
