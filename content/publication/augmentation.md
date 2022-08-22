+++
title = "Strong data augmentation sanitizes poisoning and backdoor attacks without an accuracy tradeoff"

date = "2021-06-06

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["Eitan Borgnia", "Valeriia Cherepanova", "Liam Fowl", "Amin Ghiasi", "Jonas Geiping", "Micah Goldblum", "Tom Goldstein", "Arjun Gupta"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "ICASSP 2021"
#publication_short = "ISBI"

# Abstract and optional shortened version.

abstract = "Data poisoning and backdoor attacks manipulate victim models by maliciously modifying training data. In light of this growing threat, a recent survey of industry professionals revealed heightened fear in the private sector regarding data poisoning. Many previous defenses against poisoning either fail in the face of increasingly strong attacks, or they significantly degrade performance. However, we find that strong data augmentations, such as mixup and CutMix, can significantly diminish the threat of poisoning and backdoor attacks without trading off performance. We further verify the effectiveness of this simple defense against adaptive poisoning methods, and we compare to baselines including the popular differentially private SGD (DP-SGD) defense. In the context of backdoors, CutMix greatly mitigates the attack while simultaneously increasing validation accuracy by 9%."


# Featured image thumbnail (optional)
image_preview = "lowkey.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ""

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/abstract/document/9414862"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#[[url_custom]]
#name = "Journal"
#url = "https://link.springer.com/article/10.1007/s10584-014-1174-4"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
#highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "lowkey.png"
#caption = ""

+++
