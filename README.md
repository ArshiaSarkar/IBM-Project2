# 🧠 Mental Health Diagnostic Survey

This is an interactive Mental Health Diagnostic Tool built using Python, Pandas, and Gradio. It presents a set of 10 mental health-related questions to users and provides a simple interpretation based on their responses.

## 💡 Project Purpose

The goal is to encourage self-awareness about common mental health symptoms like depression and anxiety by offering a non-clinical, accessible, and private self-check survey.

---

## 🛠️ Features

- 10-question mental health survey.
- Interactive UI using Gradio.
- Simple logic-based diagnosis based on user responses.
- Prompts for professional help if critical signs are detected.

---

## 📦 Installation

### 🔗 Google Colab (Recommended)

You can run this notebook directly in Google Colab:

1. Open the Colab notebook.
2. Click on `Runtime > Run all`.
3. Wait for Gradio interface to launch and open the shareable link.

### 🧑‍💻 Local Setup

If you want to run it locally:

```bash
git clone (https://github.com/ArshiaSarkar/IBM-Project2/tree/main)
cd mental-health-diagnostic

pip install -r requirements.txt
````

*Or install the core dependencies manually:*

```bash
pip install pandas gradio
```

Then run the notebook in Jupyter or VSCode.

---

## 📋 Questions Used

The tool asks the following questions:

1. How often do you feel sad or depressed?
2. Do you experience anxiety or nervousness?
3. How is your sleep quality?
4. Do you have changes in appetite?
5. Do you feel hopeless or worthless?
6. Have you had thoughts of self-harm or suicide?
7. How would you rate your energy levels?
8. Do you find it hard to concentrate?
9. How often do you feel tired or fatigued?
10. Do you have difficulty relaxing?

---

## 🧠 How It Works

* Each answer is assigned a numeric score.
* Higher scores indicate stronger signs of emotional distress.
* If the user reports suicidal ideation, a critical warning is given regardless of total score.

### 📊 Scoring Tiers

| Score Range      | Interpretation                                                    |
| ---------------- | ----------------------------------------------------------------- |
| 0–4              | Low symptoms detected                                             |
| 5–9              | Moderate symptoms — consider monitoring or light support          |
| 10+              | High likelihood of depression or anxiety — consult a professional |
| Self-harm Answer | Immediate help message shown                                      |

---

## 🚨 Disclaimer

This tool is **not a medical diagnosis**. It is a basic educational and self-awareness tool and should not replace professional evaluation. If you're in distress, seek help from a licensed mental health professional or local support service.

---

## ✨ Demo Screenshot

![Demo](https://github.com/user-attachments/assets/501248b5-c976-495f-9a2c-62ce220953ef)

---

## 📄 License

This project is released under the MIT License.

---

## 🙌 Acknowledgements

Inspired by global efforts to increase mental health awareness through technology.

---

## ✨ Built with ❤️ by Arshia Sarkar



