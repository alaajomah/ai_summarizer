# ai_summarizer
# Mini project using GitHub Models summarizer
# GitHub Models Text Summarizer – Lab

## 1. Lab Title

Using `meta/Llama-4-Scout-17B-16E-Instruct` for Text Summarization via `azure-ai-inference`

---

## 2. Objectives

By the end of this lab, I was able to:

- Connect to the GitHub Models endpoint using `azure-ai-inference`.
- Send chat completion requests to the `meta/Llama-4-Scout-17B-16E-Instruct` model.
- Build a prompt that summarizes a long paragraph into **exactly 3 bullet points**.
- Export the Colab notebook and organize the project in a structured GitHub repository.

---

## 3. Steps Completed

1. **Environment setup**
   - Installed `azure-ai-inference`.
   - Configured the `endpoint`, `model` name, and `GITHUB_TOKEN`.

2. **Client initialization**
   - Created a `ChatCompletionsClient` using `AzureKeyCredential`.
   - Verified the connection with a simple Q&A question (“What is the capital of France?”).

3. **Prompt and summarization logic**
   - Wrote a prompt that instructs the model to:
     - Summarize a given paragraph.
     - Produce **exactly 3 concise bullet points**.
     - Avoid extra text or headings.
   - Sent the request using `client.complete()` and printed the model’s response.

4. **Notebook and outputs**
   - Ran all cells in the Colab notebook.
   - Saved the model’s summary output to `summary_output.txt`.
   - Exported the Colab notebook to `.ipynb` and added it to the `notebooks/` folder.

5. **Repository organization**
   - Created the required folders: `notebooks/`, `outputs/`, and optional `assets/`.
   - Captured screenshots from the Playground / terminal and saved them in `assets/`.

---

## 4. Link to the Colab Notebook

You can open and run the Colab notebook here:

👉 [Open in Colab](<https://colab.research.google.com/drive/1gwCwxye2fqRJSeedV_zvnm_k5-5fqkEP?usp=sharing>)

The exported notebook file is also included in this repo:

- `notebooks/genai_summarizer.ipynb`

---



## 6. Summary of the Mini Project

This mini project demonstrates how to use GitHub Models through the `azure-ai-inference` SDK to perform **automatic text summarization**.

- The model used: `meta/Llama-4-Scout-17B-16E-Instruct`.
- Input: A long paragraph about **Generative AI**.
- Output: **Exactly three concise bullet points** capturing:
  - What generative AI is and what it can create.
  - How it relies on deep learning models and large datasets.
  - Its impact on industry adoption and productivity.

The project shows a simple but practical pattern for:
- Connecting to a hosted LLM endpoint.
- Designing a clear, constraint-based prompt.
- Saving and organizing experiments and outputs inside a reproducible GitHub repository.

---

## 7. How to Run This Project Locally (Optional)

1. Clone the repo:
   ```bash
   git clone <YOUR_REPO_URL>.git
   cd <YOUR_REPO_NAME>

