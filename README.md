# AI Triaging DENSE
The code presented here is a simplified piece of code used for traiging of screening breast MRI in women with extremly dense breast
as published in Radiology 2021 "Deep Learning for Automated Triaging of 4581 Breast MRI Examinations from the DENSE Trial"

Citation: {Verburg, E., van Gils, C. H., van der Velden, B. H., Bakker, M. F., Pijnappel, R. M., Veldhuis, W. B., & Gilhuijs, K. G. (2022). Deep learning for automated triaging of 4581 breast MRI examinations from the DENSE trial. Radiology, 302(1), 29-36.}

#INPUT
Multiple input files are required to run the code. 
-The model weights
-Input images

The  model weights resulted form the train data which was used in for publication is enclosed. Because 8 fold internal external valiation
was completed 8 weightfiles are present. In addition to that also a weight file is added were all data is used to train the model.

Enclosed are also three example images which can be traiged by the model. The images are Maximal intensity projection (MIP) of one breast in Sagital
transversal and coronal direction. The MIP images are prepared as described in the publication. In the outcomes in the publication was the average outcome over the three MIP directions.

#OUTPUT
Output of the model are probabilities for lesion presence and SHAP images showing the areas on which the prediction in based.



#############################################
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
################################################

@author: Erik Verburg