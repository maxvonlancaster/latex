L'extension  tablor.sty permet  de cr�er  des tableaux  de signes  et de
variations depuis latex  en utilisant XCAS pour les  calculs et MetaPOST
pour les tableaux.

On rentre par exemple:

\begin{TV} TV([-10,+infinity],[-1,1],"g","t",x^2/(x^2-1),1,n,\tv) \end{TV} 

et on obtient le tableau de variation de x->x^2/(x^2-1). 

Les tableaux sont construits  � partir du fichier tableauVariation.mp de
Fr�d�ric Mazoit disponible � l'adresse 

http://frederic.mazoit.free.fr/LaTeX_metapost/tableauVariations/

XCAS est t�l�chargeable � l'adresse :

http://www-fourier.ujf-grenoble.fr/%7Eparisse/giac_fr.html


Les appels � giac ont �t� am�lior�s gr�ce � Yves Delhaye :

http://www.yvesdelhaye.be/?Generateur-d-interrogations-le


Il faut activer le shell-escape.


