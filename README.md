# Get-Financial-Data-From-FMP
Actually there are a lot of websites providing financial data ([finviz](https://finviz.com/),[yahoo finance](https://finance.yahoo.com/)...). A guide to use finviz to get financial data is given [here](https://towardsdatascience.com/get-up-to-date-financial-ratios-p-e-p-b-and-more-of-stocks-using-python-4b53dd82908f).

Here we obtain data from [FinancialModellingPrep](https://financialmodelingprep.com/) because it provides the most complete data, especially when analyzing historical ratios for the **past few years** for each company. Also, the data can be directly used in [Fundamental Analysis](https://www.investopedia.com/terms/f/fundamentalanalysis.asp) without changing the type.

To be able to get the data you need an API Key from FinancialModellingPrep. Here is the instruction to get the API key:

1. Go to the [Documentation page](https://financialmodelingprep.com/developer/docs/) of FMP
2. Click on "Get my API KEY here"
3. Create a new account or log in

Notice that unpaid account only gives you **limited requests (250)**, you have to upgrade to a premium version or create a new account if you want to keep going. In the code below, I use my own API key to get the result and you should expect an **error** if you don't replace API with you own valid API. 

Note that I am **not** affiliated with FinancialModellingPrep.
