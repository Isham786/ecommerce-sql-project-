-- USERS
CREATE TABLE users (
    user_id INTEGER,
    name TEXT,
    email TEXT
);

-- CATEGORIES
CREATE TABLE categories (
    category_id INTEGER,
    category_name TEXT
);

-- PRODUCTS
CREATE TABLE products (
    product_id INTEGER,
    name TEXT,
    price INTEGER,
    category_id INTEGER
);

-- ORDERS
CREATE TABLE orders (
    order_id INTEGER,
    user_id INTEGER,
    status TEXT
);

-- ORDER ITEMS
CREATE TABLE order_items (
    order_id INTEGER,
    product_id INTEGER,
    quantity INTEGER
);

-- PAYMENTS
CREATE TABLE payments (
    payment_id INTEGER,
    order_id INTEGER,
    amount INTEGER,
    payment_method TEXT
);
