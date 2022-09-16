# Generate_Chrome_Extension_i18n_Locale_Files
Generate Chrome extension i18n locale files


# Steps
1. Create a spreadsheet in Google Docs, the header should be as shown below, or refer to [this template](https://docs.google.com/spreadsheets/d/1qSR49TD8heT9baOoEAPn-aOPWehHByBjh96jJWHean4/edit?usp=sharing)
![image](https://user-images.githubusercontent.com/18564039/190636673-9e22d193-fa28-407c-9ca8-cfefe4ca6b92.png)
2. The first two columns are fixed names, the third column and after should be the [available locale codes](https://developer.chrome.com/docs/webstore/i18n/#choosing-locales-to-support)
3. Usually, the third column is set to the language you are familiar with, and the other columns use GOOGLETRANSLATE to translate the language you are familiar with into the target language
![image](https://user-images.githubusercontent.com/18564039/190639576-3d1c6a5a-836a-41e2-bc4d-582aeffb189f.png)
4. Copy the spreadsheet file key from the URL
5. Open the Generate_Locale_Files.ipynb file in Google Colab and paste the key obtained in step 4 in the 11th row of the first cell
6. Execute all cells, then you can generate the locale files in Colab and download them to your local extension directory
![image](https://user-images.githubusercontent.com/18564039/190643938-316c8796-7eff-4418-ad72-38d252b358cd.png)

