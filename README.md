# Template Pied de Vigne

Template avec header, bannière, menu de navigation, barre de recherche, section main et footer.

## Convention de codage

Nom de classes (sélecteurs CSS) en kebab-case.

Plusieurs niveaux dans les paramètres :
- Position,
- Display,
- Taille,
- Divers (couleurs, etc...),
- Bordures.

Exemple :
```css
.panier {
  position: relative;

  display: flex;
  justify-content: center;
  align-items: center;

  width: auto;
  height: 40px;

  color: #000;
  background-color: #fff;
  padding: 10px;
  text-decoration: none;

  border: 1px solid #fff;
  border-radius: 5px;
}
```
