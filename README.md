# Backend Challenge – Restaurant Review API

Welcome! This challenge is designed to evaluate your backend skills using **Java + Spring Boot**, focusing on REST API design, database management, and basic external API integration.

---

## Objective

Build a simple REST API that allows users to add restaurants, write reviews, and get basic recommendations. The mobile app will consume this API to display restaurants and reviews.

You are responsible for defining the API structure and implementing the core functionality.

---

## Functional Requirements

- Add restaurants with basic info (name, cuisine, location)
- Create and read restaurant reviews with ratings (1-5 stars)
- Calculate average ratings for restaurants
- Get simple restaurant recommendations (most rated, highest rated)
- Basic search by restaurant name or cuisine type

---

## Technical Expectations

- Use **Java 11+** with **Spring Boot** (API mode preferred)
- Use **PostgreSQL** as the database
- Use **async processing** (CompletableFuture or similar) for background jobs
- Provide a `README.md` with instructions to run and test the solution

---

## Notes

- You decide the data model structure and endpoint naming.
- You decide the logic for generating restaurant recommendations.
- You can mock complex integrations if needed (no penalty).
- Favor maintainability and clean architecture over completeness.

---

## Bonus Points

- Deploy to a public service (e.g., Render, Railway, Fly.io)
- Add AI-powered restaurant recommendations using LLM APIs (OpenAI, Anthropic, etc.)
- Include unit/integration tests
- Add request deduplication or retry logic
- Include rate limiting or basic input validation
- Return progress/status updates on async jobs if applicable

---

## Submission

1. Push your code to a **public GitHub repository**
2. Include instructions in a `README.md`
3. Share the link with us, along with any additional notes

```
Name:
Email:
GitHub Repository:
Demo URL (optional):
```

Good luck and have fun!