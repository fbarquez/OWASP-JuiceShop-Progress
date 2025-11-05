# Discover Score Board

## Challenge Info
- **Category:** Sensitive Data Exposure
- **Difficulty:** ★☆☆☆☆
- **OWASP Top 10:** A01:2021-Broken Access Control

## Objective
Find and access the Score Board page that shows all challenges.

## Methodology

### Step 1: Reconnaissance
- Explore the application navigation
- Check for hidden links or pages
- Review JavaScript files for clues

### Step 2: Common Locations
- Try `/score-board`
- Check main menu for hidden options
- Review network requests

### Step 3: Alternative Methods
- Check source code for comments
- Look for exposed API endpoints
- Try directory brute forcing (optional)
