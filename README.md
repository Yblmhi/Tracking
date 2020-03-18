# Training
Les photos training sont dans le dossier habilement appelé training, neg pour négatif et pos pour positif
Les deux pool et pool2 sont les vidéos (habile !)





# deep learning face detection
C'est le code qui marche sur les visages, tu peux tester avec ta web cam 
=> python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

ça marche juste avec opencv qui a un outil pour les reseaux de neurones intégré.

J'ai pas réussi a utiliser un autre set de données fait avec caffe dans le même code mais c'est ptetre juste 
que je suis trop con




# People counter
C'est un compteur de gens en vue de dessus, c'est pas tout a fait ce qu'on cherche mais je me suis dit que on peut
ptet réutiliser le dataset qui est un truc assez global je crois mais je sais pas trop comment ça fonctionne ces 
choses là... En tout cas il reconnaît pas de gens sur mes vidéos :)
