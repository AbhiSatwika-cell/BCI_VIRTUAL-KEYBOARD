## BCI Virtual Keyboard with CNN  

### Introduction  
This project develops a **Brain-Computer Interface (BCI) Virtual Keyboard** that leverages a **Convolutional Neural Network (CNN)** to interpret EEG signals and recognize alphabetic characters in real time. It integrates efficient signal processing, precise predictions, and an intuitive Python-based graphical user interface.  

### Key Features  
- **EEG Signal Processing**: Converts raw EEG signals into a suitable format for model input.  
- **CNN-Based Prediction**: Utilizes deep learning to detect character patterns in EEG data.  
- **Interactive Virtual Keyboard**: Enables real-time display of predicted letters.  
- **User-Friendly GUI**: Provides seamless interaction via a Python-based interface.  

### Potential Applications  
- Assists individuals with disabilities in communication.  
- Enables hands-free text input.  
- Can be incorporated into gaming, education, and healthcare technologies.  

### Technologies Employed  
- **Python**: Used for coding the model and graphical interface.  
- **TensorFlow/Keras**: Framework for training the CNN.  
- **EEG Data**: Collected from public sources or custom datasets.  
- **PyQt/Tkinter**: Builds the graphical user interface.  

### Workflow  
1. **Data Acquisition**: EEG signals are captured while the user focuses on specific letters.  
2. **Preprocessing**: The raw EEG signals undergo cleaning and transformation.  
3. **Model Training**: The CNN learns patterns corresponding to different characters.  
4. **Live Predictions**: The trained model deciphers letters from EEG input.  
5. **Virtual Keyboard Output**: The recognized letters appear on the GUI.

## Download EEG Datasets
You can download  EEG datasets from the following link:
- https://drive.google.com/drive/folders/1bPkUAXfaNIASRYOV8dfZ4E5meMvylhy_?usp=drive_link
 
## Future Enhancements
- Add support for numbers and symbols.
- Improve prediction accuracy and real-time performance.
- Introduce multi-language support for the virtual keyboard.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/BCI_Virtual_Keyboard.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Contributions
We welcome contributions! Feel free to fork this repository, submit pull requests, or open issues to suggest improvements or report bugs.
