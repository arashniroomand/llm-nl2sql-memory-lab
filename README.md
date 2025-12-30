# Applied LLM Internship

Hands-on notebooks introducing core LLM system concepts through **NL2SQL** and **conversational memory**, designed for intern-level training and architectural understanding.

This repository focuses on helping interns move beyond simple prompt usage and understand how LLM-based systems are built in practice.

---

## 📌 Repository Goals

- Understand how **natural language interfaces** connect to structured databases
- Learn how **LLMs generate and validate SQL queries**
- Explore **memory mechanisms** for multi-turn conversational systems
- Build intuition for **LLM-based agents and system design**



## NL2SQL Structure

```
User Question
      │
      ▼
get_database_schema
      │
      ▼
generate_sql_query
      │
      ▼
validate_sql_query
      │
      ▼
execute_sql_query
      │
      ▼
fix_sql_error (if needed)
      │
      ▼
Provide Answer
```

<img src="img\nl2sql.avif" alt="My image" width="600" height="600" />


## Memory:

<img src="img\memory.webp" alt="My image" width="1000" height="600" />
