# Invoicing System

## Project Overview
The Invoicing System is a web-based application designed to generate professional invoices based on client details. Users can enter customer information, add multiple products, and select currency formats (USD or PHP) to produce a clear and printable invoice. The system streamlines the invoicing process, providing an intuitive interface that simplifies generating invoices.

## Objectives and Goals
- Create a functional web-based invoicing system.
- Allow users to input customer details and product information.
- Support multiple products and handle currency selection (USD or PHP).
- Provide printable invoices with a clear format and accurate calculations.
- Innovate by offering invoice templates for enhanced usability.

## Requirements

### Functional Requirements
- Generate invoices using client information such as name, email, phone number, and purchase date.
- Allow users to add multiple products with names and prices.
- Support two currency formats: US Dollar (USD) and Philippine Peso (PHP).
- Provide a clear, structured, and printable invoice display.
- Implement an interface for users to add additional products dynamically.

### Non-functional Requirements
- Efficient data entry and processing to minimize delays.
- User-friendly interface that is easy to navigate.
- Maintain data integrity by ensuring accurate and properly formatted information.
- Ensure cross-browser compatibility and responsive design.

### Technical Requirements
- Python 3.x, embedded within HTML using PyScript.
- GitHub for version control and hosting.
- Compatible with modern web browsers.

### User Requirements
- Users should enter customer name, email, phone number, and purchase date.
- Input the product name and price for each item, with an option to add multiple products.
- Choose the preferred currency format (USD or PHP) before generating the invoice.

## Design

### System Architecture
The system follows a modular architecture, separating input handling, invoice generation, and output display into distinct components. The Python logic embedded within the HTML handles calculations, while the HTML and CSS manage the layout and design.

### Module Design
- **User Input Module**: Collects customer details and product information.
- **Invoice Generation Module**: Processes data, formats it, and calculates totals.
- **Display Module**: Outputs the generated invoice in a structured and printable format.
- **Currency Handling Module**: Adjusts prices based on the selected currency.

### User Interface Design
- Input fields for customer details (name, email, phone, and date).
- Dropdown menu for currency selection (USD or PHP).
- Input fields for adding products and prices.
- Button to add more products dynamically.
- "Generate Invoice" button to display the formatted invoice.

## Implementation

### Coding Standards
- Follow PEP8 guidelines for Python code.
- Consistent indentation and naming conventions.
- Use comments to describe each function and code block.

### Version Control Strategy
- GitHub for version control.
- Single main branch for stable releases.
- Feature branches for adding new functionalities and fixing bugs.
- Regular commits for incremental updates and tracking changes.

### Deployment Procedure
The program is hosted on GitHub and embedded in an HTML file. The invoicing logic runs using PyScript, enabling it to execute directly within a web environment for easy accessibility.

## Service Improvement

### Future Enhancements
- Enable users to download the generated invoice as a file (e.g., PDF) for easier sharing and record-keeping.
- Extend the system to allow for detailed invoice previews or downloads before finalizing.
- Add support for additional currency types and integrate actual currency conversion features instead of relying on presets.

## Appendix

### Glossary of Terms
- **Invoice**: A document issued by a seller to a buyer listing the products or services provided, along with prices, quantities, and payment terms.
- **PyScript**: A tool that allows Python code to run directly in a web browser by integrating it within HTML, enabling Python use for front-end web development tasks.
- **Front-end**: The part of a website that users interact with, typically involving HTML, CSS, and JavaScript (or PyScript in this case).
- **GitHub**: A platform for hosting and version control of code repositories, enabling developers to manage and share projects.
- **PEP8**: A style guide for Python code that promotes readability and consistency.
- **Currency Conversion**: The process of converting one currency to another based on exchange rates.

### References
- **Cody** - AI tool used to help convert the Python program into PyScript.
- **[Invoice Simple](https://www.invoicesimple.com/invoice-generator)** - Inspiration for designing the invoice system.
- **[Investopedia](https://www.investopedia.com/terms/i/invoice.asp)** - Used for understanding invoicing concepts.
- **W3C Standards** - Guidelines and standards for web development, including HTML and CSS, from the World Wide Web Consortium.
- **Python Enhancement Proposals (PEPs)** - Standards for writing Python code, ensuring readability and maintainability (e.g., PEP 8 for code style).

## Repository and Live Server
- **GitHub Repository**: [Invoicing System](https://github.com/NotKaede-11/Invoicing.System)
- **Live Server**: [Invoicing System Live](https://notkaede-11.github.io/Invoicing.System/)
