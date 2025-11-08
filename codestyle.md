# Frontend Code Style Guide

This document outlines the coding standards and best practices for the Contact Management System frontend.

## HTML
- **Semantic Markup**: Use appropriate HTML5 semantic elements (header, nav, main, section, article, footer)
- **Indentation**: Use 2 spaces for indentation
- **Tag Closure**: Close all HTML tags properly
- **Case Sensitivity**: Use lowercase for tag names and attributes
- **Attribute Quotes**: Use double quotes for attribute values
- **Form Elements**: Always associate labels with form controls using for/id attributes
- **Comments**: Add comments to explain complex sections of HTML
- **Accessibility**: Ensure proper ARIA attributes are used where necessary
- **Image Optimization**: Include appropriate alt text for all images and optimize file sizes

## CSS
- **Naming Convention**: Use meaningful class names and follow BEM (Block, Element, Modifier) where appropriate
- **Organization**: Group related styles together and use comments to separate sections
- **Bootstrap**: Prefer Bootstrap utility classes over custom CSS when possible
- **Specificity**: Avoid using !important; instead, use more specific selectors
- **Colors**: Define a consistent color palette and use variables where applicable
- **Typography**: Maintain consistent font sizes, weights, and spacing
- **Whitespace**: Use whitespace to improve readability
- **Responsive Design**: Implement responsive styles using Bootstrap breakpoints

## JavaScript
- **ES6+ Features**: Use modern JavaScript features (arrow functions, template literals, let/const)
- **Naming Conventions**: Use camelCase for variables and functions, PascalCase for classes
- **Comments**: Add comments to explain complex logic and functions
- **Error Handling**: Implement proper error handling with try/catch blocks
- **Asynchronous Operations**: Use async/await for fetch requests and other asynchronous operations
- **DOM Manipulation**: Minimize direct DOM manipulation; use efficient selectors
- **Modularity**: Organize code into logical functions and modules
- **Variable Declarations**: Use const by default, let when reassignment is needed
- **String Handling**: Prefer template literals over concatenation
- **API Communication**: Centralize API calls and handle responses consistently

## Performance Optimization
- **Lazy Loading**: Implement lazy loading for images and heavy content
- **Minification**: Minify CSS and JavaScript files for production
- **Caching**: Leverage browser caching where appropriate
- **Network Requests**: Minimize the number of HTTP requests

## Code Organization
- **Separation of Concerns**: Keep HTML structure, CSS styling, and JavaScript behavior separate as much as possible
- **Grouping**: Group related functions and code blocks together
- **Ordering**: Place function declarations before their usage

## Commit Messages
- Write clear, concise commit messages describing the changes made
- Use imperative mood ("Add feature" rather than "Added feature")
- Include relevant context in commit messages
