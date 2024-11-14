## Module 13 Challenge: Candidate Search

TypeScript can enhance the overall development experience with React, leading to more reliable, maintainable, and scalable applications.

This week, we completed a candidate search application that calls the GitHub API and renders data in the browser.

## User Story

```md
AS AN employer
I WANT a candidate search application
SO THAT I can hire the best candidates
```

## Acceptance Criteria

```md
GIVEN a candidate search application
WHEN the candidate search page loads
THEN the information for one candidate should be displayed, including the candidate's name, username, location, avatar, email, html_url, and company
WHEN I click the "+" button
THEN the candidate should be saved to the list of potential candidates and the next candidate's information should be displayed
WHEN I click the "-" button
THEN the next candidate's information should be displayed without saving the current candidate
WHEN there are no candidates available to review
THEN an appropriate message should be shown indicating no more candidates are available
WHEN the potential candidates page loads
THEN the user should see a list of previously saved potential candidates with their name, username, location, avatar, email, html_url, and company
WHEN the page reloads
THEN the list of potential candidates should persist and be available for viewing
WHEN there are no potential candidates
THEN an appropriate message should be displayed indicating no candidates have been accepted
WHEN I click the "-" button
THEN the next candidate's information should be displayed without saving the current candidate
```

## Mock-Up

The following images show the web application's appearance and functionality:

![The candidate search page displays a candidate's information and allows the user to accept or reject the candidate and view a list of potential candidates.](./Assets/13-01-candidate_search_homepage.png)

![The potential candidates page displays a list of potential candidates and allows the user to reject a candidate.](./Assets/13-02-candidate_search_potential_candidates.png)
