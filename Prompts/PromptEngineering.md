# Prompt Engineering



Saturday, July 05, 2025 
create a prompt file in markdown format in visual studio code - Brave Search
https://search.brave.com/search?q=create+a+prompt+file+in+markdown+format+in+visual+studio+code&source=web&summary=1&conversation=652822b7675319cc2c2f4d 

Create Markdown Prompt VS Code
To create a prompt file in Markdown format in Visual Studio Code, you can follow these steps:
1.	Create a new Markdown file with a .prompt.md extension. For example, you might name it generate-interface.prompt.md.
2.	Place this file in the .github/prompts directory of your project. This directory is typically used for storing prompt files.
Here is an example of what the content of a prompt file might look like:

# User Authentication

Our application will have `users` with the following information:
- The standard user information, including: `name`, `email` (unique).
- A link for a "magic" login, which will be a `GUID` as well as the expiration date for the link.
- Social login account IDs for Microsoft, GitHub, and Google.
- The timestamp of the last login.
- The timestamp for when the user was created.
You can then create another prompt file called generate-interface.prompt.md that contains the instructions to generate the interface. Prompt files can reference each other, so you can pass the database schema into this prompt file as a simple Markdown link.
To use these prompt files in chat, use the attach button (paperclip) or use . Select Prompts from the menu, and then select the prompt file you want to use. Notice that when you use the generate-interface.prompt.mdfile, it automatically pulls in thedatabase_users.prompt.md` file.

Generative AI Scripting | GenAIScript
https://microsoft.github.io/genaiscript/ 
Prompting is Coding
Programmatically assemble prompts for LLMs using JavaScript. Orchestrate LLMs, tools, and data in a single script.
•	JavaScript toolbox to work with prompts
•	Abstraction to make it easy and productive
•	Seamless Visual Studio Code integration or flexible command line
•	Built-in support for GitHub Copilot and GitHub Models, OpenAI, Azure OpenAI, Anthropic, and more


create a prompt file in markdown format in visual studio code - Brave Search - https://search.brave.com/search?q=create+a+prompt+file+in+markdown+format+in+visual+studio+code&source=web&summary=1&conversation=652822b7675319cc2c2f4d 

Markdown and Visual Studio Code - https://code.visualstudio.com/docs/languages/markdown 

Customize AI responses in VS Code - https://code.visualstudio.com/docs/copilot/copilot-customization 

Prompt engineering for Copilot Chat - https://code.visualstudio.com/docs/copilot/chat/prompt-crafting 

Context is all you need: Better AI results with custom instructions - https://code.visualstudio.com/blogs/2025/03/26/custom-instructions 
Try this: create a file in your project called .github/copilot-instructions.md. This file will contain instructions that help Copilot understand your project better. It's automatically picked up by Copilot, so you don't have to do anything special to make it work.

Prompt As Code | GenAIScript - https://microsoft.github.io/genaiscript/guides/prompt-as-code/ 
