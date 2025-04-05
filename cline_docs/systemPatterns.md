# System Patterns

## How the System is Built

This system consists of a single static HTML file styled with an associated CSS file. It is designed for direct viewing and printing from a web browser.

## Key Technical Decisions

- **Static HTML:** Chosen for simplicity, portability, and ease of printing. No server-side processing is required.
- **External CSS:** Styling is separated into a CSS file for better organization and maintainability.
- **Print-Optimized CSS:** Specific styles will be included to ensure the page looks good when printed (e.g., hiding unnecessary elements, ensuring text readability).

## Architecture Patterns

- **Single Page Application (Static):** The entire price list is contained within one HTML document.
- **Separation of Concerns:** HTML for structure, CSS for presentation.