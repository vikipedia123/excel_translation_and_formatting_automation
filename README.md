# 📊 Excel Translation & Formatting Automation

Translate formatted Excel text (**bold**, *italic*, etc.) directly into
a target language while preserving the original rich-text formatting.

This tool processes `.xlsx` files and ensures:

-   ✅ Run-level formatting is preserved\
-   ✅ Cell-level styling is retained\
-   ✅ Output is written to a new Excel file

------------------------------------------------------------------------

## 🚀 How to Run (PowerShell)

> 💡 You can use your own AI API key.

### 1️⃣ Build the Project

``` powershell
& "C:\your-path-to-dotnet\dotnet.exe" build
```

------------------------------------------------------------------------

### 2️⃣ Set Your API Key

``` powershell
$env:OPENAI_API_KEY="sk-proj-your-openai-api-key"
```

------------------------------------------------------------------------

### 3️⃣ Run the Translator

``` powershell
& "C:\your-path-to-dotnet\dotnet.exe" run -- `
"C:\Users\your-input-file.xlsx" `
"C:\Users\your-output-file.xlsx"
```

------------------------------------------------------------------------

## 📁 Example

``` powershell
& "C:\Program Files\dotnet\dotnet.exe" run -- `
"C:\Users\your-input-file.xlsx" `
"C:\Users\your-output-file.xlsx"
```

------------------------------------------------------------------------

## 📝 Notes

-   Your Excel file must contain headers:
    -   `YOUR Domain Language`
    -   `YOUR Target language`
-   The program from this file translates from **ENGLISH → CHINESE**
-   Make sure Excel is closed before running
-   The translated file will be saved to the specified output path

------------------------------------------------------------------------

## 🛠 Requirements

-   .NET SDK installed
-   Internet connection
-   Valid AI API key
-   ClosedXML NuGet package

------------------------------------------------------------------------

## 📄 Output

The output file:

-   Preserves **bold**, *italic*, underline, font size, font name, and
    color
-   Maintains original cell styling
-   Writes translated content under the `CHINESE` column
