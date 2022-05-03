# Rest-mex 2022: Recommendation System for Text Mexican Tourism
#  Recomendation System Analysis Test Corpus
-*- coding: utf-8 -*-

## Spanish (Español)
El conjunto de datos se encuentra dividido en 2 archivos: rest-mex_2021_recomendation_data_test.xlsx, Places.csv y una carpeta llamada UsersTraining
#rest-mex_2021_recomendation_data_test.xlsx:
El conjunto de datos consta de 681 usuarios (el 30 % del conjunto de datos original. El otro 70 % fue utilizado como conjunto de prueba), uno por cada recomendación que recibió un turista. Cada renglón en el archivo contiene 6 columnas:
1. Index: Es el índice de cada recomendación. Tipo de dato: Texto
2. Gender:  El género del turista. Tipo de dato: [Male, Female, N/I] (N/I = Not Information)
3. Place: El lugar turístico que se le recomienda al turista visitar. Tipo de dato: Texto. Tipo de dato: Texto
4. Location: El lugar de origen del turista (las regiones de centro, noreste, noroeste, occidente, y sureste se refieren a las regiones de México). Tipo de dato: Texto
5. Date:  Fecha en la que se emitió la recomendación. Tipo de dato: Fecha
6. Type: Tipo de viaje que haría el turista. Tipo de dato: [Family, Friends, Alone, Couple, Business]

La etiqueta que su equipo debe predecir va de 1 que significa el mayor grado de insatisfacción, hasta 5 que es el mayor grado de satisfacción. Se puede interpetar de la siguiente manera:
1. Muy malo
2. Malo
3. Neutral
4. Bueno
5. Muy bueno

#Places.csv:
El archivo contiene los 18 lugares que pueden ser recomendados. Estos lugares se encuentran en el estado de Nayarit, en México. 
Cada renglón contiene el nombre del lugar y su descripción con los datos más importantes del mismo.

#UsersTest
La carpeta contiene 633 archivos, cada archivo fue nombrado como 'UsuarioN.csv' donde UsuarioN es el índice para que se pueda identificar dentro del archivo  rest-mex_2021_recomendation_data_test.xlsx. Cara archivo csv tiene una lista del historial de opiniones que ha dado el UsuarioN en TripAdvisor. Estos datos estan organizados en 4 columnas donde en cada renglón se puede encontrar la siguiente información:
	Columna 1: El comentario que el turista otorgó (desconocido = comentario en blanco)
        Columna 2: El nivel de satisfacción que tuvo el UsuarioN
        Columna 3: El lugar que el turista visitó (Este lugar puede ser de cualquier parte del mundo, no necesariamente de México)
        Columna 4: La calificación global que tiene ese lugar en el sitio TripAdvisor
##Importante 
Todos los participantes que se registraron al rest-mex 2022 y los que accedan a estos datos (sin importar que participen en el foro o no) aceptan utilizar los datos obtenidos del REST-MEX exclusivamente con fines académicos y de investigación. Cualquier otro uso de los datos será bajo su responsabilidad.

## English
The data set is divided into two files: rest-mex_2022_recomendation_data_test.xlsx, Places.csv, and a folder called UsersTest
# rest-mex_2022_recomendation_data_test.xlsx:
The data set consists of 681 users (30% of the original data set. The other 70% was be used as a test set), one for each recommendation received by a tourist. Each row in the file contains six columns:
1. Index: It is the index of each recommendation. Data type: Text
2. Gender: The tourist's gender. Data type: [Male, Female, N / I] (N / I = Not Information)
3. Place: The tourist place that the tourist is recommended to visit. Data type: Text. Data type: Text
4. Location: The place of origin of the tourist (the central, northeast, northwest, west, and southeast regions refer to the regions of Mexico). Data type: Text
5. Date: Date the recommendation was issued. Data type: Date
6. Type: Type of trip that the tourist would do. Data type: [Family, Friends, Alone, Couple, Business]

The label that your team must to predict ranges from 1, which means the highest degree of dissatisfaction, to 5, which is the highest degree of satisfaction. It can be interpreted as follows:
1. Very bad
2. Bad
3. Neutral
4. Good
5. Very good

# Places.csv:
The file contains the 18 places that can be recommended. These places are in the state of Nayarit, in Mexico.
Each line contains the name of the place and its description with the most important information about it.
#UsersTest
The folder contains 633 files; each file was named 'UserN.csv' where UserN is the index to be identified within the rest-mex_2021_recomendation_data_test.xlsx file. Each csv file has a list of the review history that UserN has given on TripAdvisor. These data are organized in 4 columns where the following information can be found in each line:
Column 1: The comment that the tourist granted (unknown = blank comment)
Column 2: The level of satisfaction that the User had
Column 3: The place the tourist visited (This place can be from anywhere in the world, not necessarily from Mexico)
Column 4: The overall rating that place has on the TripAdvisor site
##Important
All participants who registered for rest-mex 2022 and those who access this data (regardless of whether they participate in the forum or not) agree to use the data obtained from REST-MEX exclusively for academic and research purposes. Any other use of the data will be under their responsibility.
