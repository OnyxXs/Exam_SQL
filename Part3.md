# Partie 3

### 17. SELECT * FROM orders;

### 18. SELECT * FROM orders WHERE amount > 100;

### 19. SELECT clients.name, orders.id FROM clients JOIN orders ON clients.id = orders.client_id;

### 20. SELECT clients.name, orders.id FROM clients JOIN orders ON clients.id = orders.client_id WHERE clients.name = 'Nom_client';

### 21. SELECT SUM(amount) FROM orders;

### 22. SELECT AVG(amount) FROM orders;

### 23. SELECT clients.name, --la il faut compter avec les order.id, je crois que c'est COUNT mais comme je suis pas sur de moi je le met la (COUNT(orders.id))-- FROM clients JOIN orders ON clients.id = orders.client_id GROUP BY clients.name;