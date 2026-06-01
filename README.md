# DATA_PIPELINE_DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: CTIS8214

*DOMAIN*: DATA SCIENCE

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
This task focused on developing a simple and efficient data pipeline for preparing raw healthcare-related data for further analysis and machine learning applications. The complete workflow was implemented using Python in Visual Studio Code (VS Code), which served as the primary development environment. VS Code provided an organized platform for writing, executing, and managing the data processing code while enabling easy debugging and workflow management. The dataset used in this task contained disease information along with multiple symptom attributes. Since real-world datasets often contain unnecessary columns, missing values, and categorical information that cannot be directly processed by machine learning algorithms, the main objective of this task was to transform the raw dataset into a clean and structured format. The project followed the standard stages of a data pipeline: data extraction, preprocessing, transformation, and loading.

The first step involved data extraction, where the dataset was imported into the project using the Pandas library. Pandas is one of the most widely used Python libraries for data manipulation and analysis because it allows datasets to be loaded and processed efficiently in tabular form. After loading the dataset, the data was inspected to understand its structure and identify potential issues that required cleaning before further processing. 

The next stage was data preprocessing, which focused on improving the quality of the dataset. Initially, missing values were examined using functions that helped identify incomplete records. During analysis, it was observed that several symptom-related columns from Symptom_7 to Symptom_17 were not required for the intended processing workflow. These columns were removed from the dataset to reduce unnecessary complexity and improve manageability. Removing irrelevant attributes is an important preprocessing step because it reduces storage requirements, simplifies computations, and improves the overall efficiency of downstream tasks.

After removing unwanted columns, the remaining symptom columns were renamed from lengthy names such as Symptom_1, Symptom_2, and so on into shorter and more convenient labels like s1, s2, s3, s4, s5, and s6. This transformation made the dataset easier to read and work with during later stages of the pipeline. Another important preprocessing activity involved handling missing values. Instead of leaving blank entries, all missing symptom values were replaced with the text "No Symptoms". This ensured that every record contained valid information and prevented errors during data transformation and model-building processes. The data transformation stage was performed using the LabelEncoder tool from the Scikit-learn library. Since machine learning algorithms typically require numerical input, categorical values needed to be converted into numerical representations. The disease column was encoded into numerical labels, allowing each disease category to be represented by a unique integer value. Similarly, the symptom columns were also transformed into encoded numerical values. This conversion made the dataset machine-readable while preserving the relationship between different categories.

Several scalable data-processing actions were incorporated throughout the workflow. The use of Pandas enabled efficient handling of large tabular datasets through optimized operations such as column removal, renaming, null-value replacement, and data inspection. Automated preprocessing steps ensured consistency across all records and reduced the need for manual intervention. The encoding process further enhanced scalability by systematically converting categorical information into a format suitable for analytical and predictive systems. These automated transformations can easily be applied to larger datasets without significant modifications to the workflow.

The final stage was data loading, where the processed dataset was exported and saved as a new file named processed_data.csv. Storing the cleaned and transformed dataset separately ensures that future analytical tasks can directly utilize the prepared data without repeating the preprocessing steps. This approach improves efficiency and supports reusable data engineering practices.

This task has practical applications in healthcare analytics, disease prediction systems, medical decision-support tools, and machine learning projects that rely on symptom-based datasets. By creating a structured and cleaned dataset, the pipeline establishes a strong foundation for building predictive models, generating insights, and supporting data-driven healthcare solutions. Overall, the task demonstrated the importance of data pipeline development in converting raw data into a reliable and usable resource for advanced analytical applications.

*OUTPUTS*:

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/b2a3a883-d3a1-4d3b-8c1a-73933ad5d503" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/81623fc0-768f-4ff5-8611-5126b4f8a0af" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/e589902e-6842-4e6c-a3dd-0b2746719d87" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/1ce3e5e8-2883-4662-9bd0-581a7da163fa" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/4290f7bd-dcbc-453b-8779-b7769a304cdb" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/e197c71a-6df9-4797-9dff-6452007eb1e9" />
