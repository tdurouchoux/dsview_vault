---
already_read: false
link: https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine?hl=fr#1
read_priority: 1
source: null
tags:
- Deep_Learning
- Python
- Natural_Language_Processing
type: Content
upload_date: '2023-09-21'
---

https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine?hl=fr#1
## Summary

L'atelier de programmation présente l'utilisation de TensorFlow.js pour créer une application Web similaire à "Teachable Machine" en utilisant l'apprentissage par transfert. 

1. **Introduction à TensorFlow.js** : TensorFlow.js est une bibliothèque de machine learning qui permet d'exécuter des modèles dans divers environnements JavaScript, y compris les navigateurs et Node.js. Il offre des avantages tels que la confidentialité des données, la rapidité d'inférence et des coûts réduits.

2. **Apprentissage par transfert** : Cette technique permet de réutiliser un modèle pré-entraîné (comme MobileNet) pour une nouvelle tâche, nécessitant moins de données et un temps d'entraînement réduit.

3. **Modèles de base** : Les modèles pré-entraînés peuvent être trouvés sur TensorFlow Hub, et l'atelier guide sur la façon de les charger et de les utiliser pour l'apprentissage par transfert.

4. **Création de l'application** : L'atelier couvre la configuration d'une page HTML/CSS/JS, l'importation de TensorFlow.js, et la création d'une interface utilisateur pour activer la webcam et collecter des données.

5. **Entraînement et prédiction** : Le code permet de collecter des données d'images, d'entraîner un modèle avec ces données, et de faire des prédictions en temps réel sur des objets reconnus via la webcam.

6. **Réinitialisation et tests** : Une fonction de réinitialisation permet de purger les données et de recommencer l'entraînement. L'atelier encourage les tests avec différents objets pour évaluer la performance du modèle.

En conclusion, cet atelier permet d'apprendre à utiliser TensorFlow.js pour créer des applications de machine learning interactives dans le navigateur, en mettant l'accent sur l'apprentissage par transfert et la manipulation de modèles pré-entraînés.
## Links

1. [Teachable Machine](https://teachablemachine.withgoogle.com/) - A web-based tool that allows users to create machine learning models using their own data.
2. [TensorFlow.js](https://www.tensorflow.org/js?hl=fr) - An open-source library for machine learning in JavaScript, enabling the development of ML models in the browser.
3. [hub TensorFlow](https://tfhub.dev/s?deployment-format=tfjs) - A repository of pre-trained models that can be used with TensorFlow.js for various machine learning tasks.
4. [ImageNet](https://www.image-net.org/) - A large visual database designed for use in visual object recognition software research, often used for training models like MobileNet.
5. [TensorFlow.js, de zéro à héros](https://www.edx.org/course/google-ai-for-javascript-developers-with-tensorflowjs) - A comprehensive course that teaches the fundamentals of TensorFlow.js and how to apply it in JavaScript development.
## Topics

- [[topics/Library/TensorFlow]]
- [[topics/Model/MobileNet]]
- [[topics/Concept/Transfer Learning]]
- [[topics/Platform/Teachable Machine]]
- [[topics/Concept/One-Hot Encoding]]