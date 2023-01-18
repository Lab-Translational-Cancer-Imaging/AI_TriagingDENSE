# AI Triaging DENSE
Presented here is simplified code used in the Radiology 2022 publication "Deep Learning for Automated Triaging of 4581 Breast MRI Examinations from the DENSE Trial"

Citation: {Verburg, E., van Gils, C. H., van der Velden, B. H. M., Bakker, M. F., Pijnappel, R. M., Veldhuis, W. B., & Gilhuijs, K. G. A. (2022). Deep learning for automated triaging of 4581 breast MRI examinations from the DENSE trial. Radiology, 302(1), 29-36.}

## INPUT
Multiple input files are required to run the code. 
-The model weights
-Input images

The  model weights resulting from training are enclosed. Because eight-fold internal-external valiation was performed, eight weight files are present. In addition, a weight file has been added resulting from training all data from all folds combined.

The input images must be Maximum Intensity projection (MIP) images of a single breast in Sagital, transversal and coronal direction. The MIP images should be prepared as described in the publication. The results reported in the publication are the averages derived from the three MIP directions.

## OUTPUT
The output of the model consists of probabilities of lesion presence and SHAP images showing the regions on which the predictions are based.



#############################################
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
################################################

@author: Erik Verburg
