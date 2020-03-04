# AutoGradeBook-Flight-Recommender-System
Master's thesis work and prototypical recommender system for automated flight event suggestions

# Abstract
The Air Force’s Pilot Training Next (PTN) program seeks a more efficient pilot training environment emphasizing the use of virtual reality flight simulators alongside periodic real aircraft experience. The PTN program wants to accelerate the training pace and progress in undergraduate pilot training compared to traditional undergraduate pilot training. Currently, instructor pilots spend excessive time planning and scheduling flights. This research focuses on methods to auto-generate the planning of in-flight events using hybrid filtering and deep learning techniques.  The resulting approach captures temporal trends of user-specific and program-wide student performance to recommend a feasible set of graded flight events for evaluation in a student's next training exercise to improve their progress toward fully qualified status.

# Files 
1. Thesis Document(Forrest_Thesis) - full document of thesis research to include motivation, literature review, modeling approach, results, and proposed future work.
2. Thesis Defense Slides(ThesisDefenseSlides-notes) - final powerpoint presentation for thesis defense with notes on each slide. 
3. Initial Data(PTN_raw_data_clean) - Grade sheets from the first PTN graduating class. 
4. Research Summary Poster(Research_Poster) - Poster outlining all research. 


# Jupyter Notebooks

1. Initial data cleaning (DataCleanUp_PTNdata1.ipynb)
2. Exploratory Data analysis (EDA_PTNdata1.ipynb)
3. Model training (LOOCV_ModelTraining_PTNdata1.ipynb)
4. Model time trials (final_time_trials.ipynb)
5. Final Recommender system (final_model.ipynb)

# Model Parameters
final, best-fit model weights for LSTM model (final_model.h5) - these were generated in the Model Training Jupyter Notebook

# Other data files
PTNdata1_clean.ipynb - 
PTNdata1_final.ipynb - 
PTNdata1_master.ipynb - 
