Ce repository constitue un travail sur le finetuning de données : 
  - le premier est sur du finetuning des dialogue entre médecins et patiens (les fichiers numérotés de 1 à 5). Ces fichiers doivent être run dans l'ordre afin d'obtenir à la fin un modèle finetuné. 
  - le second est sur du finetuning de résumés d'articles (summarization.ipynb)

Le fichier "GGUF" a été ajouté pour réaliser la conversion d'un modèle huggingface en fichier GGUF, indispensable pour le faire ensuite tourner sur des applications comme JAN ou encore LM Studio

Le fichier "rag-langchain-llama-3" constitue un rag qui peut être utilisé avec nos modèles finetunés enregistrés sur huggingface ou bien sur des modèles déjà existants comme llama3. 

Le fonctionnement de tous ces codes nécessitent la création d'un compte sur huggingface mais aussi d'un compte sur wandb pour le suivi du finetuning. 
