# Matériel pédagogique pour l'UV MT94 P25.

Les fichiers de cet entrepôt sont destinés à être diffusés aux étudiants en utilisant `nbgitpuller` (https://nbgitpuller.readthedocs.io/en/latest/).

Par exemple, pour diffuser le fichier `exemples/acp_iris.ipynb` à des utilisateurs du jupyter hub de MT94 l'URL à transmettre est (il existe une extension Firefox pour générer automatiquement cet URL, voir https://addons.mozilla.org/en-US/firefox/addon/nbgitpuller-link-generator/) : 

https://jupyterhub-mt94.utc.fr/hub/user-redirect/git-pull?repo=https://github.com/mottelet/mt94&urlpath=lab/tree/mt94/exemples/acp_iris.ipynb&branch=main

Pour les utilisateurs utilisant un serveur jupyterlab local sur leur machine, il faudra plutôt leur donner l'URL suivant :

https://localhost:8888/git-pull?repo=https://github.com/mottelet/mt94&urlpath=lab/tree/mt94/exemples/acp_iris.ipynb&branch=main

Important à savoir : les modifications locales faites sur les fichiers ainsi téléchargés ne sont pas affectées si l'URL est chargé ultérieurement (voir https://nbgitpuller.readthedocs.io/en/latest/topic/automatic-merging.html)

