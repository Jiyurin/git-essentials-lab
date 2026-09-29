# How to run the library demo

## Prerequisites
- JDK 17 or later (`java -version`)
- Python 3.9 or later (`python3 --version`; on Windows you can use `py -3`)
- No Maven or extra libraries are needed

## Run the demo
From the repository root:

    python3 run.py demo

## What it does
The runner compiles the Java code in `src/library/` into a temporary folder and runs a short
demo of the library app: members borrowing books within their limits, loan due dates,
overdue fees on late returns, catalog title search, and a printed loan receipt.