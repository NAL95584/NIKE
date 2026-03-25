// Simulation d'importation des données JSON
const data = {
  "products": [
    { "name": "Nike Air Max", "price": "149€", "image": "https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=400" },
    { "name": "Veste Tech", "price": "89€", "image": "https://images.unsplash.com/photo-1591047139829-d91aecb6caea?w=400" },
    { "name": "Runner Pro", "price": "110€", "image": "https://images.unsplash.com/photo-1491553895911-0055eca6402d?w=400" }
  ]
};

const grid = document.getElementById('product-grid');

data.products.forEach(product => {
    grid.innerHTML += `
        <div class="product-card">
            <img src="${product.image}" alt="${product.name}">
            <h3>${product.name}</h3>
            <p style="color: #0052cc; font-weight: bold;">${product.price}</p>
            <button>Ajouter au panier</button>
        </div>
    `;
});
