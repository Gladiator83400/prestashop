__PRESTASHOP__


(* Modification de la Boutique le 29.02.2022 *)


-------------------------------------------------



## Les fichiers à modifier


1.  Fichier theme.css pour modifier les couleurs de votre site. ( Web et Plus )


2.  Fichier head.tpl pour modifier la balise <head> de votre boutique et installer Google Tag Manager. ( Webbax )


3.  Fichier layout-both-columns.tpl pour modifier la balise <body> de votre boutique et installer la suite de Google Tag Manager.


----------------------------------------------------


(* Modification de la Boutique le 30.02.2022 *)


-----------------------------------------------------


# Pour modifier les couleurs de votre boutique suivez les étapes 



->Chemin racine->prestashop/modules/


1.  Copier et coller le *Dossier* ps_sreachbar



2.  Ex chemin->thèmes/classic/modules
    Tout dépend du thème que vous avez installé.



3.  Supprimer tous les fichiers à l'intérieur sauf ps_sreachbar.css
    (* Document de feuille de style en cascade *)
    
    

4.  Ouvrir le fichier supprimer les deux premières ligne 
    #header, #header, .header-top {
    Background-color: white;
    
    
---------------------------------------------------------------

    
# Modifier ensuite le fichier thèmes.css
    
    
---------------------------------------------------------------------  


Chemin->prestashop/thèmes/classic/assets/css/


1.Décompresser le fichier thèmes.css avec https://unminify.com/


   *Cliquez sur Browse pour télécharger votre fichier,
   
   *Récupérez le fichier thèmes.css et cliquez sur Unminify pour le décompresser
   
   *Download pour le récupérer et le remplacer par celui qui est déjà installé,
   
   *(solution mettre un underscore _ devant pour le garder par précaution.)
   
   
   ------------------------------------------------------------------------------------------
   
   
2.Ouvrir le fichier thèmes.css pour modifier le Header, Wrapper et Footer.  


  *Ligne 11068 Background : ( #fff ) choisir la couleur désirée Ex: extension ColorPick Eyedropper sur Google Chrome
  
  *Ligne 11230 Background : ( #f6f6f6 ) même procéder, n'oubliez pas le dièse
  
  *Ligne 10551 au bout du point virgule, cliquez, espace et entrez manuellement Background : ( code couleurs )
  
 
    
    
    
