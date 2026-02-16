# 📈 Networking Estratégico en LinkedIn: Cómo Maximizar el Engagement para Estudiantes Universitarios.

## 🎯 Problema de Negocio

El networking y la marca personal en LinkedIn son vitales para el éxito laboral, pero existe un vacío de información sobre cómo los estudiantes universitarios adoptan estas herramientas. Tras capacitar a un grupo de estudiantes en estrategias de visibilidad profesional, surge el reto de entender su adopción tecnológica.
Este proyecto utiliza un algoritmo de clustering para responder a la pregunta: 
**¿Cómo podemos segmentar a los estudiantes según su comportamiento digital para predecir su lealtad a la plataforma y su éxito en la construcción de redes profesionales?**

Este proyecto transforma comportamientos en  **Estrategia de Retención**.

* **Objetivo:** Identificar perfiles de usuario para maximizar el desarrollar estrategias de marketing que generen engagement
* **KPI Impactado:** Tasa de retención

## 🧠 Methodologia
"Implementación de un algoritmo de K-Means Clustering para segmentar estudiantes según su nivel de interacción, red de contactos y uso estratégico de LinkedIn."

* **Study Population:** University students who received specific training in personal branding and career visibility.
* **Data Processing:** [Pandas, NumPy, Matplotlib, Seaborn, WordCloud, Scikit-Learn].
* **Validation:** Selection of 'k' using the Silhouette Score method.

## 👥 Marketing Profiles
| Student Type| Description | Marketing Strategy |
| :--- | :--- | :--- |
| **Strategic Career Builder** |*“I use LinkedIn as a key tool to build my career”* | Mentoring - Recruitment Events |
| **Exploratory Observer** |"I know LinkedIn exists and what it's for, but I don't know how to unlock its full potential" | Professional Digital Literacy - Clear Examples of Usefulness|
| **Passive Knower** | *“LinkedIn is important, although I don’t actively use it yet”* | Practical workshops - Incentives for interaction|

## 📊 Visualizations
Wordcloud of comments from surveyed students:
![WordCloud Comentarios](wordcloud_linkedin.png)
Students recognize the value of LinkedIn, but only in the long term.

Feature Influence Map
![Mapa_Influencia de variables](Influence_feature_map.png)
The features that point in the same direction reveal:

* *First quadrant:* Students for whom exposure and visibility are more important (sometimes twice as important) than their professional development, without implying that the latter is unimportant.

* *Fourth quadrant:* Students for whom professional development is moderately important, but whose profiles do not generate visibility on the social network.

![Clusters](clusters.png)


