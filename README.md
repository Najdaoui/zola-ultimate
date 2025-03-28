![Codexa Solutions Logo](https://www.codexa.ma/logo.png)

# Zola Ultimate

**Correcteur Typographique Intelligent pour le Français**  
*« Une solution élégante pour une typographie impeccable »*

## ✨ Fonctionnalités

### 🔠 Correction automatique
- Espaces insécables avant `: ; ? ! » «`
- Protection des mots clés (`et`, `à`, `ou`, `où`, etc.)
- Gestion des majuscules (`À`, `Et`, `Où`)
- Combinaisons spéciales (`et les`, `et un`, `et une`)

### ⚡ Performance
- Deux modes de fonctionnement :
  - **Mode Léger** : <150 nœuds texte
  - **Mode Complet** : Optimisations avancées
- Surveillance intelligente du DOM
- Détection automatique du contenu dynamique

## 🚀 Installation

### Via CDN
```
<script src="https://cdn.jsdelivr.net/gh/codexa/zola-ultimate@latest/dist/zola.min.js"></script>
```

### Module ES6
```
import zola from 'zola-ultimate';
zola();
```

### ⚙️ Configuration
```
window.ZolaConfig = {
  // Personnaliser la ponctuation
  ponctuation: [':', ';', '?', '!', '»', '«', '›', '‹'],
  
  // Ajouter des mots protégés
  motsProteges: ['et', 'à', 'ou', 'où', 'la', 'le', 'les', 'un', 'une', 'des'],
  
  // Options avancées
  seuilComplexite: 150,  // Nombre de nœuds pour activer le mode complet
  delaiMutation: 50      // Délai de traitement des mutations (ms)
};
```
### 📚 Exemples d'Utilisation

Texte simple :

```<p>« Bonjour : voici un test; avec et des éléments à vérifier! Où sont la leçon et les règles ? » À un moment, ou peut-être à une heure, des questions se posent où la clarté et le style sont importants.</p>```

outerHTML :

```<p>« Bonjour&nbsp;: voici un&nbsp;test; avec et&nbsp;des&nbsp;éléments à&nbsp;vérifier! Où&nbsp;sont la&nbsp;leçon et&nbsp;les&nbsp;règles&nbsp;?&nbsp;» À&nbsp;un&nbsp;moment, ou&nbsp;peut-être à&nbsp;une&nbsp;heure, des&nbsp;questions se posent où&nbsp;la&nbsp;clarté et&nbsp;le&nbsp;style sont importants.</p>```

## 📊 Compatibilité

| Navigateur    | Version minimale |
|--------------|------------------|
| Chrome       | 60+              |
| Firefox      | 55+              |
| Safari       | 12+              |
| Edge         | 15+              |
| iOS Safari   | 12+              |

## 📜 Licence
MIT License - © Codexa Solutions

<div> <img src="https://www.codexa.ma/signature.png" alt="Signature Codexa" width="48"/> <p>Développé avec ❤️ par <a href="https://www.codexa.ma">Codexa Solutions</a></p> </div> ```
