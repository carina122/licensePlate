Advanced ANPR program, using Sobel Operator logic and CNN architecture for character prediction.

Disclaimers: The CNN model is not pre-trained, that's why the first run (before the checkpoint directory is created), can take up to 4 mins.

Resorces: https://github.com/pragatiunna/License-Plate-Number-Detection.git

Setup:
   # Create virtual environment (optional but recommended)
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    
   # Install dependencies
    pip install --upgrade pip
    pip install ipywidgets==8.1.1
    pip install opencv-python==4.9.0.80
    pip install imutils==0.5.4
    pip install numpy==1.24.3
    pip install matplotlib==3.7.1
    pip install tensorflow==2.13.0
    pip install pandas==2.0.3
    pip install jupyter==1.0.0
    
   # Enable Jupyter widgets
    jupyter nbextension enable --py widgetsnbextension
   
  # Launch Jupyter (other IDEs can be used but this one is recommended)
    jupyter notebook
    
  # Navigate to license_plate.ipynb and run all cells in order

  # Upload files only from the provided "licensePlate\Artificial Mercosur License Plates\images" directory
   For best results, choose well-lit pictures.
   


