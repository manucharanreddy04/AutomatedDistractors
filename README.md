📝 AutomatedDistractors — Automatic Distractor Generation for MCQs

   AutomatedDistractors is a Natural Language Processing (NLP) project designed to automatically generate high-quality distractor options for multiple-choice questions. Distractors are incorrect but plausible answer choices used in exams, quizzes, and e-learning platforms.
   This system helps educators and content creators reduce manual effort in building assessment materials.


--🎯 Project Goal--

   To automate the creation of plausible, context-aware distractors using NLP techniques, improving the quality of MCQs while saving time and effort for instructors.



--🚀 Features--

   *🤖 Automatic distractor generation from input text or keywords
   *📚 NLP-based processing for semantic similarity
   *📝 Generates multiple distractors per correct answer
   *🧠 Prevents irrelevant or illogical distractors
   *🔧 Configurable logic to adjust difficulty
   *🎓 Useful for learning apps, assessments, and test prep



--🛠️ Tech Stack--

  *Python
  *NLTK / spaCy (if used)
  *WordNet (semantic relationships)
  *Sentence Transformers / Embeddings (optional)
  *Scikit-learn


--AutomatedDistractors/--

  ├── distractor_generator.py     # Core logic for generating distractors
  ├── utils.py                    # Helper functions (tokenization, stemming, etc.)
  ├── data/                       # Any datasets or keyword lists
  ├── examples/                   # Sample input/output
  ├── AutomatedDistractors.ipynb  # Notebook for testing and demos
  ├── README.md                   # Documentation
  └── requirements.txt            # Dependencies (optional)


--▶️ How It Works--

   1.Input: A correct answer or source sentence.
   2.NLP Processing:
     .Tokenization
     .POS tagging
     .Synonym / antonym extraction
     .Semantic similarity
   3.Filtering to remove irrelevant or identical options.
   4.Rank and Select top distractors based on linguistic plausibility.
   5.Output: A set of 3–5 distractors ready for use in MCQs.


   --▶️ How to Run the Project--
    
  1. Clone the repository
     git clone https://github.com/manucharanreddy04/AutomatedDistractors.git
     cd AutomatedDistractors

  2. Install dependencies
     pip install -r requirements.txt
     If no requirements file exists, install common packages:
     pip install nltk spacy sklearn

  3. Run the demo script
     python distractor_generator.py

  4. Or open the notebook
     jupyter notebook AutomatedDistractors.ipynb


--📌 Example Output--

   Input:
   Correct answer → Photosynthesis

   Generated Distractors:

   Respiration
   Chlorophyll breakdown
   Carbon cycle

   (This is just an example; real outputs depend on dataset/implementation.)

--🔮 Future Enhancements--

   Add deep learning–based distractor generation
   Improve contextual awareness (transformers-based)
   Add difficulty-level selection
   Build a simple UI using Flask or Streamlit
   Deploy as an API


--📄 License--

   This project is meant for educational and research purposes.
  
