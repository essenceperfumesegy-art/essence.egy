const inventory = [
    { id: 1, name: "Midnight Rose", price: 120.00, img: "product1 (26).png" },
    { id: 2, name: "Oceanic Mist", price: 95.00, img: "product1 (33).png" },
    { id: 3, name: "Amber Wood", price: 145.00, img: "product1 (13).png" }
];

let cart = [];

function renderProducts() {
    const list = document.getElementById('product-list');
    list.innerHTML = "";
    inventory.forEach(p => {
        list.innerHTML += `
            <div class="product-card">
                <img src="${p.img}" alt="${p.name}">
                <h3>${p.name}</h3>
                <p>$${p.price.toFixed(2)}</p>
                <button class="cta-button" onclick="addToCart(${p.id})">Add to Cart</button>
            </div>
        `;
    });
}

function addToCart(id) {
    const item = inventory.find(p => p.id === id);
    cart.push(item);
    document.querySelector('.cart-icon').innerText = `🛒 Cart (${cart.length})`;
    alert(`${item.name} added to your bag!`);
}

function toggleCart() {
    if (cart.length === 0) return alert("Your cart is currently empty.");
    const total = cart.reduce((sum, item) => sum + item.price, 0);
    const confirmOrder = confirm(`Your subtotal is $${total.toFixed(2)}. Proceed to checkout?`);
    
    if (confirmOrder) {
        alert("Success! Your order has been placed. Thank you for choosing Essence.");
        cart = [];
        document.querySelector('.cart-icon').innerText = `🛒 Cart (0)`;
    }
}

renderProducts();
