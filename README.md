# Nlp Article Library

NLP Article Library application, a powerful software tool that uses natural language processing algorithms to analyze articles and provide automated article classification.
# Technologies Used

* Java
* Javascript
* HTML
* Maven
* Spring Boot
* Hibernate
* PostgreSQL

## Screenshot

![Output](https://github.com/dithiane/nlpApp/blob/main/src/main/resources/static/media/nlpLibrary1.png)
![Output](https://github.com/dithiane/nlpApp/blob/main/src/main/resources/static/media/nlpLibrary2.png)
![Output](https://github.com/dithiane/nlpApp/blob/main/src/main/resources/static/media/nlpLibrary3.png)

# Features

- User Registration and Authentication: Users can create an account and log in to access their article.
- Create and Edit Articles: Users can create new articles, edit existing articles.
- Search and Filter Articles: Users can search for specific articles.
- Edit the categories automatically generated by [MeaningCloud's API](https://www.meaningcloud.com/) solution for automated document classification.


# Installation

To run the NlpApplication, you need to have the following prerequisites:

- Java Development Kit (JDK) 8 or higher
- Maven
- API key for [MeaningCloud's API](https://www.meaningcloud.com/)

Follow these steps to install and run the application:
1. Clone the repository:
```bash
shell git clone https://github.com/dithiane/nlp-article-library.git
```
2. Navigate to the project directory:

```bash
shell cd nlp-article-library
```
3. Build the application using Maven
```bash
shell mvn clean install
```
4. Run the application
```bash
shell mvn spring-boot:run
```
The application will start running on `http://localhost:8080/index.html`.

# Usage

Once the NlpApplication is up and running, you can access it through your web browser. Here are the main functionalities:

- Register a new account or log in with an existing account.
- Create new articles by posting any text.
- View the articles.
- Sort the articles by categories.
- Edit or delete existing articles.
- Search for specific articles using keywords.
- Edit categories automatically generated by [MeaningCloud's API](https://www.meaningcloud.com/).