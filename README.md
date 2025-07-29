# AI-Powered Student Assistance Chatbot for Admissions through MHT-CET

This project developed an **AI chatbot** to assist students with **MHT-CET admission queries**. The chatbot leverages **Meta's Llama-3.2-3B-Instruct** model, fine-tuned using **Unsloth**, to provide personalized guidance on:

- Application requirements  
- Scholarship opportunities  
- Eligibility criteria
- Finding colleges
- and many more...

This innovative approach improves the student experience by delivering tailored and instant responses to admission-related queries.

---

## 🛠️ Technologies Used

- **Open-source AI models** (Meta's Llama-3.2-3B-Instruct)
- **Unsloth** for fine-tuning
- **Streamlit** for the user interface
- **Python**

---

## 🚀 How to Use This Repository

### Step 1: Prepare the Environment
1. Download this repository and navigate to the required files.
2. Place the `models` folder in the **"My Drive"** of the Google account you'll use with **Google Colab**.

### Step 2: Run the Chatbot
1. Open the **`CET_Assist.ipynb`** notebook in **Google Colab**.
2. Run the cells sequentially and follow the instructions in the notebook.
3. **Important Notes:**
   - Only the **Cloudflare link** provided in the notebook will work; other links are unsupported.
   - Ensure your session is running on at least a **T4 GPU**.

---

## 🔧 Fine-tuning Instructions

If you want to fine-tune the **Llama-3.2-3B-Instruct** model (similar to this project):
1. Use the **`Project_Llama_3_2_finetuning.ipynb`** notebook in **Google Colab**.
2. Follow the detailed instructions within the notebook to prepare the data, configure fine-tuning parameters, and execute the process.

---

## 📁 Files/Folder in repository

- **models/**: Contains the fine-tuned model files (`adapter_model.safetensors`).
- **CET_Assist.ipynb**: Main notebook to deploy and run the chatbot.
- **Project_Llama_3_2_finetuning.ipynb**: Notebook for fine-tuning the Llama-3.2-3B-Instruct model.
- **data.json**: data we use for fine-tuning.

---

## 💻Output
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; ">
  <img src="https://github.com/user-attachments/assets/42fc670d-18fa-4aec-a157-11d7e7f32905" height="340" alt="starting" style="object-fit: cover;">
  <img src="https://github.com/user-attachments/assets/3abe0d87-aeb1-4d18-81cf-5da5184796ae" height="340" alt="mobile_phone" style="object-fit: cover;">
  <img src="https://github.com/user-attachments/assets/d51045d3-d4a0-4c1b-af9f-3e8adb489bd0" height="340" alt="mobile_phone1" style="object-fit: cover;">
  <img src="https://github.com/user-attachments/assets/6717143a-829e-47a1-b7d4-dbb3c8e56007" height="340" alt="output" style="object-fit: cover;">
</div>

---


## 📝 Acknowledgments

- **Meta** for their open-source Llama model.
- **Unsloth** for simplifying fine-tuning processes.

---

Enjoy building and improving the AI-powered student assistance chatbot! 🎓🤖
