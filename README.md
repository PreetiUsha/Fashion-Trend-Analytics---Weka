J48 Classifier Result
=== Run information ===

Scheme: weka.classifiers.trees.J48 -C 0.25 -M 2
Relation:     Attribute DataSet-weka.filters.unsupervised.attribute.Remove-R3-5, 13-14-weka.filters.unsupervised.attribute.Remove-R4-9
Instances:    481
Attributes:   3
              Dress ID
              Style
              Season
Test mode: 10-fold cross-validation

=== Classifier model (full training set) ===

J48 pruned tree
------------------
: Casual (481.0/249.0)

Number of Leaves: 	1

Size of the tree: 	1


Time taken to build model: 0.02 seconds

=== Stratified cross-validation ===
=== Summary ===

Correctly Classified Instances         226               46.9854 %
Incorrectly Classified Instances       255               53.0146 %
Kappa statistic                          0.0046
Mean absolute error                      0.1308
Root mean squared error                  0.2594
Relative absolute error                 99.2879 %
Root relative squared error            101.3834 %
Total Number of Instances              481     

=== Detailed Accuracy by Class ===
   2 222   1   4   0   0   0   2   1   0   0 |   b = Casual
   0  25   0   0   0   0   0   0   0   0   0 |   c = vintage
   1  43   0   0   0   0   0   1   0   0   0 |   d = cute
   0  24   0   0   0   0   0   0   0   0   0 |   e = bohemian
   0   7   0   0   0   0   0   1   0   0   0 |   f = Novelty
   0   2   0   0   0   0   0   0   0   0   0 |   g = Flare
   1  48   0   0   0   0   0   2   0   0   0 |   h = party
   0   7   0   0   0   0   0   0   0   0   0 |   i = sexy
   0  16   1   0   0   0   0   0   0   0   0 |   j = work
   0   1   0   0   0   0   0   0   0   0   0 |   k = OL
