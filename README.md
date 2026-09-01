# SpendDNA: Your Wallet's Year-End Story 💸

**"Spotify Wrapped for your money."**.

## What is this?
Let's be real: bank statements are messy and impossible to read. SpendDNA is a Python project I built to figure out exactly where money goes. 

It takes 6 months of raw, ugly UPI and bank exports, cleans the data, and spits out a clean, readable summary of spending habits.It categorizes purchases, flags weirdly high transactions, and even assigns a financial "personality type" (like if you're a late-night Swiggy orderer).

## The Challenge (Strings, Lists, Dicts, Sets, Functions, NumPy, Pandas, Datetime, EDA, Anomaly Detection).
Anyone can use AI or fancy pre-built tools to read a CSV, but this project was built under strict constraints to prove real data-wrangling skills.

**What I used:** 
* Just Python, Pandas, and NumPy.

**What was strictly forbidden:**.
* No Regex (`re`): All text extraction had to be done with pure string matching.
* No visualization libraries: No Matplotlib or Seaborn. The final report is 100% text/ASCII.
* No automated profiling tools or machine learning.

## Core Features
1. **The Cleaner:** Fixes 4 different date formats and 3 different currency formats all mixed in the same file.
2. **Vendor Extraction:** Figures out that a messy string like `UPI-SWIGGY-1234@HDFCBANK` just means `Swiggy`.
3. **Smart Categorization:** Drops spending into 12 buckets like Quick Commerce, Food Delivery, and Investments.
4. **Time-of-Day Tracking:** Pinpoints behavioral habits (like ordering food past 9 PM).
5. **Anomaly Detection:** Uses Z-scores to flag unusually high transactions automatically.
6. **Archetype Engine:** Assigns fun labels like "The YOLO Spender" or "The Shopaholic" based on the math.



## How to run it yourself
1. Clone this repo.
2. Make sure you have `pandas` and `numpy` installed.
3. Open `SpendDNA_Atharv.ipynb`.
4. Drop `rahul_transactions.csv` (or your own bank statement exported as a CSV) into the same folder.
5. Run all the cells and see where your money actually went!
