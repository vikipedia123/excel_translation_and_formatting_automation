# excel_translation_and_formatting_automation
Translate the formatted text (**bold**, *italic*)on xlsx directly into the target language and preserve the original formatting.

# Command line on powershell to run this
Note: You can choose other AI API key
`"C:\yourpathofdotnet\dotnet\dotnet.exe" build`
`$env:OPENAI_API_KEY="sk-proj-yourbeautifulapiofopenai"`
`$env:OPENAI_API_KEY="sk-proj-yourbeautifulapiofopenai"
& "C:\yourpathofdotnet\dotnet\dotnet.exe" run -- `
"C:\Users\yourfile.xlsx" `
"C:\Users\yourtargetfilename.xlsx"`

