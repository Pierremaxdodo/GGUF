Ce repository constitue un travail sur le fine-tuning de données :

Le premier est sur le fine-tuning des dialogues entre médecins et patients (les fichiers numérotés de 1 à 5). Ces fichiers doivent être exécutés dans l'ordre afin d'obtenir à la fin un modèle fine-tuné.
Le second est sur le fine-tuning de résumés d'articles (summarization.ipynb).
Le fichier "GGUF" a été ajouté pour réaliser la conversion d'un modèle Huggingface en fichier GGUF, indispensable pour le faire ensuite tourner sur des applications comme JAN ou encore LM Studio.

Le fichier "rag-langchain-llama-3" constitue un RAG qui peut être utilisé avec nos modèles fine-tunés enregistrés sur Huggingface ou bien sur des modèles déjà existants comme LLaMA 3. Il y a aussi un RAG basé sur DSPY et non Langchain comme celui mentionné précédemment. Nous pouvons aussi nous appuyer sur les codes fournis dans la présentation de GitHub de DSPY sur le lien suivant : https://github.com/stanfordnlp/dspy?tab=readme-ov-file#2-documentation. 

Le fonctionnement de tous ces codes nécessite la création d'un compte sur Huggingface mais aussi d'un compte sur W&B (Weights & Biases) pour le suivi du fine-tuning.
