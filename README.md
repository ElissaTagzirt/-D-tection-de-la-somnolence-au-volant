Ce projet vise à développer un système icapable de détecter la somnolence chez les conducteurs en temps réel, à partir d’images vidéo. Il combine des approches de vision par ordinateur et d’apprentissage automatique, notamment :

L’analyse des traits du visage (yeux, bouche, inclinaison de la tête) via le modèle shape_predictor_68_face_landmarks.dat

Le calcul du rapport d’aspect des yeux (EAR) et de la bouche (MAR) pour détecter les signes de fatigue

L’estimation de l’inclinaison de la tête grâce à la résolution du problème PnP

L’utilisation d’un CNN pour extraire des caractéristiques visuelles à partir d’images de visages

L’entraînement d’un SVM pour classer les états somnolents ou vigilants

Une phase finale de prédiction et affichage en temps réel via webcam ou vidéos embarquées
