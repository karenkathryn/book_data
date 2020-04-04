# Another collaborative book recommender

This README.md file will serve as a roadmap to this repository. The repository is open and available to the public.

Directories and files to be aware of:

1. A notebooks/ directory that contains two Jupyter notebooks: 
    - A data exploration notebook that was used with another dataset (books_eda) 
    - A modeling notebook (books_sample_nb)

2. A data/ directory containing six data files. Due to GitHub upload restrictions, these are included as .gitignore files. The relevent files fir the modeling notebook are, in brief:   
    - ratings.csv
    - books.csv



Data: The data files described above can be found [here](https://www.kaggle.com/zygmunt/goodbooks-10k). An account setup is required for download.

Methodology: After performing a (very small) EDA of the dataset, we built a model ([reference tutorial](https://www.kaggle.com/sriharshavogeti/collaborative-recommender-system-on-goodreads)) to predict five books from a user’s choice of a book preference.      
   - The model used DictVectorizer. 
   

Result: The functionality recommends a book based on nearly one million ratings. The blog post associated with this Repo can be read [here](https://medium.com/@kwarmbein/yet-another-recommender-ad473a5894f9).