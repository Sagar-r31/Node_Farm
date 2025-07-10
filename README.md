
# 🌽 Node Farm

This project is a simple Node.js application that serves dynamic farm product pages using raw Node.js (no frameworks). It demonstrates:

- Reading and parsing JSON data
- Building HTML templates dynamically
- Serving different routes (overview, product details, API)

---

## 🗂 Project Structure

```
1-node-farm/
├── data/
│   └── data.json               # Product data
├── templates/
│   ├── template-overview.html  # Overview page template
│   ├── template-card.html      # Template for individual product cards
│   └── template-product.html   # Template for the product detail page
├── index.js                    # Node.js server logic
├── package.json                # NPM configuration and dependencies
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) installed (v12+ recommended)

---

### Installation

1. Clone or download this repository.
2. Open your terminal and navigate into the project folder:

   ```bash
   cd Node_Farm
   ```

3. Install dependencies (if you have a `package.json`):

   ```bash
   npm install
   ```

   > Note: This project may not have external dependencies. If so, skip this step.

---

### Running the Server

To start the Node.js server:

```bash
node index.js
```

You should see a message:

```
Listening to requests on port 8000
```

---

### Usage

- Open your browser and visit:

  ```
  http://localhost:8000
  ```

- **Overview Page:** Lists all products as slanted cards.
- **Product Page:** Click "DETAIL" on a product to see details.
- **API Endpoint:** Access raw data as JSON via:
  
  ```
  http://localhost:8000/api
  ```

---

## 🧩 Customizing Templates

All HTML templates are in the `templates/` folder:

- `template-overview.html`: the main listing page
- `template-card.html`: each product card
- `template-product.html`: single product detail

You can adjust styling or HTML as needed.

---

## 💻 Screenshots

Example Overview Page:
![alt text](image.png)
![alt text](image-1.png)


---

## 📝 License

This project is for educational purposes. Use it freely to learn how Node.js handles HTTP servers without frameworks.

---

Enjoy building your own Node Farm! 🌿🌽
