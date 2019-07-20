+++
title = "CoReRank: Ranking to Detect Users Involved in Blackmarket-based Collusive Retweeting Activities"
date = 2019-02-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Aditya Chetan", "Brihi Joshi", "Hridoy Sankar Dutta", "Tanmoy Chakraborty"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *The Twelfth ACM International Conference on Web Search and Data Mining (WSDM 2019)*, ACM."
publication_short = "In *WSDM 2019*"

# Abstract and optional shortened version.
abstract = """Twitter’s popularity has fostered the emergence of various illegal user activities – one such activity is to artificially bolster visibility of tweets by gaining large number of retweets within a short time span. The natural way to gain visibility is time-consuming. Therefore, users who want their tweets to get quick visibility try to
explore shortcuts – one such shortcut is to approach the blackmarket services, and gain retweets for their own tweets by retweeting other customers’ tweets. Thus the users intrinsically become a part of a collusive ecosystem controlled by these services. 

In this paper, we propose CoReRank, an unsupervised framework to detect collusive users (who are involved in producing 
artificial retweets), and suspicious tweets (which are submitted to the blackmarket services) simultaneously. CoReRank leverages the retweeting (or quoting) patterns of users, and measures two scores – the ‘credibility’ of a user and the ‘merit’ of a tweet. We propose a set of axioms to derive the interdependency between these two scores, and update them in a recursive manner. The formulation is further extended to handle the cold start problem. CoReRank is guaranteed to converge in a finite number of iterations and has linear time complexity. We also propose a semi-supervised version of CoReRank (called CoReRank+) which leverages a partial ground-truth labeling of users and tweets. Extensive experiments are conducted to show the superiority of CoReRank compared to six baselines on a novel dataset we collected and annotated. CoReRank beats the best unsupervised baseline method by 269% (20%) (relative) average precision and 300% (22.22%) (relative) average recall in detecting collusive (genuine) users. CoReRank+ beats the best supervised baseline method by 33.18% AUC. CoReRank also detects suspicious tweets with 0.85 (0.60) average precision (recall). To our knowledge, CoReRank is the first unsupervised method to detect collusive users and suspicious tweets simultaneously with theoretical guarantees."""
abstract_short = ""

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://dl.acm.org/citation.cfm?id=3291010"
url_preprint = ""
url_code = "https://github.com/LCS2-IIITD/CoReRank-WSDM-2019"
url_dataset = "https://github.com/LCS2-IIITD/CoReRank-WSDM-2019/tree/master/data"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1145/3289600.3291010"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
 -->