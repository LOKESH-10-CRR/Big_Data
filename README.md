# Big_Data
### Magic Commands in Data Bricks.
#### %sql    -> to run SQL Code.
#### %Python -> to run Python Code.
#### %Spark  -> to run Spark Jobs.
#### %fs     -> to check file system.
#### %ps     -> to check process status.
# Utilities
#### They allow us to perform deferent type of tasks in a single Notebook
#### ex :- File operations with ETL tasks etc.
#### We can only run utilities from (python , scala, R) cells in a note book.
#### Following are the utilities in Azure data bricks they are 
#### 1) File System Utilities.
#### 2) Secret Utilities ( from key vault).
#### 3) Widget Utilities ( parameterize notebooks so that a data factory pipeline can call this notebook. just like a parameter to function. Really help full for reusability purpose).
#### 4) Notebook Workflow Utilities ( Allow us to call another work book ).
### while doing file operations from Azure data bricks to File blob storage better to follow abfs driver process (azure blob File system ) driver. The following syntax as given below .
### abfs[s]:// container @storage_account_name.dfs.core.windows.net / folder_path / file_name .
### example :- abfss://demo@formula1dl.dfs.core.windows.net/
### example2 :- abfss://demo@formula1dl.fs.core.windows.net/test.

### https://colab.research.google.com/drive/17baMmZeRJ7ccO8J0VWmjr3G_4NXVHwau?usp=sharing
