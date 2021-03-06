# red
Automatic Data Extraction from Result Pages



- Jinsong Guo - University of Oxford
- Valter Crescenzi - Università Roma Tre
- Giovanni Grasso - University of Calabria, Italy  / Meltwater - Wrapidity, UK
- Tim Furche - University of Oxford / Meltwater - Wrapidity, UK
- Georg Gottlob - University of Oxford / TU Wien



We present RED, an automatic approach and prototype system for extracting data records from result pages of websites that follow a widespread publishing pattern: the data about a set of objects (usually returned in response to query submitted by a web form) is presented as one or several paginated pages, each containing a list of result records. Every result record contains the main attributes about one single object, and links to another type of page publishing the details of the object possibly extending the set of attributes.
The intra-site redundancy implied by this publishing patern is leveraged to design an effective fully-unsupervised and domain-independent method for extracting from result pages data that are also published in the corresponding detail pages.
With respect to previous unsupervised methods, our method can achieve a significantly higher accuracy while automatically selecting only relevant attributes, a task which is out the scope of the traditional fully unsupervised approaches. With respect to previous supervised methods, RED can scale to a large number of websites reaching similar accuracy and covering various domains without requiring human intervention for each distinct domain.
