# 💬 AI Chatbot for University Support using Rasa

An intelligent, conversational AI chatbot built with Rasa to handle student queries related to university departments, courses, admission, deadlines, and general support. Designed to reduce manual workload and provide 24/7 assistance.


## 🧠 Key Features

- 📚 Understands natural language student queries
- 🎯 Responds with relevant university info (courses, admission, faculty, etc.)
- 🗃️ Built with **Rasa NLU + Rasa Core**
- 🔄 Supports contextual multi-turn conversations
- 🌐 Deployed locally or over web-based channels


## ⚙️ Technologies Used

- 🧠 [Rasa](https://rasa.com/) (Open source chatbot framework)
- 🐍 Python
- 📝 YAML/NLU training format
- 🔌 Flask (optional for API interface)
- 🌐 Webchat (optional frontend)


## 📁 Project Structure

```

AI-Chatbot-using-Rasa/
├── data/
│   └── nlu.yml              # NLU training data
├── domain.yml               # Domain: intents, entities, responses
├── config.yml               # Rasa pipeline config
├── stories.yml              # Sample conversations (stories)
├── rules.yml                # Rule-based handling
├── actions.py               # Custom Python actions
├── endpoints.yml            # Webhooks for custom actions
├── credentials.yml          # Bot channel credentials
├── README.md

````


## 🚀 How to Run

### 1️⃣ Install Requirements

```bash
pip install rasa
````

### 2️⃣ Train the Model

```bash
rasa train
```

### 3️⃣ Start the Bot

```bash
rasa shell
```

### 4️⃣ Run Actions Server (if using custom actions)

```bash
rasa run actions
```


## 📚 Example Queries

```
User: What courses are available in the AI department?
Bot: We offer courses like Machine Learning, NLP, Deep Learning, and more.

User: How can I apply for admission?
Bot: You can apply through our online portal at admissions.university.edu.
```


## 💡 Future Improvements

* Integrate with website via Rasa Webchat
* Deploy on WhatsApp / Messenger using Twilio or Facebook API
* Add multilingual support
* Connect to live university database or CRM


## 👨‍💻 Author

Muhammad Mubashir
📧 [mubashiryaseen@hotmail.com](mailto:mubashiryaseen@hotmail.com)
🔗 [GitHub](https://github.com/mubashir-yaseen)


## 📄 License

MIT License

```
> Note: This chatbot is designed for demo purposes. Data is static and not connected to a live university database.
