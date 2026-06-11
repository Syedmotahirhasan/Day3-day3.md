# Day 3 - Role-Based Prompting

## What is Role-Based Prompting?
Role-Based Prompting means giving Claude a specific 
identity or persona before asking a question.
When you assign a role, Claude answers from that 
expert's point of view — making the response more 
focused, detailed, and useful.

## Normal Prompt Used
What are the most important things to 
consider when building a startup?
<img width="882" height="767" alt="Screenshot 2026-06-11 145656" src="https://github.com/user-attachments/assets/483acf48-d8f1-4cb5-868d-96452a6fd7d8" />



### Output Summary
- Gave very general advice
- No specific focus area
- Like reading a basic article
- Good for beginners but not deep enough

---

## Founder Persona Prompt
You are an experienced startup founder who 
has built and sold 3 companies. 
What are the most important things to 
consider when building a startup?

<img width="1078" height="902" alt="Screenshot 2026-06-11 145811" src="https://github.com/user-attachments/assets/40d34726-6714-4c24-97f1-9ec00d818b40" />


### Output Summary
- Focused on business strategy and vision
- Talked about finding the right co-founder
- Emphasized customer validation first
- Mentioned fundraising and investor relations
- Real-world practical advice

---

## Developer Persona Prompt
You are a senior software developer with 
10 years of experience in startups.
What are the most important things to 
consider when building a startup?

<img width="1028" height="876" alt="Screenshot 2026-06-11 150023" src="https://github.com/user-attachments/assets/f0c88245-5e27-45f8-a429-66171a8664f9" />

### Output Summary
- Focused on tech stack selection
- Talked about building MVP quickly
- Emphasized scalability and clean code
- Mentioned avoiding over-engineering early
- Technical and product focused advice

---

## Key Learnings
- Role-based prompts give more specific answers
- Different roles = completely different perspectives
- Expert role = expert level response
- Same question, 3 different answers — all useful!
- Always assign a role when you need expert advice

## Difference Observed
| | Normal | Founder | Developer |
|---|---|---|---|
| Focus | General | Business | Technical |
| Depth | Basic | Deep | Deep |
| Usefulness | ⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |

## Conclusion
Role-Based Prompting is a powerful technique.
Always tell Claude WHO it should be before 
asking WHAT you want to know!
