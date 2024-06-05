; Application de Gestion des Notes dévloppé par Franchini Jade 

; ============Architecture du projet============

; L'architecture se compose comme suit, dans le dossier GestionNotes/src/Class:

;       1) Classe : Gère les informations sur les classes (identifiants, nom, niveau).
;       2) Eleve : Gère les informations sur les élèves (identifiant, nom, prenom, classe associée).
;       3) Enseignant : Gère les informations sur les enseignants (identifiant, nom, prenom, spécialité enseignée, identifiant classe, identifiant matière).
;       4) Matiere : Gère les informations sur les matières (identifiant, nom).
;       5) Note : Gère les informations sur les notes (identifiant, identifiant élève, identifiant matière, valeur).
;       6) Main : point d'entrée de l'application. Il affiche un menu qui permet d'effectuer différentes opérations sur les classes. 


; ============Menu interactif============

; Ce menu vous permet, sur différents éléments, de:
;       - Create (Créer)
;       - Read (Lire)
;       - Update (Mettre à jour)
;       - Delete (Effacer)
;       

; ============Fonction Class Main============ 

; 1) main(String[] args) :
; Fonction d'entrée de l'application

; 2) afficherMenu() :
; Affiche le menu principal à l'utilisateur.
; Le menu présente les différentes options disponibles pour l'utilisateur.

; 3) afficherSousMenu() :
; Le sous-menu présente les différentes options disponibles pour l'utilisateur en fonction du menu selectionné.

; 4) fonctMenu(int) :
; Redirectionne l'utilisateur vers le sous-Menu sélectionné

; 5) fonctSousMenu(int) :
; Actionne la fonction sélectionnée par l'utilisateur dans le sous-menu

; 6) lister/Class/() : 
; Permet d'afficher la liste de tous les éléments présents dans la liste. 

; 7) creer/Class/() :
; Permet de créer un nouvel élément dans la liste. 

; 8) supprimer/Class/() : 
; Permet de supprimer un élément dans la liste en fonction de son ID. 

; 9) mettreAJour/CLass/() : 
; Permet de modifier les informations d'un élément de la liste en fonction de son ID. 
