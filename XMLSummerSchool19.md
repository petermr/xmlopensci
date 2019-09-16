# XMLSummerSchool Project

This is a *voluntary* project for delegates at the [XMLSummer School at Oxford 2019](https://xmlsummerschool.com). PeterMR is unable 
to attend (broken leg) and (apart from a virtual lecture on Wed 2019-09-18) will offer some self-paced XML relating to modern science. 
It shows how XML can be easily deployed within minutes and search world-leading science. 

## The project

### plants and medicines
We are going to search the modern scientific literature (over 5-20 million articles) for **plants** producing **chemicals** with  **medicinal properties** . (So many drugs come from plants - 
quinine, taxol, artemisin, aspirin.). We've made XML dictionaries of terms for all these concepts and produced a robust commandline tool (AMI) to extract 
this knowledge. A major new development is the use of Wikidata to add linked knowledge

### Climate change
There are tens of thousands of articles on climate change and we'll search them in the same way. 


## How the project works

Anyone can install and run AMI in a few minutes and we invite delegates to have a go. This is *voluntary* but hopefully fun. AMI reads and emits
XML and shows how procedural code and XSLT can both be used to filter and aggregate information. The JATS DTD (was NLM) is probably the most widely
used XML flavour for science and worth investigating in its own right.

All instructions will gradually appear on this repo. If you are unclear, just [raise an Issue](RaisingIssues.md). 
You will first install `getpapers` and download
some papers;
and then install `AMI` and `ami-search` the papers with a selection of dictionaries. When you are confident, you can then make your own dictionaries from simple
word lists.

### installing software
We hope that all software can be distriuted as Docker images and then simply run on commandline. However there is also a Node/Java-absed approach described undr Tigr2ess (more later).


## people involved
Many thanks to volunteers (alphabetical order)

### Emanuel Faria ("Manny") (Brasilia)
Manny develops skin medicines (antibacterials) from plant oils and is helping run the CEV project

### Peter Flynn (UCC, IE)
Peter is organizer of XMLSS and has supported PeterMR in running this session

### Graham Klyne (Oxford)
Graham will be at XMLSS19 and will act as PeterMR's "avatar", making sure that the software and demos work on 2019-09-18 Wed.

### Ambarish Kumar (New Delhi)
Ambarish helped create a tutorial/workshop in 2019-02 and is continuing to support the creation on dictionaries and implementation.

### Tiago Lubiana (Univ Sao Paulo)
Tiago coordinated the eLife Sprint and added many terms to Wikidata

### Simon Worthington (TiB, Hannover)
Simon runs Open Science in TiB (the German Technical Library) and has made climate a special feature.


### eLife Sprint
A group of 6 delegates at eLife Sprint , Cambridge, 2019-09-04 who prototyped the creation of dictionaries from text.

### XMLSummer School
Thanks to all running the event, espcially Lauren Wood and John Chelsom.






