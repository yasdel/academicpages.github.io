---
title: "Towards Evaluating User Profiling Methods Based on Explicit Ratings on Item Features"
collection: publications
permalink: /publication/RMSERecSys19
date: 2019-08-27
venue: 'Joint Workshop on Interfaces and Human Decision Making for Recommender Systems  (IntRS) as part of ACM RecSys 2019'
citation: 'Luca Luciano Costanzo, <b>Yashar Deldjoo</b>, Maurizio Ferrari Dacrema, Markus Schedl, Paolo Cremonesi<i> Joint Workshop on Interfaces and Human Decision Making for Recommender Systems</i>.'

---


[[DOI]](https://dl.acm.org/citation.cfm?id=3109908) [[PDF]](https://re.public.polimi.it/retrieve/handle/11311/1032224/227263/exploring-semantic-gap-final.pdf)  [[bibtex]](https://github.com/yasdel/yasdel.github.io/tree/master/_publications/RecSys17_1.bib)


## Abstract

In order to improve the accuracy of recommendations, many recommender systems nowadays use side information beyond the user rating matrix, such as item content. These systems build user profiles as estimates of users' interest on content (eg, movie genre, director or cast) and then evaluate the performance of the recommender system as a whole eg, by their ability to recommend relevant and novel items to the target user. The user profile modelling stage, which is a key stage in content-driven RS is barely properly evaluated due to the lack of publicly available datasets that contain user preferences on content features of items.
To raise awareness of this fact, we investigate differences between explicit user preferences and implicit user profiles. We create a dataset of explicit preferences towards content features of movies, which we release publicly. We then compare the collected explicit user feature preferences and implicit user profiles built via state-of-the-art user profiling models. Our results show a maximum average pairwise cosine similarity of 58.07\% between the explicit feature preferences and the implicit user profiles modelled by the best investigated profiling method and considering movies' genres only. For actors and directors, this maximum similarity is only 9.13\% and 17.24\%, respectively. This low similarity between explicit and implicit preference models encourages a more in-depth study to investigate and improve this important user profile modelling step, which will eventually translate into better recommendations.
