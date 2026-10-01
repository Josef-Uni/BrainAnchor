# BrainAnchor

Per-cell localization of spatial transcriptomics data in the Allen Mouse Brain Common
Coordinate Framework (CCFv3).

BrainAnchor predicts the CCFv3 coordinate of every cell in a mouse brain section from
its local neighborhood. Cells are first projected into a frozen molecular reference, so
data from new gene panels and platforms can be mapped without retraining. A point
transformer then reads the arrangement of cells around each target cell and regresses
its coordinate. Because each prediction uses only a local neighborhood, the method needs
no reference section, no cutting plane and no intact tissue.

## Status

A manuscript describing the method is in preparation. The preprint link and the code
will be added to this repository on publication of the preprint.

## Contact

Josef Salg, Institute for Stroke and Dementia Research (ISD), LMU University Hospital
Munich, group of Dr. Hannah Spitzer.
Josef.Salg@med.uni-muenchen.de
