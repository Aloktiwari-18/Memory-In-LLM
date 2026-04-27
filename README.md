🚀 Memory System Implementation (STM + LTM)

This repository demonstrates the implementation of Short-Term Memory (STM) and Long-Term Memory (LTM) concepts, commonly used in AI systems, chatbots, and LLM-based applications.

It includes step-by-step notebooks covering memory creation, persistence, trimming, summarization, and integration with databases like PostgreSQL.

📂 Project Structure
├── 1_stm.ipynb                 # Basic Short-Term Memory implementation
├── 2_stm_persistence.ipynb     # STM with persistence
├── 3_stm_trimming.ipynb        # Memory trimming techniques
├── 4_stm_deletion.ipynb        # Deleting old/irrelevant memory
├── 5_stm_summarization.ipynb   # Summarizing memory for optimization
├── 6_ltm_basics.ipynb          # Introduction to Long-Term Memory
├── 7_ltm_implementation.ipynb  # LTM implementation logic
├── 8_ltm_postgres.ipynb        # PostgreSQL integration for LTM
├── docker-compose.yml          # Docker setup for services
└── README.md                   # Project documentation
🧠 Concepts Covered
🔹 Short-Term Memory (STM)
Stores recent interactions
Used for context in conversations
Includes:
Persistence
Trimming
Deletion
Summarization
🔹 Long-Term Memory (LTM)
Stores important data permanently
Useful for personalization & knowledge retention
Implemented using:
Database storage (PostgreSQL)
Retrieval mechanisms
⚙️ Tech Stack
🐍 Python
📓 Jupyter Notebook
🐘 PostgreSQL
🐳 Docker (via docker-compose)
🤖 AI/LLM concepts
🐳 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Run Docker (for PostgreSQL)
docker-compose up -d
3️⃣ Open Notebooks
jupyter notebook
📌 Use Cases
Chatbot memory systems 🤖
AI assistants with context retention
Personalized recommendation systems
Conversational AI applications
📈 Learning Outcome

By exploring this repo, you will understand:

How memory works in AI systems
Difference between STM & LTM
Memory optimization techniques
Database integration for AI memory
🤝 Contributing

Feel free to fork this repository and improve the implementation.

📬 Contact

For any queries or collaboration:

GitHub: Aloktiwari-18
⭐ If you found this useful

Give it a ⭐ on GitHub!
