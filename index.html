```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Dressing Virtuel</title>
</head>
<body>
    <h1>Mon Dressing Virtuel</h1>
    
    <div id="upload-section">
        <h2>Ajouter des vêtements</h2>
        <input type="file" id="file-input" accept="image/*" multiple>
        <button id="upload-button">Télécharger</button>
    </div>
    
    <div id="categories">
        <h2>Mes Vêtements</h2>
        <div id="clothes-list"></div>
    </div>
    
    <div id="virtual-dressing">
        <h2>Dressing Virtuel</h2>
        <div id="model">
            <img id="head" src="" alt="Tête" />
            <img id="torso" src="" alt="Torso" />
            <img id="legs" src="" alt="Jambes" />
            <img id="shoes" src="" alt="Pieds" />
        </div>
        <div id="controls">
            <button id="prev-head">⬅️</button>
            <button id="next-head">➡️</button>
            <button id="prev-torso">⬅️</button>
            <button id="next-torso">➡️</button>
            <button id="prev-legs">⬅️</button>
            <button id="next-legs">➡️</button>
            <button id="prev-shoes">⬅️</button>
            <button id="next-shoes">➡️</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
```

### 3. Code CSS (styles.css)

```css
body {
    font-family: Arial, sans-serif;
    text-align: center;
}

#upload-section, #categories, #virtual-dressing {
    margin: 20px;
}

#model {
    position: relative;
}

#model img {
    position: absolute;
}

#controls button {
    margin: 5px;
}
```

### 4. Code JavaScript (script.js)

```javascript
const fileInput = document.getElementById('file-input');
const uploadButton = document.getElementById('upload-button');
const clothesList = document.getElementById('clothes-list');

let clothes = {
    head: [],
    torso: [],
    legs: [],
    shoes: []
};

// Ajouter les vêtements à la liste
uploadButton.addEventListener('click', () => {
    const files = fileInput.files;
    
    for (let i = 0; i < files.length; i++) {
        const file = files[i];
        const reader = new FileReader();
        
        reader.onload = (function(file) {
            return function(e) {
                // Ici, vous pouvez trier les vêtements par catégorie
                // Pour simplifier, je vais les ajouter à toutes les catégories
                clothes.head.push(e.target.result);
                clothes.torso.push(e.target.result);
                clothes.legs.push(e.target.result);
                clothes.shoes.push(e.target.result);
                
                updateClothesList();
            };
        })(file);
        
        reader.readAsDataURL(file);
    }
});

// Mettre à jour la liste de vêtements
function updateClothesList() {
    clothesList.innerHTML = '';
    for (const category in clothes) {
        clothesList.innerHTML += `<h3>${category.charAt(0).toUpperCase() + category.slice(1)}</h3>`;
        clothes[category].forEach((item, index) => {
            clothesList.innerHTML += `<img src="${item}" alt="Vêtement" style="width: 100px; height: auto;"/>`;
        });
    }
}

// Navigation entre les vêtements
let currentIndex = { head: 0, torso: 0, legs: 0, shoes: 0 };

function updateModel() {
    document.getElementById('head').src = clothes.head[currentIndex.head] || '';
    document.getElementById('torso').src = clothes.torso[currentIndex.torso] || '';
    document.getElementById('legs').src = clothes.legs[currentIndex.legs] || '';
    document.getElementById('shoes').src = clothes.shoes[currentIndex.shoes] || '';
}

document.getElementById('next-head').addEventListener('click', () => {
    currentIndex.head = (currentIndex.head + 1) % clothes.head.length;
    updateModel();
});

document.getElementById('prev-head').addEventListener('click', () => {
    currentIndex.head = (currentIndex.head - 1 + clothes.head.length) % clothes.head.length;
    updateModel();
});

// Répéter pour torso, legs et shoes...
```
