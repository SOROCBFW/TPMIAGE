https://github.com/SOROCBFW/TPMIAGE.git
README.txt

TP noté:FONDAMENTAUX DE LA POO

NOM: SORO
PRENOM: MOUROULAYE ADAMA
CLASSE: L2 B

EXPLICATION:


Ce projet est une console multi-service qui peut permettre a une entrepise de location de vehicule de gérer un parc automobile.
A partir de la console celle-ci pourra mener plusieurs taches comme:
                    - Ajouter des vehicules 
                    - Ajouter des clients
                    - Gerer les locations et les retours des vehicules
                    - avoir une idée du statut des vehicules(Disponible ou loué)
      tous cela dans une liste bien ordonnée.

le programme est également contitué de plusieurs classes a savoir:
                    -la classe vehicule(classe mere) consitué de plusieurs attributs caractérisant un vehicule et aussi de méthodes telles que:
                       o- une methode pour calculer le prix de la location 
                       o- une methode pour louer un vehicule 
                       o- une methode pour retourner un vehicule loué aupparavant
                       o- une methode pour afficher les details du vehicule choisi par l'utilisateur
                       o- une methode pour verifier si le permis est valide ou non(lorqu'un client veut louer un camion)
                    -la classe voiture(classe premiere classe fille) qui herite de certains attributs de la classe Vehicule
                    -la classe camion camion qui herite également de la classe vehicule ainsi que de voiture
                    - une classe Client avec des attributs tels que : nom, prénom, numéro de permis de conduire, numéro de téléphone aussi une liste(ArrayList) des locations en 
cours. 
le programme est aussi constitué d'exceptions "VehiculeIndisponibleException" lorsqu'un véhicule est déjà loué ou "ClientNonAutoriseException" si un client tente de louer un camion sans 
permis adéquat.

Enfin le programme comprend aussi un menu interactif ou l'on poura saisir toutes les informations necessaire concernant un vehicule a louer et sur le client y compris.
