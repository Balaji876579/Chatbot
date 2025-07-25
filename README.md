# Jarvis: An Interactive AI Assistant Notebook

A Jupyter Notebook assistant—**Jarvis**—combining real-time news, Wikipedia search, jokes, time-telling, and video search, all through an interactive button-based interface with a simple RNN model setup using TensorFlow.

## Features

- **News Headlines:** Fetches and displays the latest top 5 U.S. news headlines with a single click.
- **Wikipedia Search:** Lets you search Wikipedia easily and view concise results instantly in the notebook.
- **Joke Teller:** Delivers tech-friendly jokes with no repetition until all available jokes are exhausted.
- **Current Time:** Instantly displays the current time in Indian Standard Time (IST).
- **YouTube Video Links:** Generates clickable YouTube search links based on user input to find videos easily.

## How It Works

- **Interactive Buttons:**  
  Five buttons—News, Time, Joke, Search, Play—are displayed for quick access to different functionalities. Clicking any button updates the output area accordingly, keeping the interface clean and user-friendly.

- **Dynamic Content:**  
  All operations (news fetch, Wikipedia search, etc.) happen dynamically so results appear right after your button click or query input.

- **Simple RNN Example:**  
  The code includes an example of a simple RNN model, showcasing how to set up a TensorFlow Sequential model for those interested in experimentations with deep learning.

## Usage

1. **Dependencies:**  
   Install required Python packages:
   ```
   pip install tensorflow requests pyjokes ipywidgets beautifulsoup4 lxml pytz
   ```
2. **Notebook Environment:**  
   Make sure to run this script in a Jupyter or IPython notebook to support `ipywidgets` and real-time interactivity.
3. **Run the Script:**  
   All main functions and handlers are defined in a single cell. Just run the cell and use the buttons.
4. **Welcome Message:**  
   You’ll see:  
   ```
   Welcome to Jarvis! Use the buttons above to interact.
   ```

## Customization Ideas

- Plug in your own News API key for news headlines.
- Swap out the search endpoint to support other information sources.
- Expand with weather updates, dictionary lookups, or additional AI-driven responses.
- Modify the RNN architecture for your own text modeling use cases.

## Disclaimer

- The Notebook relies on certain third-party APIs (e.g., NewsAPI, Wikipedia); API usage limits may apply.
- Designed for demostration, learning, and fun—not for production or critical use.
- Requires internet connectivity for live content retrieval.

**Get started and have fun with Jarvis—your interactive notebook assistant!**
