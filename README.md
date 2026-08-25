# AutoEncoder Web-App Project

[![React](https://img.shields.io/badge/React-18.0+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Flask](https://img.shields.io/badge/Flask-2.0+-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)

Welcome to my journey of exploring artificial intelligence and modern web development through practical projects. This repository contains a collection of intelligent web applications created for learning, experimentation, and implementation of AI/ML concepts.

---

## Featured Project: AutoEncoder Lab (Premium Denoising & Reconstruction)

AutoEncoder Lab is a production-ready, interactive Deep Learning web application designed to demonstrate image compression and noise reduction using a convolutional autoencoder model trained on the MNIST handwritten digit dataset. 

Built around the exact model architecture specified in `AutoEncoders_DL.ipynb`, the application is split into a **React 18 frontend** and a **Flask backend API**. It features custom canvas drawing inputs, real-time comparisons, before/after slider layers, metric calculations, and an interactive 2D latent space mapping viewer.

### Key Features

**Handwriting Canvas:** Draw a digit with brush/eraser sizing and full undo/redo capabilities. Downsamples drawings automatically to 28x28 grayscale tensors.

**Drag & Drop Upload:** Browse or drop PNG/JPG/JPEG digit images for instant inference.

**Interactive Comparison Slider:** Swipe side-by-side to compare original noisy inputs with denoised neural reconstructions.

**Inference Latency & Metrics:** Displays Mean Squared Error (MSE), latency times in milliseconds, compression ratios, and shape configurations.

**Latent Space Painter:** Explores the 392-dimensional bottleneck representation (8 channels of 7x7 activation grids). Click or hover-scroll grids to paint activations directly and morph digits in real time.

**Download Center:** Export the autoencoder-synthesized images to PNG format.

---

## 📂 Project Structure
