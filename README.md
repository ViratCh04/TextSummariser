# TextSummariser

This program utilised the BART seq2seq transformer model with a bidirectional(BERT-like) encoder and an autoregressive decoder(GPT-2 like). The model works well for both comprehension and text generation after having been fine tuned by the folks at Hugging Face on the CNN dataset. 

## Functioning
Simply put, the program establishes a pipeline to the BART transformer which then analyses the text provided as input and provides a comprehensive summary as output on the streamlit hosted web application. 

Will be adding the references I used for self studying the model before implementing the pipeline soon.