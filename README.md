# FinWise SPA

FinWise is a simple Single Page Application (SPA) for personal finance management. It includes Dashboard, Transactions, Budget Planner, and Profile pages, all styled with Tailwind CSS.

## Features

- Dashboard overview with accounts and metrics
- Transactions list and filters
- Budget planner and tracking
- Profile and settings page
- Responsive design using Tailwind CSS
- SPA navigation (no page reloads)

## Getting Started

1. **Clone or download this repository.**
2. **Open `index.html` in your browser.**
   - For best results, use a local web server (e.g. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code).
   - All navigation is handled client-side; no backend required.

## Project Structure

```
d:\FinWise\
│
├── index.html      # Main SPA entry point
├── dashboard.html  # (Legacy) Standalone dashboard page
├── transactions.html # (Legacy) Standalone transactions page
├── budget.html     # (Legacy) Standalone budget page
├── profile.html    # (Legacy) Standalone profile page
├── README.md       # This file
```

- **index.html** contains all SPA logic and content.
- Other HTML files are legacy and not needed for SPA usage.

## Customization

- To add or edit content, modify the corresponding sections in `index.html`.
- Tailwind CSS is loaded via CDN for rapid styling.

## License

This project is for educational/demo purposes. No license.
