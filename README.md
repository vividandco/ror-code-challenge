Press Release Manager - Code Challenge
======================================

Welcome to the Press Release Manager challenge. Your task is to build a Ruby on Rails app to evaluate your skills in full stack Rails development, data modeling, validation, testing, and authentication.

### Goal

Develop a Rails app for managing press releases. The application should allow users with different roles to create and manage press releases, publishers, and organizations.

Stack to be Used:
------
- Ruby: >= 3.3.0
- Rails: >= 7.1
- PostgreSQL: >= 15
- Sidekiq: >= 7
- Redis
- Hotwire: Use Turbo and Stimulus for front-end interactions.
- ViewComponent (Optional): For advanced view encapsulation.

Ensure your application is compatible with these technologies to demonstrate your proficiency with up-to-date development practices.


Steps:
------

1.  **GitHub:**

    -   Initialize a repository named `press-release-manager` on GitHub.
    -   Commit regularly with clear messages.
      
2.  **Rails App:**

    -   Create a new Rails app.
    
3.  **Data Models:**

    -   `User`: Attributes should include `email`, `password`, and `role`.
    -   `PressRelease`: Attributes like `title`, `content`, `publish_date`.
    -   `Publisher`: Attributes like `name` and `description`.
    -   `Organization`: Attributes like `name`, `description`,
    -   To all data models, add other attributes you deem necessary.
    -   Specify the associations among the models as needed.
      
4.  **Controllers:**

    -   Write controllers for each model ensuring they can be accessed from remote clients.
      
5.  **Validations:**

    -   Add necessary validations to each model.
      
6.  **Authentication:**

    -   Implement user authentication. You're free to use any reasonable method or gem (e.g., Devise, JWT).
      
7.  **Front-end Views with Hotwire:**

    - Implement at least one feature using Ruby on Rails Hotwire, integrating both Stimulus and Turbo. This will demonstrate your ability to enhance the user experience with real-time updates and interactive interfaces.

8.  **Scheduled Release Feature:**

    -   Implement a feature to schedule the release of press releases using Sidekiq. This should allow users to set a future date and time for a press release to be published automatically.

9.  **Testing with RSPEC:**

    -   Write unit tests using RSPEC for all your models, controllers, and any additional services you might implement.
      
9.  **Creativity:**

    - Implement a couple features that show off your creativity and depth of understanding of Rails.
