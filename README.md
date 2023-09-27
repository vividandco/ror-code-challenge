Press Release Manager - Code Challenge
======================================

Welcome to the Press Release Manager challenge. Your task is to build a Rails app to evaluate your skills in back-end development, data modeling, validation, testing, and authentication.

### Goal

Develop a Rails app for managing press releases. The application should allow users with different roles to create and manage press releases, publishers, and organizations.

Steps:
------

1.  **GitHub:**

    -   Initialize a repository named `press-release-manager` on GitHub.
    -   Commit regularly with clear messages.
      
2.  **Rails App:**

    -   Create a new Rails app.
    
3.  **Data Models:**

    -   `User`: Attributes should include `email`, `password`, and `role`.
    -   `PressRelease`: Attributes like `title`, `content`, `publish_date`, and a foreign key for association with `Organization`.
    -   `Publisher`: Attributes like `name` and `description`.
    -   `Organization`: Attributes like `name`, `description`, and others you deem necessary.
    -   Specify the associations among the models as needed.
      
4.  **Controllers:**

    -   Write controllers for each model ensuring they can be accessed from remote clients.
      
5.  **Validations:**

    -   Add necessary validations to each model.
      
6.  **Authentication:**

    -   Implement user authentication. You're free to use any reasonable method or gem (e.g., Devise, JWT).
      
7.  **Testing with RSPEC:**

    -   Write unit tests using RSPEC for all your models, controllers, and any additional services you might implement.
      
8.  **Creativity:**

    -   Implement a couple features that show off your creativity and depth of understanding of Rails.
