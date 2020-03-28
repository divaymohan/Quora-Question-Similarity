# Overview :
* ## Very Basic Analysis:
    * ### Data Size
    ```python
    import os
   fileSize = round(os.path.getsize('questions.csv')/1000000,2);
   print("File Size: {} MB".format(fileSize))
    ```
    > File Size: 60.75 MB


    * ### Data Format
    ```python
    import pandas as pd
    df = pd.read_csv("questions.csv")
    df.head()
    ```
    > 
* ## Basic Analysis:
    * ### Number Of Data Points
    * ### Number Of Features
    * ### Features Data Types
* ## Description :
```

```
