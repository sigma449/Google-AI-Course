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

Q1

#### 1. You have been asked to do a presentation to a stakeholder in your organization on the importance of responsible AI. As you are thinking through your key opening statement, what is the most appropriate statement you can make that describes the importance of having responsible AI?
Responsible AI is important for our organization because it reduces overall harm that our products may inflict on underrepresented groups.

#### 2. Which statement accurately describes a Google AI principle?
Be accountable to people.

#### 3. The data scientist team in your company is working to implement an AI model to assist processing credit card applications. During testing, you notice that the model has inconsistent performance among different sub-group of applicants. What responsible AI best practice should the team apply to the model?
Ensure the recommendation data the product is pulling from is fairly representative of the entire dataset.

#### 4. As you think through the development of your AI product, your organization is looking to you to lead and guide the development team around responsible AI best practices. What is a key best practice the team should think through as they develop the AI product?
When possible, the team should hold the capability to access raw data to investigate issues or unintended behaviors.
