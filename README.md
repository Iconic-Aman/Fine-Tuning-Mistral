# **Mistral Fine-tuning with QLoRA 🚀**  

### **Overview**  
This project fine-tunes the **Mistral model** using **QLoRA** to efficiently adapt large models on limited hardware. We leverage the **Samsum dataset** to improve the model's ability to summarize conversations and engage in chat-based tasks.  

---

### **Dataset**  
The **Samsum dataset** contains human-written conversations with summaries, making it ideal for dialogue generation, text summarization, and chatbot development.  

---

### **Setup**  
**Install:**  
`transformers`, `peft`, `datasets`, `torch`, `accelerate`, `bitsandbytes`

---

### **Process**  
- **QLoRA**: Efficient tuning with low memory usage  
- **Training**: Adjust hyperparameters (batch size, learning rate, epochs)  
- **Inference**: Use the fine-tuned model for chat summaries and responses  

---

### **Next Steps**  
Evaluate performance and explore further improvements—try other datasets or build interactive chatbots.  

---

### **Credits**  
Built using **Mistral**, **Samsum dataset**, and Hugging Face’s **PEFT framework**.  
