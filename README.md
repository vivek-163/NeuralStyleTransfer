# Neural Style Transfer

## 📌 Overview

This project implements **Neural Style Transfer (NST)** using a **pre-trained VGG19 model**. NST applies the artistic style of one image to another while preserving the content structure.

## 🚀 Features

- Uses **VGG19** for feature extraction.
- Extracts **content** and **style features**.
- Computes **Gram matrices** for style representation.
- Optimizes an image to match style and content.
- Supports **custom content and style images**.

## 📂 Project Structure

```
├── neural_style_transfer.ipynb  # Jupyter Notebook containing the NST implementation
├── README.md                    # Project documentation
├── LICENSE                       # Open-source license file
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. **Install dependencies**
   ```bash
   pip install tensorflow numpy matplotlib pillow
   ```
3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook neural_style_transfer.ipynb
   ```

## 📸 Example Output

| Content Image | Style Image | Generated Image |
|--------------|------------|----------------|
| ![Content](images/content.jpg) | ![Style](images/style.jpg) | ![Output](images/output.jpg) |

## 📜 How It Works

1. Extract content & style features using VGG19.
2. Compute the **content loss** between the generated and content images.
3. Compute the **style loss** using the **Gram matrix**.
4. Optimize the generated image using **gradient descent**.

## 🛠 Technologies Used

- **TensorFlow/Keras** - Deep learning framework
- **VGG19** - Pre-trained model for feature extraction
- **NumPy & Matplotlib** - Data manipulation & visualization

## 📌 To-Do

- [ ] Improve training efficiency
- [ ] Add support for different optimization techniques
- [ ] Create a web UI for image upload & processing

## 📢 Contributing

Feel free to open issues, submit pull requests, or suggest improvements!

## 📜 License

This project is open-source under the **MIT License**.


