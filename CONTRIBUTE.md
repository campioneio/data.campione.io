Campione.io is what you make of it. A dataset is missing? You have produced a cool set of data for your research and want some visibility this is the right place to index it?

Feel free to add it but please respect the following guidelines.

Acceptance criteria
===

The datasets that you submit must be:

* Parsable
* Usable for machine learning / knowledge purpose (e.g.: aggregated statistics are not a dataset)
* Freely available (without registration)

The last criteria may be removed or updated with time but this let us focus more what we are doing right now.

Structure
===

A Dataset description must be:

* Matching something similar to what can be viewed for the reference sample: [Karlik & Albastaki 2003](https://github.com/campioneio/data.campione.io/blob/master/data/uci.edu/karlik-albastaki-2003-perfume.json).
* Including the right tags. There is currently no finite list of tags / formats, try to maintain as much as you can the currently existing tag list. You can add one tag when none of the others are properly describing the content. For example, if you are adding forest sense data to predict fire and a tag "odor" already exist there is no need to add a "forest odor" tags, but adding a "forest" tag is ok.
* In a subfolder of the data folder, named according to the domain hosting the **main page** of the dataset.
* Named according to a description of the producer of the data, the year of production with, another short element differentiating the dataset from others. e.g.: *karlik-albastaki-2003-perfume.json*

Process
===

When you plan to add a dataset:

* You just create an issue identifying clearly this dataset before starting to edit your json.
* You fork (or update to the current version) of the project.
* You create a branch with the name of the file you plan to add
* You create and polish your json file
* You submit a pull request linked to your issue

Please note: **one pull request per dataset**. This allows us to work at the dataset level, one can be wrong while the other one can be perfect, we would like to be able to integrate your great work as soon as possible!


Any questions? Just ping [@FrantzMiccoli](https://twitter.com/FrantzMiccoli) on Twitter.