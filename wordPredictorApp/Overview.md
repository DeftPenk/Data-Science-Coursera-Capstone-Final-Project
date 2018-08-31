This application is developed as part of the **Coursera's Data Science Capstone: Final Project**. In this capstone, we will be applying data science in the area of natural language processing. The project is sponsored by SwiftKey.

The purpose of the project is to create text-prediction application with R Shiny package that predicts words using a natural language processing model i.e. creating an application based on a predictive model for text. Given a word or phrase as input, the application will try to predict the next word, similar to the way most smart phone keyboards are implemented today using the technology of Swiftkey. The predictive model will be trained using a corpus, a collection of written texts, called the HC Corpora which has been filtered by language.

### Steps
1. Upon initial load up of the application, **"NULL"** will be displayed at the Predicted Next Word textbox.
2. User may then enter a partially complete sentence to begin the next word prediction.


### Results
1. Next word predicted is shown at the Predicted Next Word textbox.
2. Information on the n-gram backoff algorithm used to predict is shown as indication.

#### Note:
The source codes for ui.R and server.R files are also available on the [GitHub repo](https://github.com/badal2017/Capstone)

Presentation Slide decks are available on the [RPubs page](https://rpubs.com/badalchowdhury/capstone)