### How to convert a Markdown file to a PDF

There are [multiple options](https://gist.github.com/justincbagley/ec0a6334cc86e854715e459349ab1446) for the conversion. The simplest way is to use grip.

The command-line-tool grip can be installed on Windows with `pip install grip` inside a terminal. For the conversion, navigate to the folder containing the Markdown in the terminal and run the command `grip YourMarkdownFile.md -b`. The file content will be displayed in a webbrowser. A PDF can be obtained by printing the Website to a PDF file by `Ctrl + P` and selecting `Microsoft Print To PDF` as printer. 

