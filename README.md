# IB_EXPRESS_EXO

class User {
    id: number
    nom: string
    prenom: string
    date_de_naissance?: string
    date_inscription: Date
    nationalite?: string
}

A partir de cette classe, définir une API permettant de gérer les
contraintes:
-la date de naissance et la nationalité sont facultatives
-la date de l'inscription doit être au format d/M/Y hh:mm:ss
