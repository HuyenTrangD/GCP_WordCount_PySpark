# WordCount avec GCP et PySpark

__Auteur__: Killian Raoux  
__Date de création__: 2023-07-25  
__Présentation__: Ce notebook permet de compter le nombre d'occurence de chaque mot dans un text. Il utilise pour cela 
pyspark.

__Prérequis__: Un bucket gcp pour le stockage des données. (BUCKET_NAME)  
__Inputs__: texte d'entrée: `gs://{BUCKET_NAME}/input/{INPUT_FILE_NAME}`  
__Outputs__: csv de sortie: `gs://{BUCKET_NAME}/output/{OUTPUT_FILE_NAME}`

__Params__:
- `BUCKET_NAME`: nom du bucket GCP. DOIT être dans le même projet.
- `INPUT_FILE_NAME`: nom du fichier a traiter. DOIT être au format "txt"
- `OUTPUT_FILE_NAME`: nom du fichier de sortie contenant le résulta.
