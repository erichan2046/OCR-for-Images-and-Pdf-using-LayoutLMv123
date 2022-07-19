I am using AI model to detect the textual data from the pdf/images. 
The model used here is LayoutLMv3. I have experimented with v2 and v3, v3 surpasses with the results. 
The dataset used it my own and can't be made public. But the model is finetuned onto such labelled pdf/images. 

/studio-label-ocr folder contains info about the annotation steps involved. 
/tessseractocr.py cotains the info about the annotation code used for annotating in LabelStudio OCR step

**Research papers:** 

[LayoutLMv2](https://paperswithcode.com/paper/layoutlmv2-multi-modal-pre-training-for)

[LayoutLMv2](https://arxiv.org/abs/2204.08387)
