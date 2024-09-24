# BudgetBee

### Problem Statement 

Conventional expense management tools such as the ones built into banking apps are a great start to understanding our spending habits. They give us a receipt by receipt breakdown of how much we spend in different categories. However, anyone who has tried using these built in tools knows that they do not track what we buy, but rather where we buy from. In today's day and age where convenience is everything and more one-stop shops like Amazon are surfacing, financial tracking at the receipt level is no long enough.

### Solution

This is where BudgetBee comes in. By breaking down our purchases to individual items, BudgetBee is able to more accurately analyze our spending patterns. Combined with customizable categories, you have the flexibility to decide which categories you care about and at what granularity.

### Spin up 
To see this project in action you will need:

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [Polyglot](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) to run the notebook using .NET Interactive.
- Your own instance of OpenAI or Azure OpenAI.

Using `settings.json.openai-example` or `settings.json.azure-example` as a template, create a `settings.json` file in the `config` folder. 

Then go to `budgeting-app.ipynb` and run all cells to see the project in action.

> [!NOTE]
> This project is currently just a proof of concept that demonstrates using Microsoft.SemanticKernel to sort the items on receipts into customizable categories. There is no front end or back end at the moment.
