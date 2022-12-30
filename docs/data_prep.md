# Data Prepration stage

- Convert my data into test and train in 70:30 ratio

```
data.xml 
    |-train.tsv
    |-test.tsv

```
- We are chossing only three tags in the xml data - 1. row id, 2. title and body 3. tags (stackoverflow tags specific to python)

|Tags|Feature names|
|-|-|
|row id|row id|
|title and body|text|
|stackoverflow tags|Label -python|
