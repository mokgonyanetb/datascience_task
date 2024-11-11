# LelapaAI Data Scientist Task

Before running the Jupyter notebook, make sure to install the following dependencies:

1. **NLTK Data Downloads**  
   You need to download the necessary NLTK data packages for text processing. In your Python environment, run the following commands:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   nltk.download('stopwords')
   ```

2. **Python Packages**  
   Install the necessary Python packages using `pip`:

   ```bash
   pip install wordcloud matplotlib
   ```

3. **PyTorch Installation**  
   If you’re using CUDA 11.8, install PyTorch and its dependencies by running:

   ```bash
   pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
   ```

4. **KaggleHub**  
   For data access and loading, install KaggleHub:

   ```bash
   pip install kagglehub
   ```

5. **Torchaudio**  
   Install torchaudio for audio processing:

   ```bash
   pip install torchaudio
   ```

## How to Run the Jupyter Notebook

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mokgonyanetb/datascience_task.git
   ```

2. Navigate to the project directory:

   ```bash
   cd datascience_task
   ```

3. Install the necessary dependencies listed above.

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook and run the code cell by cell.

## Notes

- Make sure that the versions of the installed libraries are compatible with your Python environment.
- If you encounter any issues during installation, refer to the official documentation of the respective packages.