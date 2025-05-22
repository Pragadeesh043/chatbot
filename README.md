# chatbot
# 🛍️ **E-Commerce Chatbot – AI Customer Assistant**  

**E-Commerce Chatbot** is an intelligent AI-powered assistant designed to streamline customer interactions. It helps users **track orders, check product details, and receive personalized support** using **machine learning-based intent classification** and **real-time CSV data integration** via Streamlit.  

---

## ✨ **Features**  

✅ **Natural Language Processing (NLP)** for intent recognition  
✅ **Order tracking** via dynamic CSV data integration  
✅ **Product information retrieval** using partial matching  
✅ **Structured chatbot responses** for seamless interaction  
✅ **Interactive web-based deployment** using Streamlit  
✅ **Custom UI enhancements** with styling and fonts  

---

## 🎯 **Project Objectives**  

- Develop a **functional customer support chatbot** for e-commerce businesses  
- Use **machine learning** for **intent classification and response generation**  
- Make **product and order information accessible** in real-time via CSV  
- Provide a **clean, interactive UI** for an enhanced customer experience  
- Deploy the chatbot on **Streamlit Cloud for accessibility**  

---

## 🧱 **Tech Stack**  

🔹 **Python 3.8+** – Core programming logic  
🔹 **Scikit-learn** – Intent classification using NLP models  
🔹 **Streamlit** – Interactive chatbot UI  
🔹 **Pandas** – Data handling for orders and products  
🔹 **GitHub & Streamlit Cloud** – Deployment and version control  

---

## 🚀 **Getting Started**  

### **1️⃣ Clone the repository**  

```bash
git clone https://github.com/YourUsername/Ecommerce-Chatbot.git
cd Ecommerce-Chatbot
```

### **2️⃣ Install dependencies**  

```bash
pip install -r requirements.txt
```

### **3️⃣ Run the application**  

```bash
streamlit run app.py
```

---

## 🖥️ **User Interface**  

- **Chat interface** with real-time product and order tracking    
- **Clean and structured responses** for better readability  
- **Responsive UI with custom styling**  

---

## 🔎 **Example Use Cases**  

### **Order Tracking Prompt**  

> "Check the status of my order **ORD123**"  

✅ **Response:**  
> **Order ID:** ORD123  
> **Product:** Wireless Mouse  
> **Status:** Shipped  
> **Expected Delivery:** 2025-05-16  

---

### **Product Inquiry Prompt**  

> "Tell me about **Noise Cancelling Headphones**"  

✅ **Response:**  
> **Product:** Noise Cancelling Headphones  
> **Price:** ₹2999  
> **Availability:** Limited Stock  
> **Description:** Over-ear headphones with superior noise cancellation.  

---

## ⚠️ **Limitations**  

- The chatbot **relies on CSV files**; future enhancements may integrate a database  
- NLP model can improve **intent accuracy** with more training data  
- **Real-time stock updates** require API integration instead of static CSV  

---

## 🛡️ **Security & Deployment**  

- Hosted on **GitHub & Streamlit Cloud**    
- **Secure CSV data handling** for product & order tracking  

---

## 📁 **Folder Structure**  

```plaintext
Ecommerce-Chatbot/
├── app.py                 # Main chatbot interface
├── chatbot_model.py       # Core logic & intent classification
├── intents.json           # Stores predefined chatbot responses
├── orders.csv             # Order tracking database
├── products.csv           # Product details database
├── requirements.txt       # Dependencies list
├── README.md              # Documentation
```

## 👤 **Author**  

Developed by **pragadeesh**  
🔗 [GitHub Profile](https://github.com/pragadeesh043)  

---

## 🙌 **Acknowledgements**  

- **Scikit-learn & Pandas** for data processing  
- **Streamlit** for building an intuitive chatbot interface  
- **GitHub & Streamlit Cloud** for deployment  

---
