# MLonBL2

The data produced in the neutron beam experiments are ginormous and not easily sorted through. Sometimes the detectors get set off by things they shouldn’t and other times they get hit so quickly that the detector doesn’t distinguish them as separate hits. Instead of using the older, and sometimes vague, methods to sort the types of events, I applied some unsupervised machine learning clustering algorithms to the data. These algorithms and libraries can find groups within data, without the need for much intervention.

After the initial investigation, pseudo data was generated else where in the research group. This allows accuracy scores for my old methods to be applied, as well as supervised machine learning methods.

The three folders conatin the different types of data. Inside each is the application of a variety of ML algos including DBSCAN, OPTICS, HDBSCAN, SVMs, DNNs, and CNNs

Read the docx and look at the pptx for a visual and more intuative version of what's going on.
