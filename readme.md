# Precium Technical Assessment

---

## Objective - VibeTools Web App
Build a simple AI tool directory web app that allows users to browse, add, and review listings of trendy and useful AI tools. Users should be able to view suggested tools, make their own submissions for tools they like, and post reviews on already listed tools. Their reviews should allow them to add their comments and provide a star rating for a tool, which can be used to derive a ranking for the directory. In this context the term "AI tools" may refer to models, IDE's, MCP's, a SaaS, etc.

---

## Tech Requirements
- **Backend**: .NET Core (C#)
- **Frontend**: React or Next.js (TypeScript ideal)
- **Database**: Any SQL DB
- No authentication/login required
- **Dockerize** for extra cred
> Outside of the above, there are no expectations. You can use which ever tools you like - any ORM, no ORM, component libraries, dotnet/frontend packages, etc. Feel free to show off cool tech you like. 

---

## Required Features
- View a suggested list of tools including name, ranking, and any other details you like.
- Click on a tool to view it's details and any associated reviews
- Review a tool from it's details page
- Search for tools
- Submit new tools
- Use the average of all of a tools ratings to determine a ranking for the list
- If the latest 5 reviews for a tool are all 5-stars, the tool should be marked as a community favorite. If the latest 5 reviews are all 1-star reviews, the tool should be hidden from suggestions.
- Styling is not of importance
> Feel free to improvise any additions you believe demonstrate your expertise

---

## Documentation
- Please provide us with some rough architectural diagrams for the system. Examples:
  - How the user would interact with the APIs
  - How the system would interact with any integrations/databases
  - How the system would be structured when hosted on a cloud provider

## Submission details
- Supply us with the URL to a public git repo with your submission
- Include a readme with setup instructions and anything you feel we should know
- We don't intend to take up too much of your time with this assessment. If you want to invest more time into an aspect of the project you feel demonstrates your strengths, feel free to do so, but please include some reasoning for your choice in the readme.

<!-- mention 'rubber duck' somewhere in your submission for brownie points -->
