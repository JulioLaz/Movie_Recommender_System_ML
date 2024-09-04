# Movie_Recommender_System_ML
<h1 align="center"><b><big>:clapper: :film_projector:	:film_strip: Movie Recomender - CINEMIO :movie_camera: </big></b></h1>
<p align="center">
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/Leop/images/movies3.png" alt="Movies" width="100%" height="100%"/>
</p>
## Tecnologías Usadas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Descripción del proyecto
<p align="justify">En este proyecto, nos sumergimos en el fascinante mundo de la ciencia de datos aplicada a la industria del entretenimiento, específicamente en el desarrollo de un sistema de recomendación de películas. Con acceso a datos reales de una plataforma de streaming, nuestro objetivo es mejorar la experiencia del usuario mediante la construcción de un recomendador personalizado, capaz de ofrecer sugerencias precisas y relevantes.
El proyecto está estructurado en varias etapas, cada una diseñada para abordar diferentes enfoques de recomendación:</p>
<p align="justify"> Recomendación No Personalizada: Comenzamos con un sistema básico que sugiere películas populares a todos los usuarios, independientemente de sus preferencias individuales.
<p align="justify"> Recomendación Basada en Contenido (Content-Based): Avanzamos hacia un modelo que recomienda películas basadas en las características de las películas que un usuario ya ha disfrutado, utilizando similitudes en géneros y descripciones.
<p align="justify"> Filtrado Colaborativo (Collaborative Filtering): Finalmente, implementamos un enfoque que sugiere películas basadas en las preferencias de usuarios similares, aprovechando patrones de comportamiento colectivo.

## Objetivos
* <p align="justify"> Permitir al usuario interactuar con el repositorio de películas y poder calificarlos, de acuerdo a un rango de rating del 1 al 5. </p>
* <p align="justify"> Desarrollar un algoritmo de recomendación que aprenderá de las preferencias del usuario analizando datos del usuario y películas para ofrecer sugerencias personalizadas basadas en sus gustos y que estará disponible una vez que haya calificado al menos una película.</p>
<h3 align="center"><b>Flujo del proceso </b></h1>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/3.jpg" alt="proceso" width="100%" height="100%"/>
<br>

* <p align="justify"> Implementar un recomendador basado en contenido (Content-based), para que el cliente pueda ver títulos recomendados de películas según popularidad y por género.</p>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/5.jpg" alt="proceso" width="100%" height="100%"/>
<br>

Para ello utilizaron dos estrategias: Similitud de Jaccard y la Similitud de Coseno que se basan en las teorias siguientes:

  <ul>
    <li>
      <b>Similitud de Jaccard</b>: es una métrica utilizada para medir la similitud entre dos conjuntos de datos y permite a los sistemas identificar y recomendar películas que comparten características similares.
      <p align="center">
          <img src="https://github.com/user-attachments/assets/67123502-51dd-4daf-8198-ed3bc43c0189" alt="Jaccard" width="100%" height="100%"/>
          <br>
          <b>Jaccard</b>
          <br><br>
          <img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/Leop/images/jaccard1.jpg" alt="Jaccard Formule" width="500" height="250"/>
          <br>
          <b>Jaccard Formule</b>
      </p>
    </li>
    <li>
      <b>Similitud de Coseno con TF-IDF</b>
      <p align="center">
          <img src="https://github.com/user-attachments/assets/df034b19-c1fd-45eb-892e-b66df1d922d0" alt="Coseno Similitud" width="100%" height="100%"/>
          <br>
          <b>Coseno Similitud</b>
          <br><br>
          <img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/Leop/images/cosined.png" alt="Coseno Fórmula" width="500" height="250"/>
          <br>
          <b>Coseno Fórmula</b>
      </p>
    </li>
  </ul>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/6.jpg" alt="proceso" width="100%" height="100%"/>
<br>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/7.jpg" alt="proceso" width="100%" height="100%"/>
<br>

* <p align="justify"> Implementar un recomendador basado en filtrado colaborativo (Collaborative filtering) y visualizar resultados. </p>

<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/8.jpg" alt="proceso" width="100%" height="100%"/>
<br>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/9.jpg" alt="proceso" width="100%" height="100%"/>
<br>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/10.jpg" alt="proceso" width="100%" height="100%"/>
<br>

<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/11.jpg" alt="proceso" width="100%" height="100%"/>
<br>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/12.jpg" alt="proceso" width="100%" height="100%"/>
<br>
<img src="https://github.com/LeopoldoGitHub/Cinemio/blob/main/img/Cinemio-show/13.jpg" alt="proceso" width="100%" height="100%"/>
<br>

## Enlaces del Proyecto
https://favoritemovies.streamlit.app/


