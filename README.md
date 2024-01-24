# Blog Generation LLM App

This Streamlit web application simplifies the process of generating blogs using the LLama 2 language model. To make it easy for others to use and deploy, follow the steps below:

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/hardikjp7/Blog-Generation-LLM-App.git
   cd Blog-Generation-LLM-App
   ```

2. **Download LLama 2 Model:**
   Visit the official LLama 2 model page [here](https://ai.meta.com/llama/) and download the "llama-2-7b-chat.ggmlv3.q8_0.bin" file.

3. **Add Model to "models" Folder:**
   Place the downloaded model file in the "models" folder of this project.

4. **Install Dependencies:**
   Use the following command to install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application:**
   Execute the Streamlit app with the following command:
   ```bash
   streamlit run app.py
   ```

6. **Access the Web App:**
   Open your web browser and navigate to the provided local address (usually http://localhost:8501).

## Generating Blogs

1. Enter the desired blog topic in the provided text input.

2. Choose the intended audience for the blog by selecting from the available options: Researchers, Data Scientists, or Common People.

3. Specify the desired word count for the generated blog.

4. Click the "Generate" button to trigger the LLama 2 language model and receive the dynamically created blog.

Now you can effortlessly create blogs using the Blog Generation LLM App! 🚀
