<!-- # GoMozChecker - Bulk DA, PA & Spam Score Checker -->

<h1 align="center">DaPa</h1>
<h3 align="center">Bulk DA, PA & Spam Score Checker</h3>

<div align="center">


**GoMozChecker** is a simple program that grabs **Domain Authority a.k.a DA, Page Authority a.k.a PA & Spam Score** data from the Mozscape API.

<p align="center">
    <a href="http://github.com/" alt="Made with Python">
        <img src="https://forthebadge.com/images/badges/made-with-python.svg" /></a>
</p>

<h4 align="center">It requires Python ≥ 3.2.</h4>

# 

### Features

- [x] Bulk Checking
- [x] Fast (can grab 1000 URLs data in 15 Seconds)
- [x] Easy to Use
- [ ] 100% Accurate results
- [ ] 100% Error Free

#### Requirements
- Requests
- Config

## How to Use It ? (Usage)
#### ❗️ It is recommended to run this script on [Google Cloud Shell Editor](https://ssh.cloud.google.com/cloudshell/editor "Open Google Cloud Shell Editor") or else you may end up facing some unknown error.


```bash
1. 
```

2. Now we will open the "GoMozChecker" folder which got created "after clonning" it in the previous step.. 

```bash
cd GoMozChecker
```
3. Next we need to install the "python modules" which will be required for running the program
```bash
pip3 install -r requirements.txt
```
4. Next, you need to Add your "Moz API keys" in the "config.json" file for that run the following command, and paste your "Access ID" & "Secret Key" credentials when asked.

> ℹ️ Side Note: If you **don't have "Moz API keys"** then you need to sign up for a free Mozscape account at [Mozscape API Pricing](https://moz.com/products/api/pricing) and after that you will get your "Moz API Credentails"....

```bash
python3 api.py
```
5. Now the last thing to do before running the script is to add the Domain name in "urls.txt", so just paste the list of domain names in urls.txt.

> ⚠️ Side Note  : Do not insert more than 1000 URLs for checking at once or else you may encounter some errors on the way.

6. Finally we are ready to run the script, now the only thing you need to do is to run the following command:
```bash
python3 main.py
```
and just wait for few seconds... after that you will find a **".csv"** will get created named as "date-and-time.csv" for example: "23-09-2020_16:56.csv"

You can use any .csv viewer for viewing the .csv file..

I hope this will help. 😊

