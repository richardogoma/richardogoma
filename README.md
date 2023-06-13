```python
# Define the user's information using a dictionary
user_info = {
    'learning': 'data engineering',
    'working_on': 'building a data engineering portfolio',
    'collaboration_interest': 'developing data engineering related projects',
    'topics': ['Data Quality Management', 'Business Intelligence & Data Analytics', 'ETL', 'SQL', 'Python', 'Bash']
}

# Print the user's information
print("Hi there 👋")
print(f"- 🌱 I’m currently learning {user_info['learning']}")
print(f"- 🔭 I’m currently working on {user_info['working_on']}")
print(f"- 👯 I’m looking to collaborate on {user_info['collaboration_interest']}")
print("- 💬 Ask me about:")
for topic in user_info['topics']:
    print(f"  - {topic}")
```
