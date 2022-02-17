Utilitzar el codi que hem implementat és molt intuitiu, a més, 
està tot explicat en el mateix jupyter notebook.

Tot i així, escrivim una petita guia.

Hem dividit el codi per seccions:
1) Un script llarg per calcular l'error de reconstrucció en datasets 2D 
per qualsevol dels 3 kernels.
2) Un script que fa els plots per PCA i KPCA.
3) El codi emprat (main) per fer tots els càlculs necessaris per cada toy dataset 
utilitzat que crida a les funcions de l'script 1).
4) Un script per calcular l'error de reconstrucció en datasets 4-D (real dataset)
5) El codi main per fer tots els càlculs d'aquest dataset real.


Per utilitzar aquest codi només hem de canviar els valors dels kernels o 
hiper-paràmetres (tant els dels kernels com per exemple el numero de particions K).
I aplicar els steps descrits al jupyter notebook en més detall.