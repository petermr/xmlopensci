# xmlopensci
XML Tools and resources for Open Science.
A personal selection of tools I find most useful

## scientific background
A distributed group of open scientists are mining the literature for knowledge relevant to global problems. the discussion is concentrated at [openNoteBook](https://github.com/petermr/opennotebook) and the domain-specific ([climate change](https://github.com/petermr/climate) and [plant chemistry for medicine, CEV](https://github.com/petermr/plants)). The original material from [EPMC](http://europepmc.org) is in XML and most of the output of the analysis program [AMI](http://github.com/petermr/ami3) is also in XML.

## XML background and vision
petermr is giving a tutorial/presentation at [XMLSummerSchool 19](https://xmlsummerschool.com/) and using CEV as the example material. I'm assuming that all delegates are familiar with XML basics by this time but won't know about scholarly articles and JATS.

The vision was set out 20 years ago by PMR and Henry Rzepa:
http://www.ch.ic.ac.uk/rzepa/codata/
This outlines the "datument" - a combination of text and data from many sciences that is simple to manage with XML, but does not appeal to a PDf-centered world... Ah well.

## tools fot XML
I currently use Java - first suggested by Jon Bosak in 1997 - and I haven't regretted it. It's a bit verbose by modern standards but it's strongly typed, fail-at-compile

### XOM
[XOM](http://xom.nu) is an excellent tool whuch supports the concept of XML elements == XML Objects . All my code is based on XOM and, where necessary, subclassed Objects.
See [XOM for science](./xom/)

### XPath
This is widey used in AMI and support is contained natively within XOM.

### XSLT vs. DOM
Generally I use `XOM`+`XPath`+`proceduralCode` rather than XSLT. This is partly because I find any stylesheet over a few pages is hard to maintain. However with JATS input I use XSLT to create HTML.
[JATS2HTML stylesheet](https://github.com/ami3/src/main/resources/org/contentmine/norma/pubstyle/nlm/toHtml.xsl)

## applications of XML
We use the following applications of XML. They are all used for both display/reading and as something that can be built up from cruder primitives.

### XHTML
wherever possible text is translated into a basic subset of XHTML, with full `head`, `head/meta/`, `body`, `ul`, `table`, `div`, `p`, `span` as the key elements. Frequenct use of `@class`. 

### SVG
wherever possible graphics and images are translated into a subset of SVG (i.e. without interactivity). Common elements are `svg`, `g`, `rect`, `(poly)line`, `poly(gon)`



## infrastructure
We have 2 approaches to running the software. The first relies on users installing Node and Java8 - this can sometimes be problematic. The second uses Docker but it's very early days. Hopefully fixed by the SummerSchool.
### native
See [TIGR2ESS tutorial](https://github.com/petermr/tigr2ess/blob/master/installation/INSTALLATION.md) for installation instructions

### docker
NOT YET VERIFIED, so don't use.
[Install Docker](https://docs.docker.com/get-started/)








## 
