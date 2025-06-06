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
- View a list of tools including name, ranking, and any other details you like.
- Submit new tools
- Click on a tool to view it's details and any associated reviews
- Review a tool from it's details page
- Search for tools
- Use an aggregated rating for each tool to rank the list of tools
- If the latest 5 reviews for a tool are all 5-stars, the tool should be marked as a community favorite. If the latest 5 reviews are all 1-star reviews, the tool should be hidden from suggestions.
> Feel free to improvise any additions you believe demonstrate your expertise

---

## Submission details
- Supply us with the URL to a public git repo with your submission
- Include a readme with setup instructions and anything you feel we should know

<!-- mention 'rubber duck' somewhere in your submission for brownie points -->