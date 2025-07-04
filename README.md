
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DS Technologies | Solutions Technologiques Innovantes</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    <header>
        <div class="container header-container">
            <div class="logo">
                <!--<img src="dfh.png" alt="Logo DS Technologies">-->
                DS<span>Technologies</span></div>
            <nav>
                <ul>
                    <li><a href="#">Accueil</a></li>
                    <li><a href="#products">Produits</a></li>
                    <li><a href="#categories">Catégories</a></li>
                    <li><a href="#">Promotions</a></li>
                    <li><a href="#apropos">À propos</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="user-actions">
                <div class="search-bar">
                    <input type="text" placeholder="Rechercher...">
                </div>
                <button class="account-btn">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
                        <circle cx="12" cy="7" r="4"></circle>
                    </svg>
                </button>
                <button class="cart-btn">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="9" cy="21" r="1"></circle>
                        <circle cx="20" cy="21" r="1"></circle>
                        <path d="M1 1h4l2.68 13.39a2 2 0 0 0 2 1.61h9.72a2 2 0 0 0 2-1.61L23 6H6"></path>
                    </svg>
                    <span class="cart-count">0</span>
                </button>
            </div>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Solutions Technologiques Innovantes</h1>
            <p>Découvrez les dernières innovations technologiques pour améliorer votre quotidien et optimiser votre entreprise avec DS Technologies</p>
            <a href="#products" class="cta-button">Découvrir nos produits</a>
        </div>
    </section>

    <section class="services" id="services">
      <div class="container">
        <h2 class="section-title">Nos Services</h2>
        <div class="services-grid">
          <div class="service-card">
            <h3>Vente de Matériel Informatique</h3>
            <p>Ordinateurs, imprimantes, accessoires, composants et équipements électroniques fiables et de qualité.</p>
          </div>
          <div class="service-card">
            <h3>Maintenance & Réparation</h3>
            <p>Diagnostic, réparation rapide, entretien et optimisation de vos appareils informatiques et réseaux.</p>
          </div>
          <div class="service-card">
            <h3>Conception de Sites Web</h3>
            <p>Sites vitrines, e-commerce ou sur mesure, adaptés à vos besoins, avec un design moderne et responsive.</p>
          </div>
          <div class="service-card">
            <h3>Infographie & Sérigraphie</h3>
            <p>Création de logos, affiches, cartes de visite, t-shirts personnalisés et supports publicitaires.</p>
          </div>
          <div class="service-card">
            <h3>Formation & Accompagnement</h3>
            <p>Formations en bureautique, marketing digital, cybersécurité et assistance personnalisée.</p>
          </div>
          <div class="service-card">
            <h3>Domotique & Sécurité</h3>
            <p>Installation de systèmes de sécurité, vidéosurveillance, automatisation de bâtiments et objets connectés.</p>
          </div>
        </div>
      </div>
    </section>



    <section class="featured-products" id="products">
        <div class="container">
            <h2 class="section-title">Produits Vedettes</h2>
            <div class="product-grid">
                <div class="product-card" data-product-id="prod001">
                    <div class="product-img">
                        <img src="https://i.pinimg.com/736x/3b/c0/9a/3bc09aed5bd7ef4da6361246eb8e08e1.jpg?auto=format&fit=crop&w=300&q=80" alt="Ordinateur portable professionnel">
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Ordinateur Portable Pro X9</h3>
                        <p class="product-price">1299 €</p>
                        <button class="add-to-cart">Ajouter au panier</button>
                    </div>
                </div>
                <div class="product-card" data-product-id="prod002">
                    <div class="product-img">
                        <img src="https://i.pinimg.com/736x/35/82/5b/35825b53d0ff4a040ab2567c320cfe4c.jpg?auto=format&fit=crop&w=300&q=80" alt="Écran ultra-large">
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Écran Ultra-Large 32</h3>
                        <p class="product-price">499 €</p>
                        <button class="add-to-cart">Ajouter au panier</button>
                    </div>
                </div>
                <div class="product-card" data-product-id="prod003">
                    <div class="product-img">
                        <img src="https://i.pinimg.com/736x/d6/6e/ea/d66eeaf6317890424833dc09cad5bbfb.jpg?auto=format&fit=crop&w=300&q=80" alt="Serveur haute performance">
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Serveur Haute Performance</h3>
                        <p class="product-price">2499 €</p>
                        <button class="add-to-cart">Ajouter au panier</button>
                    </div>
                </div>
                <div class="product-card" data-product-id="prod004">
                    <div class="product-img">
                        <img src= "https://i.pinimg.com/736x/f9/2c/15/f92c15d097d2c8220d9b3a212ea8fd5c.jpg?auto=format&fit=crop&w=300&q=80" alt="Solution cloud entreprise">
                    </div>
                    <div class="product-info">
                        <h3 class="product-title">Solution Cloud Entreprise</h3>
                        <p class="product-price">899 €/an</p>
                        <button class="add-to-cart">Ajouter au panier</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="categories">
        <div class="container" id="categories">
            <h2 class="section-title">Nos Catégories</h2>
            <div class="category-grid">
                <div class="category-card">
                    <div class="category-img">
                        <img src="https://i.pinimg.com/736x/cc/51/57/cc515797b1ef76d8bfdf2221bd5ef1a1.jpg" alt="Matériel informatique">
                    </div>
                    <div class="category-overlay">Matériel Informatique</div>
                </div>
                <div class="category-card">
                    <div class="category-img">
                        <img src="https://i.pinimg.com/736x/2b/a2/9c/2ba29c620e03944902f182e748aa8abd.jpg" alt="Logiciels">
                    </div>
                    <div class="category-overlay">Logiciels</div>
                </div>
                <div class="category-card">
                    <div class="category-img">
                        <img src="https://i.pinimg.com/736x/87/10/05/871005a54223842c4b891d8864b67acb.jpg" alt="Solutions réseau">
                    </div>
                    <div class="category-overlay">Solutions Réseau</div>
                </div>
                <div class="category-card">
                    <div class="category-img">
                        <img src="https://i.pinimg.com/736x/ce/6d/33/ce6d3360255ea7510139e39561fbefc2.jpg" alt="Services cloud">
                    </div>
                    <div class="category-overlay">Services Cloud</div>
                </div>
            </div>
        </div>
    </section>

    <section class="about">
        <div class="container" id="apropos">
            <div class="about-content">
                <div class="about-img">
                    <img src="logo.jpg" alt="À propos de DS Technologies">
                </div>
                <div class="about-text">
                    <h2>À Propos de DS Technologies</h2>
                    <p>DS Technologies est une entreprise innovante spécialisée dans la fourniture de solutions technologiques de pointe pour les professionnels et les entreprises de toutes tailles.</p>
                    <p>Depuis notre création, nous nous engageons à offrir des produits et services de haute qualité qui répondent aux besoins évolutifs de nos clients dans un monde numérique en constante évolution.</p>
                    <p>Notre équipe d'experts passionnés travaille sans relâche pour identifier et proposer les meilleures solutions technologiques adaptées à chaque situation, qu'il s'agisse de matériel informatique, de logiciels spécialisés ou de services cloud avancés.</p>
                    <a href="#" class="cta-button">En savoir plus</a>
                </div>
            </div>
        </div>
    </section>

    <section class="newsletter">
        <div class="container">
            <h2>Restez Informé</h2>
            <p>Abonnez-vous à notre newsletter pour recevoir en avant-première nos offres exclusives, nos nouveaux produits et des conseils technologiques professionnels.</p>

            <form action="https://getform.io/f/byvymgza" method="POST" class="newsletter-form">
                <input type="text" name="nom" placeholder="Votre nom">
                <input type="email" name="email" placeholder="Votre adresse email">
                <button type="submit">S'abonner</button>               
            </form>
            <!--<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScgjNL9wiT5OuXdB1FVQjPVGM9G6qHeTOk-2LPLqjw5IZTs2g/viewform?usp=dialog" 
                    width="100%" height="700" frameborder="0" marginheight="0" marginwidth="0">
                Chargement…
            </iframe> -->

        </div>
    </section>

    <footer>
        <div class="container" id="contact">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>DS Technologies</h3>
                    <p>L'innovantion au coeur de vos besions informatique</p>
                    <div class="social-links">
                        <a href="https://www.facebook.com/profile.php?id=61565630347363">
                            <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
                            </svg>
                        </a>
                        <a href="#">
                            <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
                            </svg>
                        </a>
                        <a href="https://www.linkedin.com/company/ds-technologies-officiel/">
                            <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/>
                            </svg>
                        </a>
                        <a href="#">
                            <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>Liens Rapides</h3>
                    <ul>
                        <li><a href="#">Accueil</a></li>
                        <li><a href="#apropos">À propos</a></li>
                        <li><a href="#products">Produits</a></li>
                        <li><a href="#">Services</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Catégories</h3>
                    <ul>
                        <li><a href="#">Matériel Informatique</a></li>
                        <li><a href="#">Logiciels</a></li>
                        <li><a href="#">Solutions Réseau</a></li>
                        <li><a href="#">Services Cloud</a></li>
                        <li><a href="#">Cybersécurité</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Contact</h3>
                    <ul>
                        <li><a href="mailto:contact.dstechnologies@gmail.com">contact.dstechnologies@gmail.com</a></li>
                        <li><a href="https://wa.me/22666022525">Whatsapp</a></li>
                        <li>Burkina Faso, Ouagadougou</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 DS Technologies. Tous droits réservés.</p>
            </div>
        </div>
    </footer>

    <!-- Intégration de Stripe -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://js.stripe.com/v3/"></script>
    <script>
        // Configuration Stripe - À remplacer avec votre clé publique réelle
        const stripe = Stripe('pk_test_51RLXzmFJPwNQhFmnQYIBXD7XURd22oUnZYhjEuMkdXmLBrZoIMA8OaOFM6uh23qHZ4n3c6brwhY36JsZcL8LXow300lrZTd9We');
        const elements = stripe.elements();
        
        // Système de panier
        document.addEventListener('DOMContentLoaded', function() {
            const addToCartButtons = document.querySelectorAll('.add-to-cart');
            const cartCount = document.querySelector('.cart-count');
            
            // Panier stocké en localStorage
            let cart = JSON.parse(localStorage.getItem('dstech_cart')) || [];
            
            // Mettre à jour le compteur
            function updateCartCount() {
                const count = cart.reduce((total, item) => total + item.quantity, 0);
                cartCount.textContent = count;
            }
            
            // Initialiser le compteur
            updateCartCount();
            
            // Ajouter au panier
            addToCartButtons.forEach(button => {
                button.addEventListener('click', function() {
                    const productCard = this.closest('.product-card');
                    const productId = productCard.getAttribute('data-product-id') || Math.random().toString(36).substr(2, 9);
                    const productTitle = productCard.querySelector('.product-title').textContent;
                    const productPrice = parseFloat(productCard.querySelector('.product-price').textContent.replace(/[^0-9.-]+/g,""));
                    const productImgSrc = productCard.querySelector('.product-img img').getAttribute('src');
                    
                    // Vérifier si le produit est déjà dans le panier
                    const existingProductIndex = cart.findIndex(item => item.id === productId);
                    
                    if (existingProductIndex > -1) {
                        cart[existingProductIndex].quantity += 1;
                    } else {
                        cart.push({
                            id: productId,
                            title: productTitle,
                            price: productPrice,
                            image: productImgSrc,
                            quantity: 1
                        });
                    }
                    
                    // Enregistrer le panier et mettre à jour l'affichage
                    localStorage.setItem('dstech_cart', JSON.stringify(cart));
                    updateCartCount();
                    
                    // Notification
                    const notification = document.createElement('div');
                    notification.style.position = 'fixed';
                    notification.style.bottom = '20px';
                    notification.style.right = '20px';
                    notification.style.backgroundColor = '#0066cc';
                    notification.style.color = 'white';
                    notification.style.padding = '15px';
                    notification.style.borderRadius = '5px';
                    notification.style.zIndex = '1000';
                    notification.textContent = `${productTitle} ajouté au panier !`;
                    
                    document.body.appendChild(notification);
                    
                    setTimeout(() => {
                        notification.remove();
                    }, 3000);
                });
            });
            
            // Afficher le panier lorsqu'on clique sur l'icône
            const cartBtn = document.querySelector('.cart-btn');
            cartBtn.addEventListener('click', function() {
                showCart();
            });
            
            function showCart() {
                // Créer la modal du panier
                const cartModal = document.createElement('div');
                cartModal.style.position = 'fixed';
                cartModal.style.top = '0';
                cartModal.style.left = '0';
                cartModal.style.width = '100%';
                cartModal.style.height = '100%';
                cartModal.style.backgroundColor = 'rgba(0,0,0,0.5)';
                cartModal.style.display = 'flex';
                cartModal.style.justifyContent = 'center';
                cartModal.style.alignItems = 'center';
                cartModal.style.zIndex = '1000';
                
                // Contenu du panier
                const cartContent = document.createElement('div');
                cartContent.style.backgroundColor = 'white';
                cartContent.style.borderRadius = '5px';
                cartContent.style.padding = '20px';
                cartContent.style.maxWidth = '80%';
                cartContent.style.width = '600px';
                cartContent.style.maxHeight = '80vh';
                cartContent.style.overflowY = 'auto';
                
                cartContent.innerHTML = `
                    <h2 style="margin-bottom: 20px; color: #0066cc;">Votre Panier</h2>
                    <button id="close-cart" style="position: absolute; right: 20px; top: 20px; background: none; border: none; font-size: 20px; cursor: pointer;">×</button>
                `;
                
                if (cart.length === 0) {
                    cartContent.innerHTML += '<p>Votre panier est vide</p>';
                } else {
                    let cartItems = '<div style="margin-bottom: 20px;">';
                    let total = 0;
                    
                    cart.forEach((item, index) => {
                        const itemTotal = item.price * item.quantity;
                        total += itemTotal;
                        
                        cartItems += `
                            <div style="display: flex; margin-bottom: 15px; padding-bottom: 15px; border-bottom: 1px solid #eee;">
                                <div style="width: 80px; height: 80px; background-color: #f5f5f5; margin-right: 15px;">
                                    <img src="${item.image}" alt="${item.title}" style="width: 100%; height: 100%; object-fit: cover;">
                                </div>
                                <div style="flex-grow: 1;">
                                    <h3 style="margin: 0 0 5px 0; font-size: 16px;">${item.title}</h3>
                                    <p style="margin: 0 0 5px 0; color: #0066cc; font-weight: bold;">${item.price.toFixed(2)} €</p>
                                    <div style="display: flex; align-items: center;">
                                        <button class="quantity-btn" data-action="decrease" data-index="${index}" style="width: 25px; height: 25px; background-color: #eee; border: none; border-radius: 3px; cursor: pointer;">-</button>
                                        <span style="margin: 0 10px;">${item.quantity}</span>
                                        <button class="quantity-btn" data-action="increase" data-index="${index}" style="width: 25px; height: 25px; background-color: #eee; border: none; border-radius: 3px; cursor: pointer;">+</button>
                                        <button class="remove-btn" data-index="${index}" style="margin-left: auto; background-color: #ff6600; color: white; border: none; padding: 5px 10px; border-radius: 3px; cursor: pointer;">Supprimer</button>
                                    </div>
                                </div>
                            </div>
                        `;
                    });
                    
                    cartItems += '</div>';
                    
                    // Ajouter le total et les boutons d'action
                    cartItems += `
                        <div style="font-size: 18px; font-weight: bold; margin-bottom: 20px;">
                            Total: ${total.toFixed(2)} €
                        </div>
                        <div style="display: flex; justify-content: space-between;">
                            <button id="empty-cart" style="background-color: #ccc; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;">Vider le panier</button>
                            <button id="checkout-btn" style="background-color: #0066cc; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;">Passer au paiement</button>
                        </div>
                    `;
                    
                    cartContent.innerHTML += cartItems;
                }
                
                cartModal.appendChild(cartContent);
                document.body.appendChild(cartModal);
                
                // Fermer la modal
                document.getElementById('close-cart').addEventListener('click', function() {
                    cartModal.remove();
                });
                
                // Fermer en cliquant en dehors du contenu
                cartModal.addEventListener('click', function(e) {
                    if (e.target === cartModal) {
                        cartModal.remove();
                    }
                });
                
                // Gestion des quantités et suppression
                if (cart.length > 0) {
                    // Changer quantité
                    document.querySelectorAll('.quantity-btn').forEach(btn => {
                        btn.addEventListener('click', function() {
                            const index = parseInt(this.getAttribute('data-index'));
                            const action = this.getAttribute('data-action');
                            
                            if (action === 'increase') {
                                cart[index].quantity++;
                            } else if (action === 'decrease') {
                                if (cart[index].quantity > 1) {
                                    cart[index].quantity--;
                                }
                            }
                            
                            localStorage.setItem('dstech_cart', JSON.stringify(cart));
                            updateCartCount();
                            cartModal.remove();
                            showCart(); // Réafficher avec données à jour
                        });
                    });
                    
                    // Supprimer du panier
                    document.querySelectorAll('.remove-btn').forEach(btn => {
                        btn.addEventListener('click', function() {
                            const index = parseInt(this.getAttribute('data-index'));
                            cart.splice(index, 1);
                            localStorage.setItem('dstech_cart', JSON.stringify(cart));
                            updateCartCount();
                            cartModal.remove();
                            showCart(); // Réafficher avec données à jour
                        });
                    });
                    
                    // Vider le panier
                    document.getElementById('empty-cart').addEventListener('click', function() {
                        cart = [];
                        localStorage.setItem('dstech_cart', JSON.stringify(cart));
                        updateCartCount();
                        cartModal.remove();
                        showCart(); // Réafficher avec données à jour
                    });
                    
                    // Passer au paiement
                    document.getElementById('checkout-btn').addEventListener('click', function() {
                        cartModal.remove();
                        showCheckout(total);
                    });
                }
            }
            

        // ici




            // Afficher la page de paiement

            function showCheckout(total) {
                // Créer la modal de paiement
                const checkoutModal = document.createElement('div');
                checkoutModal.style.position = 'fixed';
                checkoutModal.style.top = '0';
                checkoutModal.style.left = '0';
                checkoutModal.style.width = '100%';
                checkoutModal.style.height = '100%';
                checkoutModal.style.backgroundColor = 'rgba(0,0,0,0.5)';
                checkoutModal.style.display = 'flex';
                checkoutModal.style.justifyContent = 'center';
                checkoutModal.style.alignItems = 'center';
                checkoutModal.style.zIndex = '1000';
                
                // Contenu du checkout
                const checkoutContent = document.createElement('div');
                checkoutContent.style.backgroundColor = 'white';
                checkoutContent.style.borderRadius = '5px';
                checkoutContent.style.padding = '20px';
                checkoutContent.style.maxWidth = '80%';
                checkoutContent.style.width = '500px';
                
                checkoutContent.innerHTML = `
                    <h2 style="margin-bottom: 20px; color: #0066cc;">Finaliser votre commande</h2>
                    <button id="close-checkout" style="position: absolute; right: 20px; top: 20px; background: none; border: none; font-size: 20px; cursor: pointer;">×</button>
                    
                    <div style="margin-bottom: 20px;">
                        <h3>Récapitulatif</h3>
                        <p>Total: <strong>${total.toFixed(2)} €</strong></p>
                    </div>
                    
                    <form id="payment-form" style="margin-bottom: 20px;">
                        <div style="margin-bottom: 15px;">
                            <label for="name" style="display: block; margin-bottom: 5px;">Nom</label>
                            <input type="text" id="name" required style="width: 100%; padding: 10px; border: 1px solid #ddd; border-radius: 4px;">
                        </div>
                        
                        <div style="margin-bottom: 15px;">
                            <label for="email" style="display: block; margin-bottom: 5px;">Email</label>
                            <input type="email" id="email" required style="width: 100%; padding: 10px; border: 1px solid #ddd; border-radius: 4px;">
                        </div>
                        
                        <div style="margin-bottom: 15px;">
                            <label for="address" style="display: block; margin-bottom: 5px;">Adresse</label>
                            <input type="text" id="address" required style="width: 100%; padding: 10px; border: 1px solid #ddd; border-radius: 4px;">
                        </div>
                        
                        <div style="margin-bottom: 20px;">
                            <label for="card-element" style="display: block; margin-bottom: 5px;">Carte de crédit</label>
                            <div id="card-element" style="padding: 10px; border: 1px solid #ddd; border-radius: 4px;"></div>
                            <div id="card-errors" role="alert" style="color: #ff0000; margin-top: 5px;"></div>
                        </div>
                        
                        <button type="submit" id="submit-payment" style="background-color: #0066cc; color: white; border: none; padding: 12px 20px; border-radius: 5px; cursor: pointer; width: 100%;">
                            Payer ${total.toFixed(2)} €
                        </button>
                    </form>
                `;
                
                checkoutModal.appendChild(checkoutContent);
                document.body.appendChild(checkoutModal);
                
                // Créer l'élément de carte Stripe
                const style = {
                    base: {
                        color: '#32325d',
                        fontFamily: '"Helvetica Neue", Helvetica, sans-serif',
                        fontSmoothing: 'antialiased',
                        fontSize: '16px',
                        '::placeholder': {
                            color: '#aab7c4'
                        }
                    },
                    invalid: {
                        color: '#fa755a',
                        iconColor: '#fa755a'
                    }
                };
                
                const cardElement = elements.create('card', {style: style});
                cardElement.mount('#card-element');
                
                // Gérer les erreurs de validation de carte
                cardElement.addEventListener('change', function(event) {
                    const displayError = document.getElementById('card-errors');
                    if (event.error) {
                        displayError.textContent = event.error.message;
                    } else {
                        displayError.textContent = '';
                    }
                });
                
                // Traiter le paiement à la soumission du formulaire
                const form = document.getElementById('payment-form');
                form.addEventListener('submit', function(event) {
                    event.preventDefault();
                    
                    // Désactiver le bouton pendant le traitement
                    document.getElementById('submit-payment').disabled = true;
                    document.getElementById('submit-payment').textContent = 'Traitement en cours...';
                    
                    const name = document.getElementById('name').value;
                    const email = document.getElementById('email').value;
                    const address = document.getElementById('address').value;
                    
                    // Ici, dans une implémentation réelle, vous enverriez ces données à votre serveur
                    // qui créerait une intention de paiement avec Stripe, puis utiliserait la méthode suivante:
                    
                    /* 
                    // Code commenté: ceci serait exécuté sur votre serveur
                    stripe.confirmCardPayment(clientSecret, {
                        payment_method: {
                            card: cardElement,
                            billing_details: {
                                name: name,
                                email: email,
                                address: {
                                    line1: address
                                }
                            }
                        }
                    }).then(function(result) {
                        if (result.error) {
                            // Afficher l'erreur
                            document.getElementById('card-errors').textContent = result.error.message;
                            document.getElementById('submit-payment').disabled = false;
                            document.getElementById('submit-payment').textContent = `Payer ${total.toFixed(2)} €`;
                        } else {
                            // Succès du paiement
                            handlePaymentSuccess();
                        }
                    });
                    */
                    
                    // Pour cette démo, nous simulons simplement un paiement réussi
                    setTimeout(() => {
                        handlePaymentSuccess();
                    }, 2000);
                });
                
                // Gérer le succès du paiement
                function handlePaymentSuccess() {
                    // Vider le panier
                    cart = [];
                    localStorage.setItem('dstech_cart', JSON.stringify(cart));
                    updateCartCount();
                    
                    // Afficher confirmation
                    checkoutContent.innerHTML = `
                        <h2 style="margin-bottom: 20px; color: #0066cc;">Paiement effectué avec succès !</h2>
                        <p style="margin-bottom: 20px;">Merci pour votre commande. Un email de confirmation a été envoyé à l'adresse que vous avez fournie.</p>
                        <p style="margin-bottom: 20px;">Numéro de commande: <strong>${Math.floor(Math.random() * 1000000)}</strong></p>
                        <button id="continue-shopping" style="background-color: #0066cc; color: white; border: none; padding: 12px 20px; border-radius: 5px; cursor: pointer; width: 100%;">
                            Continuer vos achats
                        </button>
                    `;
                    
                    document.getElementById('continue-shopping').addEventListener('click', function() {
                        checkoutModal.remove();
                    });
                }
                
                // Fermer la modal
                document.getElementById('close-checkout').addEventListener('click', function() {
                    checkoutModal.remove();
                });
                
                // Fermer en cliquant en dehors du contenu
                checkoutModal.addEventListener('click', function(e) {
                    if (e.target === checkoutModal) {
                        checkoutModal.remove();

                    }
                });
            }
        });
    
    </script>
</body>

