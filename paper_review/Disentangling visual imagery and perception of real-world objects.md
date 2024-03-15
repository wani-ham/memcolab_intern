# Disentangling visual imagery and perception of real-world objects

* Date : 2011
* Keywords : *object recognition, perception, mental imagery*

### Background
* **Seen objects** and **Imagined objects**
  * Similarity 
    * The global pattern of brain activation in both imagery and perception is very similar
    * Research suggesting overlap in representation evoked during imagery and perception
  * Difference
    * Brain-damaged patients indicates that imagery and perception can be dissociated
  * So what differentiates the utilization of the tissue by the two processes (**Perception** and **Imagery**) along the ventral visual pathway?

### Methods
* Pre-scan training : Participants were familiarized with the ten object images and practiced generating vivid mental images

* fMRI Experiment
  * ![](../img/paper-review/disentangling_method.png)

* Localizer design
    * Object-selective regions : LO(lateral occipital), pFs(posterior fusiform)
    * Retinotopic : V1, ES(extrastriate cortex: V3, V4, V5/MT)

### Results
* Response magnitude
  * Perception : strong responses in all ROIs.
  * Imagery : (1) Much smaller average response + Only ES showed significantly greater than zero / (2) Opposite pattern of response in object-selective compared to perception (retinotopic < object-selective)
  * ![](../img/paper-review/imagery_result1.png)

* **Decoding**
* ![](../img/paper-review/imagery_result2.png)
1. **Perceptual decoding**
     * **discrimination index** = (average of Between-image correlations) - (Within-image correlations)
    * EX) Between-image : chair-clock / Within-image : clock-clock
    * Discrimination indices were significantly large in all ROIs, but not equal. 
      * indicates  retinotopic regions evidenced better
perceptual decoding than object-selective regions, and that the posterior was better than the anterior regions for both retinotopic and
object-selective cortex.
    * Multi-class classification ananlysis with SVM : performance in V1 > LO, pFs & performance in ES > LO, pFs
    * Indicates **(1)** Early visual cortex(V1, ES) and Object-selective cortex(LO, pFs) both contains information of seen objects ($\because$ discrimination indices > 0 in all ROIs) / **(2)** Early visual cortex contains more <ins>distinct representation</ins> of percieved object
  
2. **Imagery decoding**
    * The result indicates information for imagery objects is contained outside of V1 area 
    * $\because$ low discrimination indices in V1 + classification performance in SVM for V1

* Differences in perception and imagery
  * ![](../img/paper-review/imagery_result3.png)
  * Indicates the relative roles of retinotopic cortex and object-selective cortex are reversed in perception and imagery
    * $\because$  discrimination during imagery is roughly 40% of discrimination during perception in object-selective regions, it is only 10% of discrimination during perception in retinotopic regions
  




### Discussion