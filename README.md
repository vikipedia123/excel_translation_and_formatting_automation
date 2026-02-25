# 📊 Excel Translation & Formatting Automation

Translate formatted Excel text (**bold**, *italic*, etc.) directly into a target language while preserving the original rich-text formatting.

This tool processes `.xlsx` files and ensures:

- ✅ Run-level formatting is preserved  
- ✅ Cell-level styling is retained  
- ✅ Output is written to a new Excel file  

---

## 🚀 How to Run (PowerShell)

> 💡 You can use your own AI API key.

### 1️⃣ Build the Project

```powershell
& "C:\your-path-to-dotnet\dotnet.exe" build
2️⃣ Set Your API Key
$env:OPENAI_API_KEY="sk-proj-your-openai-api-key"
3️⃣ Run the Translator
& "C:\your-path-to-dotnet\dotnet.exe" run -- `
"C:\Users\your-input-file.xlsx" `
"C:\Users\your-output-file.xlsx"
📁 Example
& "C:\Program Files\dotnet\dotnet.exe" run -- `
"C:\Users\Vicki.Burckel\Documents\Automation\B bold.xlsx" `
"C:\Users\Vicki.Burckel\Documents\Automation\B bold_ZH.xlsx"
📝 Notes

 styling

Writes translated content under the CHINESE column
