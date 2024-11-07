# Data - репозиторий для датасетов

Чтобы прочитать данные со страницы GitHub в Pandas, укажите URL-адрес метода read_csv(~):

import pandas as pd
url = "https://raw.githubusercontent.com/OlgaManakova2021/DataSets/main/houses.csv"
df = pd.read_csv(url)

Обратите внимание, что URL-адрес начинается с raw. Чтобы получить этот URL-адрес, посетите страницу GitHub, содержащую набор данных.
Далее нажмите на кнопку "Raw" вверху, чтобы получить обычный CSV-файл.
