# hse23_hw2

Ссылка на colab: https://colab.research.google.com/drive/1s25tS-Z-WEj0FExw8JtB0WvVSSKUgTE2?usp=sharing

Для анализа были выбраны клеточная линия HeLa-S3 и гистоновая метка H3K9me3. 

Реплики: ENCFF000BBW и ENCFF000BBT

Контроль: ENCFF000BAU

## До подрезания

ENCFF000BBW

![image](https://user-images.githubusercontent.com/87883391/222204448-947bb1c2-cfd5-46f7-a519-5bb005a703c8.png)
![image](https://user-images.githubusercontent.com/87883391/222204533-7d325ce0-98e6-4dbe-9f67-78c9163a3588.png)

ENCFF000BBT

![image](https://user-images.githubusercontent.com/87883391/222204637-269632da-512b-455e-9e21-8f6870c89286.png)
![image](https://user-images.githubusercontent.com/87883391/222204692-e23e002a-f473-4d7e-ae9e-778340141201.png)

ENCFF000BAU

![image](https://user-images.githubusercontent.com/87883391/222204790-5a6cec48-3069-4a24-94d0-9e4ef6a996dd.png)
![image](https://user-images.githubusercontent.com/87883391/222204843-a434e99c-53db-4e43-a50b-05c5f367cea9.png)

## После подрезания

ENCFF000BBW

![image](https://user-images.githubusercontent.com/87883391/222219368-71e35923-ad73-4d80-92e3-141cf5e4fd7c.png)

ENCFF000BBT

![image](https://user-images.githubusercontent.com/87883391/222219437-0a4240f7-d07b-43b6-a6a8-c3da87e71988.png)

ENCFF000BAU

![image](https://user-images.githubusercontent.com/87883391/222219529-270ccbf8-7ddc-4dcd-8600-be981cd74077.png)

Для ENCFF000BBW и ENCFF000BBT улучшение от подрезания незначительное, для ENCFF000BAU заметно значительное улучшение (это видно, например по Per base sequence quality).

## Таблица выравниваний

|             | Общее число ридов | Процент выровненных уникально | Процент выровненных неуникально | Процент невыровненных |
|-------------|-------------------|-------------------------------|---------------------------------|-----------------------|
| ENCFF000BBW |      41374655     |        4.60%                  |            16.00%               |        79.40%         |
| ENCFF000BBT |    18687249       |           4.72%               |            16.51%               |       78.77%          |
| ENCFF000BAU |       69747252    |         4.50%                 |           11.69%                |        83.81%         |

Большинство ридов не выровнялись, поскольку выравнивание происходило только на одну хромосому. 

## Диаграммы

Сравнение пиков 1 реплики и с пиками, приведенными в ENCODE

![image](https://user-images.githubusercontent.com/87883391/222248343-0dc6bc92-873b-4d00-aa95-d686e70ae0f2.png)
![image](https://user-images.githubusercontent.com/87883391/222248431-530c025d-ba3f-4c40-b20d-d25f765dd4ed.png)

Сравнение пиков 2 реплики и с пиками, приведенными в ENCODE

![image](https://user-images.githubusercontent.com/87883391/222248513-303a5d94-837b-4602-858e-6b3dc46dbe5a.png)
![image](https://user-images.githubusercontent.com/87883391/222248622-f1c3d1a6-9523-4c0c-8a36-b3b5f7151733.png)

Пересечения очень маленькие опять же по той причине, что мы выравнивали только на 1 хромосому. 
