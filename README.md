# Google-AI-Course

# Path 3 Advanced: Generative AI for Developers Learning Path

### 05 Create Image Captioning Models

1. What is the name of the dataset the video uses to train the encoder-decoder model?

   COCO dataset
2. What is the goal of the image captioning task? 

   To generate text captions for images
3. What is the purpose of the attention mechanism in an encoder-decoder model?
   To allow the decoder to focus on specific parts of the image when generating text captions.
   
4. What is the purpose of the encoder in an encoder-decoder model?
  
  To extract information from the image.
  
5. What is the name of the model that is used to generate text captions for images?
  
  Encoder-decoder model
  
6. What is the purpose of the decoder in an encoder-decoder model?
  
  To generate output data from the information extracted by the encoder

----------------------------------------------------------------------------------

### 06 Introduction to Vertex AI Studio

#### Q:What is Vertex AI Studio?
A tool that lets you quickly test and customize generative AI models.

#### Q: What does Gemini multimodal do with Vertex AI Studio?
Gemini multimodal processes text, image, and video data, and generates text as output.

#### Q: What is a prompt?
A prompt is the natural language request or instruction to guide a model to generate a desired output.

#### Q: Which of the following is a type of prompt that allows a generative AI model to perform a task with only a few examples?
Few-shot prompt

#### Q: Which of the following is the best way to generate more creative or unexpected content by adjusting the model parameters in Vertex AI Studio?
Setting the temperature to a high value.

----------------------------------------------------------------------------------
### **07. Vector Search and Embeddings**

#### 1. 關於向量搜尋和傳統關鍵字搜尋的比較，下列敘述何者正確？
    3. 向量搜尋可處理語意相似度且擅長回覆不精確的查詢，而傳統關鍵字搜尋擅長回覆精確查詢。
      
#### 2. 將文字資料編碼成向量的程序稱為什麼？
    4. 生成文字嵌入。
       
#### 3. 在向量搜尋中使用點積距離等距離指標，其主要目的為何？
    4. 在語意相似度方面測量不同向量之間的距離。
       
#### 4. 需要克服哪兩大技術挑戰，才能有效地實作向量搜尋？
    1.
       
#### 5. 使用 Vertex AI Vector Search 建構搜尋應用程式的一般程序為何？
    1. 將資料編碼成嵌入、建立索引並搜尋結果。
       
#### 6. 在 RAG (檢索增強生成) 中使用向量搜尋處理 LLM (大型語言模型) 幻覺的主要優點是什麼？
    1. 讓 LLM 存取查核事實所需的即時資訊。
       
#### 7. ScaNN (可擴充的近似最鄰近項目) 使用哪兩大技術提升向量搜尋的成效？
    1. 
 
--------------------------------------------------------------------------------

### **08. Inspect Rich Documents with Gemini Multimodality and Multimodal RAG**

   https://github.com/Techcps/GSP-Short-Trick/blob/main/Inspect%20Rich%20Documents%20with%20Gemini%20Multimodality%20and%20Multimodal%20RAG%20Challenge%20Lab/inspect_rich_documents_w_gemini_multimodality_and_multimodal_rag.ipynb


--------------------------------------------------------------------------------

### **09. Responsible AI for Developers: Fairness & Bias**

### Q1

#### 1. You have been asked to do a presentation to a stakeholder in your organization on the importance of responsible AI. As you are thinking through your key opening statement, what is the most appropriate statement you can make that describes the importance of having responsible AI?
Responsible AI is important for our organization because it reduces overall harm that our products may inflict on underrepresented groups.

#### 2. Which statement accurately describes a Google AI principle?
Be accountable to people.

#### 3. The data scientist team in your company is working to implement an AI model to assist processing credit card applications. During testing, you notice that the model has inconsistent performance among different sub-group of applicants. What responsible AI best practice should the team apply to the model?
Ensure the recommendation data the product is pulling from is fairly representative of the entire dataset.

#### 4. As you think through the development of your AI product, your organization is looking to you to lead and guide the development team around responsible AI best practices. What is a key best practice the team should think through as they develop the AI product?
When possible, the team should hold the capability to access raw data to investigate issues or unintended behaviors.


### Q2

#### 1. A researcher did an anonymous survey with students in a mixed-gender middle school to learn the health and diet patterns of middle school students in the entire country. What type of bias could it introduce?
   Selection bias.

#### 2. You have been asked to do a presentation in your organization on the importance of AI fairness and bias. As you are thinking through your key opening statement, what is the most appropriate statement you can make that explains why AI fairness is difficult?
   Fairness is difficult because there are pre-existing biases, a variety of scenarios, no standard definition of fairness, and incompatibility of fairness metrics.
   
#### 3. As a data scientist, you are tasked with identifying bias in training data in an effective way. Which of the tools below can be used to identify bias in data?
   TensorFlow Data Validation, What-if Tool.


--------------------------------------------------------------------------------

### **10. Responsible AI for Developers: Interpretability & Transparency**

#### 1. As an AI engineering team manager, you're giving a presentation to explain why interpretability and transparency in AI development is important for engineers. Which of the following statements would be best to include in your slides?
   
   Understand model behaviors

#### 2. Your manager is a strong advocate for responsible AI development. During a project review, they emphasize the importance of transparency and documentation around the dataset you're using and the resulting AI model. They want to know what steps you're taking to ensure this. Which of the following tools or techniques are you using to provide a clear understanding of your dataset and model?

   Data card, Model card.
#### 3. You're working on an image classification model for identifying different types of clouds. During testing, you notice some strange results. The model seems to be focusing on irrelevant areas of the images (like background objects) instead of the actual cloud features. To understand why your model is behaving this way, which of the following tools or techniques would be the most helpful?

   XRAI (eXplainable Region-based Artificial Intelligence)


--------------------------------------------------------------------------------

### **11. Responsible AI for Developers: Privacy & Safety**

## Q1:

#### 1. You've applied various de-identification techniques to a customer dataset containing sensitive information before using it to train an AI model. Which of the following concepts should you use to evaluate the suitability of your de-identification techniques?
   1. Reversibility and referential integrity.
      
#### 2. In machine learning, privacy measures often introduce trade-offs with other important factors. Which of the following does NOT represent a typical trade-off?
   1. Privacy and Transparency

#### 3. A customer is working with a large dataset of healthcare records to develop a diagnostic AI model. They want to ensure privacy of sensitive data, by restricting the contribution of specific data on the model during training. Which privacy-focused technique would be best for the customer?
   1. DP-SGD (Differentially Private - Stochastic Gradient Descent)

********************************************************************************

## Q2.

#### 1. Your manager asked you to lead a project to research the key considerations in AI safety and develop a failure mode catalog to assist evaluate safety in Generative AI products. Which of the following should not be included as a failure mode?
   Citation
   
#### 2. You want to embed the concept of safety into a pre-trained LLM by fine-tuning it. You have a dataset of prompts and pairs of possible answers, along with labels created by human safety evaluators indicating their preference for one answer over the other. Which technique is the most suitable for fine-tuning the LLM in this scenario?
   Reinforcement Learning from Human Feedback (RLHF)

#### 3. You're pitching an AI-powered customer support solution to a potential client. Their company handles highly sensitive user information, and they have reservations about potential risks associated with AI systems. To address their concerns and win their trust, which key message about AI safety would be most effective to emphasize?
   "Adherence to AI safety principles helps us build reliable systems that minimize unexpected errors, safeguarding your customer data."

--------------------------------------------------------------------------------


