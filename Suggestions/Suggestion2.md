+annonce `<channel>`  

## **Caractéristiques:**  
le placeholder `<channel>` permet au bot de savoir ou poster le message final.  
L'utilisateur peut faire des sauts de lignes dans la condition 2 a l'aide de `\n` ou autres.

## **Messages**  
*les conditions sont des messages type `+sanction` (étape par étape)*  
#### CONDITION 1 : Envoyé a l’exécution de la commande `+annonce <channel>`:  
> **Création d'une annonce (1/4)**  
> vous avez choisi le salon `<channel choisi par l'utlisateur>`,  
>   
> Veuillez choisir un titre pour votre annonce.  
>   
> Pour annuler l'envoi de cette annonce, cliquez sur la réaction :no_entry:  
> LOGO.png `utilisateur ayant demandé la commande` • `date`  
*émoji annuler l'annonce :no_entry:*  

#### CONDITION 2 : Envoyé quand la condition 1 est remplie
> **Création d'une annonce (2/4)**  
> Le titre de l'annonce que vous avez choisi est `<titre choisi>`. 
>    
> Veuillez maintenant entrer une description.  
>    
> Pour annuler l'envoi de cette annonce, cliquez sur la réaction :no_entry:  
> LOGO.png `utilisateur ayant demandé la commande` • `date`  
*émoji annuler l'annonce :no_entry:*  

#### CONDITION 3 : Envoyé quand la condition 2 est remplie.  
> **Création d'une annonce (3/4)** 
> La description de l'annonce est maintenant prise en compte.  
>   
> Veuillez entrez le/les liens compris dans l'annonce.  
> Merci de les séparer a l'aide de virgules.  
>    
> Pour annuler l'envoi de cette annonce, cliquez sur la réaction :no_entry:  
> Exemple: `https://lien1.com/, https://www.lien2.org/, https://www.lien3.net/`  
> LOGO.png `utilisateur ayant demandé la commande` • `date`  
*émoji annuler l'annonce :no_entry:*  

#### CONDITION 4 : Envoyé quand la condition 3 est remplie.  
> **Création d'une annonce (4/4)**  
> Les liens entrés ont bien été pris en compte et sont:  
> `<liste des liens entrés par l'utilisateur>`  
>   
> Veuillez maintenant confirmer votre annonce en tapant `confirmer`  
>   
> Pour annuler l'envoi de cette annonce, cliquez sur la réaction :no_entry:  
> LOGO.png `utilisateur ayant demandé la commande` • `date`  
*émoji annuler l'annonce :no_entry:*  

#### CONDITION 5 : Envoyé quand la condition 4 est remplie.  
Veuillez confirmer l'envoi de cette annonce, cette action est irréversible !
Attention, tout le serveur sera ping a l'aide de `@everyone`.
> **`<titre de l'annonce entré par l'utilisateur>`**  
> `<descrition entré par l'utilisateur, comprend les sauts de lignes>`  
> `<liste des liens>`  
> LOGO.png `L'équipe de Furiozia` • `date`  
*émoji annuler l'annonce :no_entry:* et *émoji envoyer l'annonce :white_check_mark:*

#### CONDITION 6 : Envoyé quand la condition 5 est remplie. (modification du message envoyé aka condition 5)
> **Annonce envoyée**
> L'annonce que vous avez créee a été envoyée dans le salon `<channel>`.
> LOGO.png `utilisateur ayant demandé la commande` • `date`  
