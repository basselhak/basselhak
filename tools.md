[Home](http://jhasselbalch.org)  
[Research](http://jhasselbalch.org/research)  
[Tools and data](http://jhasselbalch.org/tools)  
[CV](http://jhasselbalch.org/cv)  
[Contact](http://jhasselbalch.org/contact)  

# Tools and data

My approach to social science research is eclectic, and I don't shy away from a particular set of tools or theories if they don't fit my current paradigm. I think it's more important to ask good questions and find compelling case studies than to commit to one particular way of viewing the world.

Having said that, because of the things that interest me and the questions I've asked, I've tended to gravitate towards approaches that take discourse, culture and network relations seriously as organizing concepts in the study of society. I normally start any research project with a deep dive into the empirical field in question through interviews, ethnography, and desk research, and then follow up later with more formal ways of working with and reflecting on the data. [Clifford Geertz](http://hypergeertz.jku.at/GeertzTexts/Natives_Point.htm) calls this balancing the experience-near with the experience-distant modes of inquiry.

# Python for social scientists

I've recently started getting into [Python programming](https://www.python.org/) for social science, and I'm finding it particularly helpful as a way to formalize and organize some of the analytical steps that I previously left undocumented and unreproducible. It's also very empowering to discover how quickly you can learn to make computers work for you in your analytical work. The natural choice for most researchers in political science and sociology is the [R programming language](https://www.r-project.org/). R is unbeaten when it comes to state-of-the-art statistical calculations, but I think Python is the better choice for me for three main reasons: (1) webscraping, (2) natural language processing, and (3) publishing and sharing code online.

## Python basics

For the benefit of others, I've collected some of the packages, guides, and courses here that I've found to be especially helpful in getting to grips with Python and what it can do for my analytical work. For learning the basics, I recommend [DataCamp](https://www.datacamp.com/) and their Data Scientist track. It's important to keep in mind that Python is a general purpose programming language and it can be used for everything from building websites and games to data analysis. DataCamp focuses Python for data science, which is why this is my pick. They also employ a great mix of short vidoes and lots of exercises that really works for me.

In terms of  tools for actual coding and analysis, I think the [Jupyter Notebook IDE](http://jupyter.org/) provides the best combination of ease-of-use, a great environment for exploratory data analysis, [literate programming](https://en.wikipedia.org/wiki/Literate_programming) (which is really wonderful for non-computer-science trained people like myself), and shareability.

## Natural language processing

There are a ton of resources for doing natural language processing (NLP) in Python, especially thanks to the Natural Language Toolkit [(NLTK)](http://www.nltk.org/), which has been in development since 2001. For getting text from the web, the [Requests](http://docs.python-requests.org/en/master/) and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) packages are beyond compare. I'm also looking forward to getting into [Gensim](https://radimrehurek.com/gensim/) and [SpaCy](https://spacy.io/) for topic modeling and other text analysis tasks. NLP in Python has really benefited from what seems like a growing adoption of the language within history and the humanities. There are some really great guides available at the [Programming Historian](https://programminghistorian.org/), as well as Folgert Karsdorp's [interactive course](http://www.karsdorp.io/python-course/) written in Jupyter Notebooks.

## Network analysis

The [NetworkX](https://networkx.github.io/) package is the go-to network analysis package in Python it seems. It's very easy to use, quite powerful, and under rapid development. NetworkX prioritizes graph manipulation and analysis instead of visualization. DataCamp has two good courses on [Network analysis in Python](https://www.datacamp.com/courses/network-analysis-in-python-part-1) by Eric Ma, who is also the maintainer of the [nxviz](http://nxviz.readthedocs.io/en/latest/) package for rational network visualizations, such as arc, hive, and circos plots. For other visualizations, I think NetworkX integrates very well with [matplotlib](https://matplotlib.org/), as well as supporting exports to [Gephi](https://gephi.org/).
