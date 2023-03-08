# -*- coding: utf-8 -*-
"""
Created on Sat Dec 24 17:52:53 2022

@author: THOCHIBA
"""



L1=[]
class Etudiants:
    #identifier etudiant
    def __init__(self,nom,prenom,cin,cne,Etablissement,Filiere):
        self.nom = nom;
        self.prenom = prenom;
        self.cin= cin;
        self.cne = cne;
        self.etablissement = Etablissement;
        self.filiere = Filiere;
            
        
    def Note(self):
        #Identifier Mention et Validation  dans EST
        if (self.etablissement == "est"):
            semester1 = float(input("donnez la note de semester 1 :"))
            semester2 = float(input("donnez la note de semester 2 :"))
            semester3 = float(input("donnez la note de semester 3 :"))
            semester4 = float(input("donnez la note de semester 4 :"))
            note = (((semester1 + semester2)/2) +((semester3 + semester4))/2)/2
         
            for i in (0,note):
                if note < 12 :
                    mention = "faible"
                elif note == 12 :
                    mention = "passable"
                elif note > 12 and note <14 :
                    mention = "assez bien"
                elif note >= 14 and note <16 :
                    mention = "bien"
                elif note >= 16 and note <20 :
                    mention = "tres bien"
                elif note == 20 :
                    mention = "excelent"
                else:
                    print("la note doit etre entre  0 and20 ")
                    
            print(mention)    
                
            if note > 12 :
                validation = "validée"
            else :
                validation = "non validée"
            print(validation, "votre note :", note)
            
            
        #Identifier Mention et Validation  dans FS:
        elif self.etablissement == "fs" :
            semester1 = float(input("donnez la note de semester 1 :"))
            semester2 = float(input("donnez la note de semester 2 :"))
            semester3 = float(input("donnez la note de semester 3 :"))
            semester4 = float(input("donnez la note de semester 4 :"))
            semester5 = float(input("donnez la note de semester 5 :"))
            semester6 = float(input("donnez la note de semester 6 :"))
            note = (((semester1 + semester2)/2) +((semester3+ semester4)/2)+((semester5+ semester6)/2))/3
            
            for i in (0,note):
                
                if note < 10 :
                    mention = "faible"
                elif note == 10 :
                    mention = "passable"
                elif note > 10 and note <12 :
                    mention = "assez bien"
                elif note >= 12 and note <14 :
                    mention = "bien"
                elif note >= 14 and note <17 :
                    mention = "très bien"
                elif note >=17 and note<=20 :
                    mention = "excelent"
                else:
                    print("la note doit etre entre  0 and20 ")
            print(mention)
            
            if note > 10 :
                validation = "validée"
            else :
                validation = "non validée"                
            print(validation, "votre note :", note)
        #Identifier Mention et Validation  dans ENSA
        elif self.etablissement == "ensa" :
            semester1 = float(input("donnez la note de semester 1 :"))
            semester2 = float(input("donnez la note de semester 2 :"))
            semester3 = float(input("donnez la note de semester 3 :"))
            semester4 = float(input("donnez la note de semester 4 :"))
            semester5 = float(input("donnez la note de semester 5 :"))
            semester6 = float(input("donnez la note de semester 6 :"))
            semester7 = float(input("donnez la note de semester 7 :"))
            semester8 = float(input("donnez la note de semester 8 :"))
            semester9 = float(input("donnez la note de semester 9 :"))
            semester10 = float(input("donnez la note de semester 10 :"))
    
            note = (((semester1 + semester2)/2) +((semester3 + semester4))/2+((semester5 + semester6))/2+((semester7 + semester8))/2+((semester9 + semester10))/2)/5
            
            for i in (0,note):
                
                if note < 10 :
                    mention = "faible"
                elif note == 10 :
                    mention = "passable"
                elif note > 10 and note <12 :
                    mention = "assez bien"
                elif note >= 12 and note <14 :
                    mention = "bien"
                elif note >= 14 and note <17 :
                    mention = "très bien"
                elif note >17 and note<=20:
                    mention = "excelent"
                else:
                    print("la note doit etre entre  0 and20 ")
            print(mention)
            
            if note > 10 :
                validation = "validée"
            else :
                validation = "non validée"
            print(validation, "votre note :", note)

                
       
        
    #Afficher les informations de l'étudiant
    def Afficher(self):
        print("Nom et prenom : "+self.nom +" "+ self.prenom +"\n"+"Etablissement : "+self.etablissement +"\n"+"Filière : "+self.filiere);
    #Méthode rechercher pour faire une recherche d'un étudiant
    def Rechercher(v_cne):
        #Liste pour trouver CNE de l'etudiant souhaité
        for i in range(len(L1)):
            if(v_cne == L1[i].cne):
                print("Nom : "+ L1[i].nom + "\n" +"Prenom :" + L1[i].prenom + "\n" +"CIN :"+ L1[i].cin + "\n" +"CNE : "+ L1[i].cne + "\n" +"Etablissement : "+ L1[i].etablissement + "\n" +"Filière : "+ L1[i].filiere)
    def Modifier(v_cne):
        #Modification les champs saisie par l'utilisateur
        for i in range(len(L1)):
            if(v_cne == L1[i].cne):
                L1[i].nom = input("Saisir le nouveau nom : ")
                L1[i].prenom = input("Saisir le nouveau Prénom : ")
                L1[i].etab = input("Saisir l'etablissement : ")
                L1[i].filiere = input("Saisir la filière : ")
                print("Nom : "+ L1[i].nom + "\n" +"Prenom :" + L1[i].prenom + "\n" +"CIN :"+ L1[i].cin + "\n" +"CNE : "+ L1[i].cne + "\n" +"Etablissement : "+ L1[i].etablissement + "\n" +"Filière : "+ L1[i].filiere)
    
        

#Exemples
Etudiant1 = Etudiants("Sara","AL MOURABETI","SB16484","H139108152","est","GIGD")
Etudiant1.Afficher()
Etudiant1.Note()

Etudiant2 = Etudiants("Anas","EL Maaroufy","hueihe","hdjd","fs","Info")
Etudiant2.Afficher()
Etudiant2.Note()

Etudiant3 = Etudiants("Ikrame","Omara","Tihojse","djvikds","ensa","GI")
Etudiant3.Afficher()
Etudiant3.Note()


L1.append(Etudiants("Meriam","ANGHMER","SB48486","Hhijjv2","est","GIGD"))
L1.append(Etudiants("Najlae","Nibou","AA7785","468468","FS","Info"))
L1.append(Etudiants("farah","AL MOURABETI","T37779","S6765412","ENSA","GI"))


#Rechercher un étudiant :avec son CNE 
Etudiants.Rechercher("Hhijjv2");
#Modifier un étudiant avec son CNE 
Etudiants.Modifier("S6765412");