# The Smartest AI Nutrition Assistant 🤖🍏

## Overview

**The Smartest AI Nutrition Assistant** is a cutting-edge, AI-powered nutrition assistant designed to offer **personalized nutrition advice**, **meal planning**, and **healthy food recommendations**. By leveraging advanced **Natural Language Processing (NLP)** and AI models, this assistant provides **tailored guidance** based on individual goals, health conditions, and preferences. Built using **IBM Watsonx.ai**, this tool aims to revolutionize the way people access **nutrition insights**, making it accessible to everyone—whether you’re looking to **lose weight**, **build muscle**, or **maintain health**.

---

## 🧩 Problem Statement

Many people face difficulties when trying to **eat healthily**, especially with the overload of **generic advice** provided by mainstream apps. There’s a growing need for **personalized nutrition**, considering factors like:

- **Health conditions** (e.g., diabetes, heart disease)
- **Fitness goals** (e.g., weight loss, muscle building)
- **Cultural food preferences** and **dietary restrictions**
- **Allergies** and **food sensitivities**

Existing nutrition apps often fail to offer tailored solutions. Many also lack real-time adaptability, which leads to advice that’s either outdated or irrelevant.

---

## 💡 Proposed Solution

**The Smartest AI Nutrition Assistant** leverages **IBM Watsonx.ai** to offer **personalized, adaptable nutrition advice** in real-time. By analyzing **user input**, including health conditions, fitness goals, preferences, and allergies, this AI model generates **meal plans**, **healthy food swaps**, and provides **contextual explanations** on why certain foods are recommended. 

Key features include:

- **Real-time adaptability** to adjust recommendations based on continuous feedback.
- **Personalized meal planning** that accounts for health goals and dietary restrictions.
- **Multimodal support**, including text, voice, and food image recognition.

The assistant is designed to be used by anyone looking to improve their eating habits or manage specific health conditions.

---

## 🧠 Technologies Used

- **IBM Watsonx.ai Studio**: For building, training, and deploying the AI assistant.
- **IBM Granite Foundation Model (LLM)**: Leveraging large language models to understand and generate nutrition-related recommendations.
- **Vector Index for Retrieval-Augmented Generation (RAG)**: To fetch relevant dietary data and recommendations from uploaded food and nutrition PDFs.
- **PDF Document Retrieval**: Nutritional guidelines from trusted sources such as the **USDA**, **WHO**, and **other health organizations**.
- **Natural Language Processing (NLP)**: For understanding user inputs and generating personalized responses.
- **IBM Cloud Object Storage**: For storing and managing food databases and user preferences.

---

## ☁️ IBM Cloud Services Used

- **IBM Watsonx.ai Studio**: For training the AI model and deployment.
- **IBM Granite Model**: A foundation model used for understanding nutrition queries.
- **Watsonx Vector Index**: For creating a high-performance vector index to retrieve the most relevant nutritional data.
- **IBM Cloud Lite Account**: To manage deployment and resources.
- **IBM Cloud IAM**: For secure user access management.
- **IBM Cloud Object Storage**: For storing food data, user details, and health-related documents.

---

## 👥 Target Users

- **General Public**: Seeking personalized meal plans and nutrition advice.
- **Fitness Enthusiasts**: Individuals looking for tailored dietary recommendations.
- **People with Health Conditions**: Users needing specific dietary advice for managing conditions like diabetes, hypertension, etc.
- **Nutritionists & Dieticians**: Professionals who wish to scale their consultations with AI-powered tools.
- **Students & Young Professionals**: Individuals who want quick, accessible nutrition advice.
- **Organizations/NGOs**: Groups focusing on improving community health with nutritional education.

---

## 🌟 Key Features

- **Personalized Meal Plans**: The AI generates meal suggestions based on the user’s health goals, preferences, and allergies.
- **Healthy Food Swaps**: Recommend healthier alternatives to common foods, making it easier for users to stick to their goals.
- **Nutritional Explanations**: When recommending a food or meal, the AI provides **reasons why** it's beneficial for the user.
- **Real-Time Adaptability**: The assistant evolves its recommendations based on feedback and ongoing health data from the user.
- **Multimodal Input**: Supports **text**, **voice**, and **food image recognition** (for food labeling or image uploads).
- **Scalable & Accessible**: A solution that scales from individual users to organizations and dieticians looking for an easy-to-use platform.

---

## 🚀 How It Works

1. **User Input**: Users provide information through a text query (e.g., "What’s a good meal for weight loss?") or upload images (e.g., food photos or grocery labels).
2. **Processing**: The input is processed by **IBM Granite LLM** to interpret the context, health goals, and preferences.
3. **Data Retrieval**: The **Vector Index** retrieves the most relevant nutritional data from uploaded documents (e.g., USDA guidelines).
4. **Response Generation**: The AI agent generates a personalized response, such as a **meal plan**, **food swap suggestion**, or a **nutritional explanation**.

---

## 🖼️ Screenshots

### 🔹 **Setting Up the AI Agent**  
![Setup AI Agent]
<img width="1365" height="643" alt="Setup" src="https://github.com/user-attachments/assets/6e67a022-2d8f-46f5-8440-36a3abca76a9" />


### 🔹 **Agent Instructions Configuration**  
![Agent Instructions]
<img width="1364" height="643" alt="instructions" src="https://github.com/user-attachments/assets/28f9172a-d967-4397-8842-87482009411f" />


### 🔹 **User Interaction**  
![User Interaction]
<img width="1365" height="643" alt="Preview" src="https://github.com/user-attachments/assets/6708dd07-7cb4-4eb9-a3ea-7e7a495dab43" />

### 🔹 **Deployment & Testing**  
![Deployment]
<img width="1365" height="643" alt="Depolyed" src="https://github.com/user-attachments/assets/6d52cf8b-86f3-4244-9301-db9d882110af" />

### 🔹 **API Reference**  
![API Reference]
<img width="1365" height="644" alt="Depolyed_1" src="https://github.com/user-attachments/assets/a4602d38-6978-4c03-b87e-10a77daac7f7" />

---

## 📌 How to Run or Deploy

1. **Log in to IBM Cloud Lite**: [IBM Cloud Lite](https://cloud.ibm.com)
2. **Launch Watsonx.ai Studio**: Create a new AI agent in Watsonx.ai.
3. **Upload Nutritional PDFs**: Add resources like USDA and WHO guidelines for accurate meal recommendations.
4. **Select Tools for Web Search**: Configure search tools (Google, Wikipedia, etc.) for real-time data retrieval.
5. **Configure Agent Instructions and Topics**: Set clear instructions to focus the agent on nutrition-related queries.
6. **Test in Preview Panel**: Test and refine the agent using Watsonx.ai's preview feature.
7. **Deploy**: Deploy via a **web snippet**, **Streamlit**, or a **custom web interface**.

---

## 🛣️ Future Enhancements

- **Voice Integration**: Adding speech-to-text support for voice-driven queries.
- **Mobile App**: Developing a companion mobile app for on-the-go nutrition advice.
- **Multilingual Support**: Expanding to multiple languages for a global user base using **IBM Language Translator**.
- **Real-Time Feedback Loop**: Integrating real-time health tracking (e.g., from wearables) to adjust meal plans dynamically.

---

## 🔗 Useful Links

- **IBM Cloud Lite**: [IBM Cloud Lite](https://cloud.ibm.com)
- **IBM Watsonx.ai**: [IBM Watsonx.ai](https://www.ibm.com/watsonx)
- **USDA Nutritional Guidelines**: [USDA Guidelines](https://www.usda.gov)
- **WHO Nutrition Guidelines**: [WHO Nutrition](https://www.who.int/nutrition)
- **IBM SkillsBuild**: [IBM SkillsBuild](https://skillsbuild.org)

---

## ⚖️ License![Uploading instructions.png…]()


This project is licensed under the **MIT License**.

---

## 🔗 Connect with Me on LinkedIn

[LinkedIn Profile](https://www.linkedin.com/in/your-profile)

---

Created with 💙 during the **IBM SkillsBuild for Academia Internship 2025** by **[Your Name]**.

---

### Steps:
1. **Commit this file** after pasting the above content into the `README.md` editor.
2. Ensure the screenshots are uploaded under the **`/images`** folder in your repository for the links to work correctly. 

Now your **README.md** includes the relevant images and links!
