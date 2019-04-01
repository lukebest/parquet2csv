# Intro
Parquet is a columnar format that is supported by many other data processing systems. Spark SQL provides support for both reading and writing Parquet files that automatically preserves the schema of the original data. When writing Parquet files, all columns are automatically converted to be nullable for compatibility reasons.

This is a simple python code for convert parquet files to pandas csv files.
# Usage
## environment
```bash
conda install pyarrow
```
or
```bash
pip install pyarrow
```
Move parquet files you want to convert into a folder, and modify the source code
```python
path = 'JoinPredict-20190401055632-SLOT_0-29358'
```
Then run it.
It'll auto-convert all the parquet files to one csv file.
