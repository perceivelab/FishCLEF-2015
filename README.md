# FishCLEF-2015

The dataset for the video-based fish identification task of LifeCLEF 2015 includes a set of 93 videos, manually-annotated with fish locations (as bounding boxes) and species, as well as a set of species sample images for. In total the dataset contains more than 14,000 annotations and 20,000 sample images. The dataset is unbalanced in the number of instances of fish species: for instance it contains 3165 instances of "Dascyllus Reticulates" and only 72 instances of "Zebrasoma Scopas". For each considered fish species, its fishbase.org link is also given. In the fishbase webpage, participants can find more detailed information about fish species including also high quality images. Please check the xls file provided in the training set.

In order to make the identification process independent from tracking, temporal information has not be exploited. This means that the annotators only labelled fish for which the species was clearly identifiable, i.e., if at frame t the species of fish A is not clear, it was not labelled, no matter if the same fish was in the previous frame (t-1). Each video is accompanied by an XML file (UTF-8 encoded) that contains instances of the provided list species. Each XML file is named with the same name of the corresponding labelled video, e.g., “0b21f0579d247c855e05405d3ed805c1#201205251240.xml”. For each video information on the location and the camera recording the video is also given.

Please note that for three fish species there are no occurrences in the test set. Also in some video segments there were no fish. This was done to test the methods' capability to reject false positives.

### Download dataset

Link to dataset files: https://bit.ly/fishclef-2015

### Citation

If you use this dataset, please cite the following works:

> Joly A., Goeau H., Glotin H., Spampinato C., Bonnet P., Vellinga W.-P., Planquè R., Rauber A., Palazzo S., Fisher R., and others}, _LifeCLEF 2015: multimedia life species identification challenges_, International Conference of the Cross-Language Evaluation Forum for European Languages, pp. 462-483, Springer, 2015.
