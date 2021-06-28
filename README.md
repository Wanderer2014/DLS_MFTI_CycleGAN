# DLS_MFTI_CycleGAN
Image2Image - CycleGAN

Здесь архив с датасетом, состоящий из трех частей 'horse2zebra_1.zip', 'horse2zebra_2.zip', 'horse2zebra_3.zip', 
необходимо распаковать в одну общую папку horse2zebra_ , которая должна находиться в текущем каталоге программы (если на PC), откуда запускается py-файл cyclegan_image2image_PC.py. В принципе py-файл всё сам сделает, если у вас установлены все необходимые библиотеки на компьютере (смотрите файл requirements.txt).

Запуск py-файла: python cyclegan_image2image_PC.py

Файл ноутбука CycleGAN_Colab_Yuriy_Belov_stepik_ID_21313451_itog.ipynb предназначен для запуска в Colabe. 
Для Colaba общую папку horse2zebra_ с датасетом необходимо упаковать в zip-архив horse2zebra_.zip

Если вы не хотите проводить данные манипуляции, то можете открыть (либо скачать) всё на Google Диске по ссылке - https://drive.google.com/drive/folders/1hpLL95QjiKyCwnizPs1FQhMJGj8UyaFj?usp=sharing

В расшаренной папке находится теже самые файлы (ноутбук, pdf-файл, веса за 300 эпох обучения модели CycleGAN), плюс уже объединенный zip-архив horse2zebra_.zip, к которому идет обращение из ноутбука. 

Файл CycleGAN_Colab_Yuriy_Belov_stepik_ID_21313451_itog.py - это просто py-копия ноутбука, настроенного на работу в Colabe. 

Если же хотите повозиться с CycleGAN на локальном компьютере, то советую запускать файл cyclegan_image2image_PC.py )

