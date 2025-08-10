# My Online Store

This is a simple HTML-based online store page showcasing a few products with images, prices, and links to their official websites. It also includes a form for customers to request a device.

## 📂 Project Structure

```
project/
│
├── HML/              # Folder containing HTML codes
│   ├── index.html          # Main HTML file
├── MIDEA/              # Folder containing product images
│   ├── iphone.jpg
│   ├── samsung.jpg
│   └── one.jpg
```

## 🛒 Features

* **Header** with store name.
* **Product Table** displaying:

  * Product name
  * Product image
  * Price
  * Link to official website
* **Order Form** where customers can submit:

  * Name
  * Email
  * Date of Birth
* **Simple Styling** using inline CSS.

## 📸 Example Products

| Item    | Price |
| ------- | ----- |
| iPhone  | 5005  |
| Samsung | 3005  |
| OnePlus | 3505  |

## 🌐 How to Use

1. **Download or clone** this repository.
2. Place product images inside the `MIDEA/` folder with matching filenames as used in `index.html`.
3. Open `index.html` in any web browser.
4. Fill out the request form to simulate ordering (currently redirects to Google).

## 📌 Notes

* This is a static HTML site — no backend or database is connected.
* Links currently point to Google for demonstration purposes. Replace them with the actual product pages.
* You can improve the design by moving inline styles to a separate CSS file.

## 🖌 Future Improvements

* Add a proper backend to handle form submissions.
* Improve styling with an external CSS file.
* Make the layout responsive for mobile devices.
* Replace placeholder links with real store URLs.
