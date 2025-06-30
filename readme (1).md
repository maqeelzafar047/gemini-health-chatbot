# Gemini Health Query Chatbot

**Developed by:** [**M Aqeel Zafar**](https://github.com/maqeelzafar047)

---

## Overview

The **Gemini Health Query Chatbot** is a Colab-based assistant that uses Google's Gemini 2.0 Flash API to answer general health-related queries. The chatbot emphasizes prompt safety and user-friendly interaction for non-professional users seeking general health information.

---

## Key Features

- Uses **Google Gemini 2.0 Flash Model** via REST API.
- Focus on **safe, filtered health answers** (no prescriptions, diagnoses, or emergency responses).
- Runs entirely in **Google Colab**, no local installation needed.
- Easy-to-understand code and user interaction through notebook cells.
- Uses **prompt engineering** to limit responses to safe, helpful topics.

---

## Prerequisites

- A Google account to run the Colab notebook.
- An active **Google Cloud API key** with access to the `generativelanguage` API.
- Internet connection.

---

## How to Use

1. **Open the Colab notebook**.

2. In the **API** **cell,** **replace**:

   ```python
   API_KEY = "YOUR_GOOGLE_CLOUD_API_KEY"
   ```

   with your actual API key.

3. Run all cells in order.

4. When prompted, type your health-related question.

5. To exit, simply type `exit`.

---

## Sample Interaction

```
Asslam-o-Alaikum! Dear User
Welcome to the Health Assistant!
Type 'exit' to quit.

🟠 You: What causes fever?
🟢 Gemini: Fever can be caused by a variety of factors, such as infection...

🟠 You: exit
🟢 Allah Hafiz! Stay safe and healthy. 🙂
```

---

## Code Summary

- **requests** library is used to make API calls.
- Gemini Flash API is contacted with a **safety-focused prompt**.
- Chat loop allows continuous interaction until the user exits.
- Outputs are printed directly in the notebook for each query.

---

## Safety Notice

This chatbot is **not intended for medical diagnosis or emergency advice**. All information is general and informational only.

---

*Report generated on June 30, 2025*

