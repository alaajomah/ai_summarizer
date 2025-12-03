# ai_summarizer

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
   - Created the required folders: `notebooks/`, `outputs/`.

---

## 4. Link to the Colab Notebook

You can open and run the Colab notebook here:

👉 [Open in Colab](<https://colab.research.google.com/drive/1gwCwxye2fqRJSeedV_zvnm_k5-5fqkEP?usp=sharing>)

The exported notebook file is also included in this repo:

- `notebooks/Summarizer.ipynb`

---





