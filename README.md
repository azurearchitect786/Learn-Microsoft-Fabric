# Learn Microsoft Fabric

The code will look like the following:
```
COPY INTO [dbo].[MyTable]
FROM 'https://mystorageaccount.blob.core.windows.net/mycontainer/
curated/weather/florida_weather.parquet'
WITH (
     CREDENTIAL =
            (
            IDENTITY = 'SHARED ACCESS SIGNATURE',
            SECRET = ''
            ),
     FILE_TYPE = 'PARQUET'
);

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 3-6 | A modern web browser (Microsoft Edge or Google Chrome) | Windows, macOS, or Linux |


