# DataEngineeringProjects
## This project shows the step-by-step process for executing a no-code simple ETL pipeline in Azure Data Factory.
### STEP 1: Extract
#### Two excel files labelled 'TEACHER_TABLE' and 'STUDENT_TABLE' were uploaded into Azure Blob storage account
### STEP 2: Transform
#### A full outer join function was applied to both files and merged into one file.
### STEP 3: Load
#### The output file from step 2 above was loaded into Azure blob storage in a downloadable parquet format. Parquet is the file type of choice because it compresses the file output and optimizes files for storage. This is particularly useful when storing large files with millions of data rows.
### P.S: To view the downloaded parquet file, access the parquet file, then add the '.parquet' extension to the filename. Afterwards, simply go to 'https://parquetreader.com/home' and drag-drop the file to read its contents.
