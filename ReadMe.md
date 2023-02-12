# Learn Mapper and Reducer

## Goals
1. To create mapper and reducer function without combiner with MRJob library
2. Save the output to txt file

## Library
1. `from mrjob.job import MRJob`: to define our "Job"
2. `from mrjob.step import MRStep`: to represent our "Job"
3. `from mrjob.runner import MRJobRunner`: to run our "Job"
4. `import re`: to deal with regex

## How to run
1. Run `python3 <script.py> <data.txt>` on terminal
2. Run `python3 <script.py>` on terminal, or
3. "Run Python File" on the Editor
