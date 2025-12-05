OBRA Furniture Quotation App

A modern, responsive product quotation web application for OBRA Office Furniture. This app allows sales staff and clients to browse the catalog, build a quote, and print/download a PDF estimate.

🚀 Features

Searchable Catalog: Instant search by name or category.

Real-time Quotation: Add items to a cart and see the total update instantly.

PDF Generation: Built-in print-to-PDF functionality for professional quotes.

Responsive Design: Works seamlessly on desktop, tablets, and mobile phones.

Data Source: Powered by a CSV-to-JSON workflow for easy inventory updates.

🛠️ Tech Stack

React: Frontend framework.

Tailwind CSS: For styling and responsive layout.

Lucide React: For beautiful icons.

📦 Installation & Setup

Clone the repository

git clone [https://github.com/YOUR-USERNAME/obra-quotation-app.git](https://github.com/YOUR-USERNAME/obra-quotation-app.git)
cd obra-quotation-app


Install Dependencies

npm install


Run Locally

npm start


Open http://localhost:3000 to view it in your browser.

🔄 Updating Products

To update the product list:

Edit obra_csv_image.csv.

Run the python script: python convert_csv.py.

Copy the output from products.json into App.jsx.

📄 License

Proprietary software for OBRA Office Furniture.
