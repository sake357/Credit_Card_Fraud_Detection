En este caso tenemos que realizar un modelo que detecte las tarjetas de creditos fraudulentas, sin embargo, la misma naturaleza del problema nos obliga a tratar con herramientas
no convencionales como SMOTE o SMOTEENN, que estos dos tratan datos desbalanceados como el oversamping.
Se va a comparar los resultados utilizando SMOTE, SMOTEENN y sin utilizar ninguno.
Explicar como funciona cada uno, y se va a ejecutar utilizando modelos de clasificación:
RandomForestClassifier, GradientBoostingClassifier
LogisticRegression, SGDClassifier
GaussianNB, BernoulliNB, MultinomialNB
KNeighborsClassifier
MLPClassifier
Se va a ejecutar y los 3 modelos mejores se va a utilizar para predecir la data test.
En este proceso va a pasar por todas las etapas de analisis exploratorio, engineer features, armado de modelo, comprobación,etc.
