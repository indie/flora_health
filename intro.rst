Flora Health Science
####################

Detecting nutrient deficiencies in Kingdom *Plantae* with 
augmented inference cyles. 


Demo Project: ML application of a Deep Neural Network 
=====================================================

Required: Compute with training memory and inference cycles 
("phases"). No GPUs needed. 

Model: Long data-ingestion heavy work (ala GPU training
cycles) are not needed; rather, the model iterates on 
"ground truth" examples to produce a result or list of results
naming probable and specific nutrient deficiencies. 


Hypothesis
===========

Due to the way plants photosynthesize, they display common characteristics 
of nutrient deficiencies, regardless of their genus.

A DNN can be trained to "recognize" instances of micronutrient or macronutrient 
deficiences. Higher resolution images may also be useful to speed-up inference; 
that is, when a DNN can be trained with a small number of high-resolution images 
of color variegations,it can be more accurate.

Such an application can be used by farmers or botanists or nurseries 
to remedy possible soil or environmental ailments in their growing zone.  

One such example may be written as:

* **Potassium (K)** deficiencies exhibit in the leaves as paleness 
  of leaf and discoloration or drying / browning around the edge of the 
  leaf. Spotting may occur, but never on the veins of the leaf.


Scientific Data
---------------

MICRO and MACRO nutrient-needs will vary slightly by sub-order PCO.GS


* ** ** 

Copper          yes                  111.0      112.2
Boron           yes                  266.3      266.4
Molybdenum      yes                  304.0      299.1
Sulphur         yes                  314.3      312.9
Zinc            yes                  486.8      479.7
Manganese       yes                  494.7      498.0
Calcium         no                   95.8       95.1
Magnesium       no                   100.8      100.9


