# nlp-group-project
NLP Group Project

## Installing Dependencies:    
    * [NOTE] TensorFlow is currently not available for Python 3.8.0+
    ```bash
    pip install -r requirements.txt
    ``` 
## Downloading NLTK Corpuses:
    * Either run nltk_dl.py file or run the following line in a python executor:
    ```python
    import nltk
    nltk.download('stopwords')
    nltk.download('reuters')
    ```
    If nltk.download('corpus_name') conflicts causes an issue, you may also instead run this command and follow its navigation: 
    ```bash
    nltk.download_shell()
    ```

## Checkpoints:
* EDA
- [x] basics
- [ ] graphs

* Data Cleaning
- [ ] "keyword" column
    - [ ] tag and merge the ones with identical meanings (e.g. blow up/blew 	up)
- [ ] "location" column
    - [ ] standardiziing a location format e.g. "city, state, nation"
    - [ ] classify all meaningless entries will count towards "nan"
    - [ ] investigate and change specific addresses/locations 
- [ ] "text" column
    
