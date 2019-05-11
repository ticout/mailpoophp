# mailpoophp
envoie de mail en poo php
Je vous propose ce code qui permettra d'envoyer un mail pour un tiers
il sera également possible d'y joindre des pièces jointes si il en existe
créer une class
elle y aura les propriétés data; boundary; boundary_alt; passage_ligne et un tableau qui contient les extensions autorisées
dans le contructeur nous accepterons une donnée (data) tels que "$_POST"
cette donnée comprendra le message en priorité
dans mon exemple elle contiendra également le sujet et le nom du destinataire 
surtout instancier les boundary et boudary alt dans la méthode "contruct"
dans une méthode on récupère les adresses mail du destinataire, ainsi que l'adresse de réponse (dans ce cas)
dans la méthode qui envoie le mail, on passe en paramêtre l'expéditeur, et les fichiers si il y en a sinon il sont à false
paramétrer le passage_ligne
assigner le header
assigner le message
ajouter les fichiers si il en existe
envoyer le mail
