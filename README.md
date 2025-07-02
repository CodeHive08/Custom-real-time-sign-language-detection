# Real-Time Sign Language Detection

A web application that uses a Teachable Machine image model and your webcam to recognize and display sign language gestures in real time. Built with HTML, CSS, and JavaScript, and deployable on any static hosting service (like GitHub Pages).
Live demo:https://signlan.netlify.app/
## Features
- **Real-time webcam sign language detection**
- **Animated prediction bars** for each class
- **Modern, dark-themed UI**
- **User manual overlay** for new users
- **Easy deployment** (no backend required)

## Demo
![image](https://github.com/user-attachments/assets/9acd9cc1-865e-489a-b29f-39c0afaff229)
![image](https://github.com/user-attachments/assets/d36ce2fe-ce6e-493c-8e01-fcd953177602)
![image](https://github.com/user-attachments/assets/208e19cc-02a0-4236-b5be-62416af15c4f)
![image](https://github.com/user-attachments/assets/b9afd4f2-a440-4cf5-a96b-ef01d8fece55)


## Getting Started

### 1. Clone or Download
```
git clone[ https://github.com/yourusername/your-repo-name.git](https://github.com/CodeHive08/Custom-real-time-sign-language-detection.git)
cd Custom-real-time-sign-language-detection
```
Or download and unzip the project folder.

### 2. Local Development
You must use a local server (not open the HTML file directly) to avoid CORS issues.

#### Using Python (recommended for most users):
```
python -m http.server 8000
```
Then open [http://localhost:8000/](http://localhost:8000/) in your browser.

#### Using Node.js (if installed):
```
npm install -g http-server
http-server -p 8000
```
Then open [http://localhost:8000/](http://localhost:8000/).

#### Using VS Code Live Server:
- Install the "Live Server" extension
- Right-click `index.html` > "Open with Live Server"

## Usage
- Click **Start Detection** to activate your webcam and begin real-time sign language recognition.
- Click **New User** to view the user manual (`usermanual.png`).
- The prediction bars show the probability for each gesture.

## Project Structure
```
real time sign language detection/
├── index.html
├── README.md
├── usermanual.png
└── tm-my-image-model/
    ├── model.json
    ├── metadata.json
    └── weights.bin
```

## Credits
- [Teachable Machine](https://teachablemachine.withgoogle.com/) for model creation
- [TensorFlow.js](https://www.tensorflow.org/js) for running the model in-browser

## Author
Sandeep Singh Mehta

## License
MIT 
