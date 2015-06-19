# Semantic Tagging #

<a href='http://www.youtube.com/watch?feature=player_embedded&v=O50GXw11748' target='_blank'><img src='http://img.youtube.com/vi/O50GXw11748/0.jpg' width='425' height=344 /></a>

"Semantic tagging" is a term that describes many of these new (and some not-so-new) findability approaches. Semantic tagging is by no means an accepted concept with an agreed upon definition. Other than the obvious "tagging for meaning," semantic tagging means different things to people coming from different parts of the information management field. It may be used interchangeably with "semantic indexing" in contexts where "indexing" is used for "tagging." Nevertheless, in the quest for better methods of findability, the term semantic tagging is starting to appear in descriptions of information services and products, blogs, online articles, and presentations.

Semantic tagging (or annotation) is now one of the promising methodologies to define semantic structures on the content. Semantic tagging is the annotation of each content word with a semantic category.  A simple way to categorize
semantic tagging systems is as follows:

  * Machine-learning methods such as Amilcare that require an annotated training corpus;
  * Rules-based systems – that rely on manually-created rules;
  * Pattern-based systems – that require an initial set of seeds in order to discover patterns.

Armadillo uses a pattern-based approach to annotation, based on the Amilcare information extraction system. It is especially suitable for highly structured Web pages. The tool starts from a seed pattern and does not require human input initially - although the patterns for entity recognition have to be added manually.

The knowledge and information management (KIM) platform consists of an ontology and knowledge base as well as an indexing and retrieval server. RDF data is stored in an RDF repository, whilst search is performed using LUCENE. KIM is based on an underlying ontology (KIMO or PROTON) that holds the knowledge required to semantically annotate documents, and on GATE to perform information extraction.

Magpie is a suite of tools that supports the fully automatic annotation of Web pages, by mapping entities found in its internal knowledge base against those identified on Web pages. The quality of the results depends on the background ontology, which has to be manually modeled and populated.

MnM is another tool that supports semi-automatic annotation based on the Amilcare system. It uses machine learning techniques and requires a training data set. The classical usage scenario MnM was designed for is the following: while browsing the Web, the user manually annotates selected Web pages in theMnM Web browser. While doing so, the system learns annotation rules, which are then tested against user feedback. The better the system does, the less user input is required.

The PANKOW algorithm is a pattern-based approach to semantic annotation that makes use of the redundant nature of information on the Web. Based on an ontology, the system constructs patterns and combines entities into hypotheses that are validated manually. S-Cream is another approach to semi-automatic annotation that combines two tools: Ont-O-Mat, a manual annotation editor implementing the CREAM framework, and the Amilcare system. S-Cream can be trained for different domains provided the appropriate training data and proposes a set of heuristics for post-processing and mapping of information extraction results to an ontology. S-CREAM 12 uses the Amilcare machine-learning system together with a training corpus of a manually annotated set of documents, to automatically suggest appropriate tags for new documents.

Con Annotator uses Support Vector Machines (SVM) and Natural Language processing (NLP) approaches to facilitate the automated generation of annotations with the support of the domain ontology.

The Sem Tag system is based on the TAP ontology (which is very similar to the KIM ontology). The system firstly annotates all occurrences of instances of the ontology. Secondly, it disambiguates the elements and assigns the correct ontological classes by analysing context.

More recently, the OntoNEO system has been developed by Choi and Park to automatically semantically annotate named entities in texts. OntoNEO claims to have 18% better performance than the Sem Tag algorithm – by using a Hidden Markov Model (HMM) to represent the probabilistic model
of named entities from a corpus of documents.

The SCORE system for management of semantic metadata (and data extraction) also contains a component for resolving ambiguities. SCORE uses associations from a knowledgebase to determine the best match from candidate entities but detailed implementation details are not available.

In ESpotter, named entities are recognized using a lexicon and/or patterns. Ambiguities are resolved by using the URI of the webpage to determine the most likely domain of the term.

# Semantic Searching #

<a href='http://www.youtube.com/watch?feature=player_embedded&v=-R87nJi9YyQ' target='_blank'><img src='http://img.youtube.com/vi/-R87nJi9YyQ/0.jpg' width='425' height=344 /></a>

Semantic search seeks to improve search accuracy by understanding searcher intent and the contextual meaning of terms as they appear in the searchable dataspace, whether on the Web or within a closed system, to generate more relevant results. Author Seth Grimes lists "11 approaches that join semantics to search", and Hildebrand et al. provide an overview that lists semantic search systems and identifies other uses of semantics in the search process. Semantic search systems consider various points including context of search, location, intent, variation of words, synonyms, generalized and specialized queries, concept matching and natural language queries to provide relevant search results. Major web search engines like Google and Bing incorporate some elements of semantic search.

Guha et al. distinguish two major forms of search: navigational and research. In navigational search, the user is using the search engine as a navigation tool to navigate to a particular intended document. Semantic search is not applicable to navigational searches. In research search, the user provides the search engine with a phrase which is intended to denote an object about which the user is trying to gather/research information. There is no particular document which the user knows about and is trying to get to. Rather, the user is trying to locate a number of documents which together will provide the desired information. Semantic search lends itself well with this approach that is closely related with exploratory search.

Rather than using ranking algorithms such as Google's Page Rank to predict relevancy, semantic search uses semantics, or the science of meaning in language, to produce highly relevant search results. In most cases, the goal is to deliver the information queried by a user rather than have a user sort through a list of loosely related keyword results. However, Google itself has subsequently also announced its own Semantic Search project.

Other authors primarily regard semantic search as a set of techniques for retrieving knowledge from richly structured data sources like ontologies as found on the Semantic Web. Such technologies enable the formal articulation of domain knowledge at a high level of expressiveness and could enable the user to specify his intent in more detail at query time.

# References #

  * http://www.econtentmag.com/Articles/Editorial/Feature/How-Semantic-Tagging-Increases-Findabillity-50700.htm
  * http://www.itee.uq.edu.au/eresearch/projects/ands/W4SemanticTagging-report-2011-02.pdf
  * http://en.wikipedia.org/wiki/Semantic_search