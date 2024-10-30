# Time Series Classification

# Список файлов 
solution.ipynb - основной код с обучением, отбором признаков, EDA.  
load.ipynb - код для получения файла submission.csv.   
model.zip - архив с моделью.  
submission.csv - файл с таблицей вероятностей 1 класса на тестовых данных.  

# Пример запуска

Вся работа делалась в среде Google Colab.

### solution.ipynb

Открыть файл в Google Colab, подгрузить в среду архивы train.parquet и test.parquet.

Код содержит: отбор признаков, EDA, обучение модели, получение файла submission.csv

### load.ipynb

Открыть файл в Google Colab, подгрузить в среду архивы model.zip и test.parquet.

Код содержит: генерацию файла submission.csv с использованием уже обученной модели из архива model.zip

