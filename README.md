Word Frequency Analyzer - C++ Data Structures Project

📌 Overview
This C++ program analyzes text input (either from the console or a file) and calculates word frequencies using efficient data structures. It provides various statistical insights, including word rankings, global frequencies, and search functionality.

✨ Features
Input Methods
Read text from console input

Read text from external files

Word Analysis
Frequency Count: Display how often each word appears

Global Frequencies: Track word occurrences across multiple inputs

Word Ranking: Show the rank of words based on frequency

Search Functionality: Find specific words and display their frequency/rank

Data Management
Update & Modify Text: Append or replace paragraphs

Save & Export: Store results in files for future reference

Visualization
Sorted Word List: View words ordered by frequency

Rank Display: See rankings for individual words or all words

🛠️ Technical Implementation
Data Structures: Uses hash maps (unordered_map) for efficient word counting

File Handling: Reads/writes text files (<fstream>)

String Manipulation: Processes input with <string> and <algorithm>

Modular Functions: Organized into logical components for readability

🚀 How to Use
Compile:

bash
Copy
g++ word_frequency.cpp -o word_frequency
Run:

bash
Copy
./word_frequency
Follow the Menu:

Choose input source (console/file)

Analyze word frequencies, ranks, and more

Save results if needed

📂 Project Structure
main.cpp: Core program with menu-driven interface

FileOperations.cpp/h: Handles file I/O

WordAnalyzer.cpp/h: Processes word frequencies & rankings

🔧 Future Improvements
Graphical UI (Qt/ImGui)

Stop-word filtering (ignore common words like "the," "and")

Multi-language support

Performance optimization for large texts

📜 License
Open-source (MIT). Contributions welcome!

Perfect for C++ learners exploring data structures, file handling, and text processing! 🚀
