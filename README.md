 🩺 Health Care Chatbot using RASA Framework

A simple yet intelligent **Health Care Chatbot** developed using the **RASA Framework** that provides **home remedies for common health issues**, verified from trusted medical articles. The chatbot uses **Natural Language Processing (NLP)** for understanding user queries and responds with appropriate remedies or guidance using **intent classification**.

---

💡 Features

- 🗣️ Understands natural language queries using RASA's NLP pipeline  
- 💬 Responds with verified **home remedies** for everyday health issues  
- 🔍 Matches user inputs with defined **intents** to generate accurate answers  
- 🧠 Leverages intent classification and custom actions for meaningful conversations  
- 🌐 Frontend built with simple HTML & CSS  
- 🖥️ Command-line based backend control for server operations

---

 🛠️ Tech Stack

- **RASA Framework** – NLP, Intent classification, and Dialogue management  
- **HTML/CSS** – Simple frontend interface  
- **Python** – For backend logic and RASA training data  
- **Command Line** – For installing RASA and running the chatbot server

---
 🚀 How to Run the Project
  
1. **Install RASA**

   bash
   pip install rasa
   

2. **Train the chatbot**

   bash
   rasa train
   

3. **Run the RASA server**

   bash
   rasa run
   

4. **Start RASA action server (if using custom actions)**

   bash
   rasa run actions
   

5. **Interact with the chatbot**

   bash
   rasa shell
   
📁 Project Structure


healthcare-chatbot/
├── actions/
├── data/
│   ├── nlu.yml
│   ├── rules.yml
│   └── stories.yml
├── domain.yml
├── config.yml
├── static/ (HTML & CSS)
└── README.md


---
 📌 Future Enhancements

* Add voice-based input using speech recognition
* Connect to a proper web frontend via REST API
* Store chat history for future analysis
* Add more diverse health intents and multilingual support

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## ✨ Acknowledgements

* Thanks to the RASA community for their excellent open-source NLP platform

---

