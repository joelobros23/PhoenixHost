# Project Plan: PhoenixHost

**Description:** A simplified web hosting platform built on Ruby on Rails, providing basic domain management and user authentication.


## Development Goals

- [ ] Configure tailwindcss-rails gem and create a basic layout using Tailwind CSS classes in application.html.erb and application.tailwind.css.
- [ ] Implement Domain model validations: presence and uniqueness of the domain name within a user's domains.
- [ ] Customize the Domain scaffold views (index, show, new, edit) to use Tailwind CSS for improved styling and user experience.
- [ ] Implement user authentication and authorization using Devise. Ensure that only logged-in users can manage their domains.
- [ ] Modify the Domains controller to associate newly created domains with the currently logged-in user (current_user), ensuring ownership.
- [ ] Add a domain status enum or similar to allow users to easily manage if their domain is live, inactive, or pending.
- [ ] Add a user dashboard to display the logged-in user's domains and a welcome message.
- [ ] Implement basic plan options (e.g., 'Basic', 'Premium', 'Enterprise') with associated features (e.g., storage, bandwidth).
- [ ] Add a simple pricing page to showcase the different hosting plans and their features.
- [ ] Implement email confirmation using Devise to verify user accounts upon registration.
- [ ] Customize Devise views for a better user experience (login, registration, password reset, etc.).
- [ ] Add a simple contact form using a gem like 'letter_opener_web' for local development.
