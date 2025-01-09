# Custom NER Model Development with spaCy

## Overview  
In this project, I developed a custom Named Entity Recognition (NER) model using **spaCy**. The process involved manually annotating data, training the model, and evaluating its performance on unseen text. This project provided hands-on experience in working with NLP models, data annotation, and model training pipelines.


![image](https://github.com/user-attachments/assets/d748d57c-d0b4-42e9-a13f-22089b1f86e5)

---

## Goals and Skills Learned

- **Manual Data Annotation**: I manually annotated a dataset with entity labels such as `NAME`, `ROLE`, and `SKILL`. This skill improved my understanding of how to prepare data for machine learning tasks.
  
- **spaCy Custom NER Model Development**: Using spaCy, I built a custom NER model, incorporating a structured approach to create and refine entity recognition capabilities.

- **Model Training and Evaluation**: I trained the model using spaCy's built-in training functionality and evaluated its performance using custom evaluation datasets.

- **Error Handling and Debugging**: Throughout the process, I encountered and resolved various issues related to annotation structure, data preprocessing, and model training.

---

## Steps Taken

1. **Manual Data Annotation**:  
   - Annotated a dataset with entities for `NAME`, `ROLE`, and `SKILL`.  
   - Used JSON format for annotations, ensuring each entity had a corresponding start and end index.

2. **Data Preparation**:  
   - Loaded annotations from a JSON file and parsed the data to extract texts and their corresponding entities.

3. **spaCy Model Training**:  
   - Initialized a blank spaCy model (`en_core_web_sm`) and added custom NER capabilities.  
   - Added annotations by processing each text and mapping entities to their respective spans and labels.

4. **Training Pipeline**:  
   - Applied training to the custom NER model using spaCy’s update method and training examples.  
   - Evaluated the model using custom evaluation data to ensure accuracy and performance.

5. **Evaluation**:  
   - Used spaCy’s built-in evaluation methods to measure precision, recall, and F1-score.  
   - Achieved a perfect 100% accuracy in metrics for the custom NER model.

---

## Application to Resume Project

- **Resume Data Extraction**:  
  - The custom NER model will be integrated into my resume project to automatically extract and categorize relevant entities such as names, roles, and skills from resumes.  
  - This will streamline the process of building a comprehensive resume database and enhance the search and filtering capabilities for roles and skill sets.

---

## Challenges and Solutions

- **Error Handling**:  
  - Overcame issues such as incorrect entity formats, ensuring that only integer indices were used for entity spans.  
  - Corrected issues related to model training inputs being incorrectly structured or parsed.

- **Debugging**:  
  - Worked through errors in model training pipeline, refining entity handling and updating process using examples.

---

## Future Work

- **Fine-tuning**: Further refining the model by adding more data and iteratively improving performance.  
- **Deployment**: Using the model in a real-world application for tasks such as extracting roles, skills, and responsibilities from text data.

---

## Conclusion

This project provided a comprehensive approach to building a custom NER model, honing skills in data annotation, NLP model development, and model evaluation.
