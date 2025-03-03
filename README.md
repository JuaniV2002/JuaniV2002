```python
class JuaniVillanueva:
    def __init__(self):
        self.name = "Juani Villanueva"
        self.location = "Argentina"
        self.pursuit = "Computer Science degree"
        self.experience = "Moodle developer"
        self.languages = ["English", "Spanish"]
        self.technologies = ["Flutter", "Moodle", "MySQL/PostgreSQL", "Firebase", "Docker", "Git/GitHub", "Xcode/Android Studio"]

    def __str__(self):
        return (
            f"Hey there! I'm {self.name} from {self.location}, pursuing a {self.pursuit}.\n"
            f"I'm currently working as a {self.experience} at Universidad Nacional de Río Cuarto"
            f"Languages: {', '.join(self.languages)}\n"
            f"Technologies: {', '.join(self.technologies)}\n"
            "Feel free to explore my repositories and connect with me!"
        )
        
# Usage
profile = JuaniVillanueva()
print(profile)
```
