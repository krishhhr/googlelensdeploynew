# 📸 Google Lens Deployment with Flask 🚀

This project demonstrates a Flask-based web application that allows users to upload images, which are then uploaded to **Imgur** 🖼️. The image’s URL is then used to query **Google Lens** 🔍 via **SerpAPI**, which returns relevant search results based on the image content. Perfect for anyone interested in integrating image recognition into web apps!

## 🌟 Features
- **Upload** an image 📤 via a user-friendly interface.
- **Image Hosting** through Imgur 🔗 for easy access and sharing.
- **Google Lens Analysis** powered by SerpAPI to fetch image-based search results 🧐.
- **Responsive UI** to display results dynamically 🎉.

## 🧑‍💻 Installation & Setup

### 🔧 Prerequisites
Before getting started, make sure you have:
- Python 3.x
- Pip (Python package installer)
- Flask (`pip install flask`)
- Requests (`pip install requests`)
- [SerpAPI Key](https://serpapi.com/) for Google Lens integration
- [Imgur Client ID](https://apidocs.imgur.com/) for image uploads

### ⚙️ Steps to Deploy

1. **Clone the repository**:
    ```bash
    git clone https://github.com/krishhhr/googlelensdeploynew.git
    cd googlelensdeploynew
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure API keys**:
   - Replace `client_id` with your **Imgur Client ID**.
   - Replace `SERP_API_KEY` with your **SerpAPI API key**.

4. **Run the Flask app**:
    ```bash
    python app.py
    ```
    The app will be accessible at `http://127.0.0.1:5000/`.

### 📸 Upload Image
- Click on the **"Upload Image"** button to select an image from your device.
- Once uploaded, the image will be sent to **Imgur** and analyzed by **Google Lens**.

### 🔍 Search Results
- After the image is analyzed, the Google Lens search results will be shown below the image, including possible matches or relevant information.
  
  ![image](https://github.com/user-attachments/assets/f276eda3-ee92-43fc-9fb1-27a8ce84ba8c)


## ✨ How It Works
1. **Image Upload**: Users upload an image to the web app via a simple form.
2. **Imgur API**: The image is sent to **Imgur**'s API, which returns a URL for the image.
3. **Google Lens**: The Imgur URL is then passed to **SerpAPI** to retrieve Google Lens results.
4. **Display Results**: The results are displayed dynamically on the webpage.

## 💡 Example Use Case
- **Image Recognition**: Upload an image and discover similar objects or information related to it.
- **Product Search**: Take a photo of a product and get related results.

## 🛠️ Contributing
We welcome contributions! Feel free to fork the repository, make improvements, or submit bug fixes. To contribute:
1. Fork the repo
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Open a pull request

## 🔑 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🏆 Acknowledgements
- [Flask](https://flask.palletsprojects.com/) for creating the web framework.
- [Imgur API](https://apidocs.imgur.com/) for image hosting.
- [SerpAPI](https://serpapi.com/) for powering Google Lens integration.

Happy Image Searching! 📸✨
