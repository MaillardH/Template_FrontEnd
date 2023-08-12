Ce dossier contient tous les composants réutilisables de l'application 
Chaque composant peut être placé dans son propre sous-dossier, avec son fichier 
JavaScript/JSX et éventuellement des fichiers CSS, des images, etc.

On utilise généralement les suffixes suivants:
    List, Item, Form, Button, Modal, etc. 

Par exemple : ProductList, UserForm, LoginButton, CartItem

// Bon
import UserProfile from './UserProfile';
import ProductList from './ProductList';
import CartItem from './CartItem';

// Évitez
import UserProf from './UserProf';
import ProdList from './ProdList';
import CItem from './CItem';

Genre > 

components > Header > 
                ----- Header.jsx
                ----- Header.css
           > UserProfile > 
                ----- UserProfile.jsx 
                ----- UserProfile.css
                ----- tous les images
