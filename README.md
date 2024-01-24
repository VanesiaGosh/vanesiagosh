# VanesiaGosh - Data Analyst

```python
def main():
    print("Hello, I'm VanesiaGosh, a data analyst!")
    print("I'm passionate about deriving insights from data.")
    print("Feel free to explore my data analysis projects below.")

if __name__ == "__main__":
    main()
class VanesiaGosh:
    def __init__(self):
        self.role = "Data Analyst"
        self.expertise = ["Data Analysis", "Data Visualization", "Statistical Analysis"]
    
    def display_info(self):
        print(f"I'm a {self.role} skilled in:")
        for skill in self.expertise:
            print(f"- {skill}")
class DataAnalysisProjects:
    def __init__(self):
        self.projects = [
            {"name": "Project One", "description": "Brief description of the first data analysis project."},
            {"name": "Project Two", "description": "Brief description of the second data analysis project."}
        ]

    def display_projects(self):
        print("Explore my data analysis projects:")
        for project in self.projects:
            print(f"1. [{project['name']}]({project['link']}): {project['description']}")
class Skills:
    def __init__(self):
        self.skills = ["Data Analysis", "Data Visualization", "Statistical Analysis", "Data Cleaning and Preprocessing"]

    def display_skills(self):
        print("Key Skills:")
        for skill in self.skills:
            print(f"- {skill}")
class ContactInfo:
    def __init__(self):
        self.email = "your-email@example.com"
        self.linkedin = "https://www.linkedin.com/in/your-linkedin-profile"
        self.twitter = "https://twitter.com/your-twitter-handle"

    def display_contact_info(self):
        print("Contact Me:")
        print(f"- 📧 Email: [{self.email}](mailto:{self.email})")
        print(f"- 💼 LinkedIn: [LinkedIn Profile]({self.linkedin})")
        print(f"- 🐦 Twitter: [@{self.twitter}](https://twitter.com/{self.twitter})")
if __name__ == "__main__":
    vanesia_gosh = VanesiaGosh()
    data_projects = DataAnalysisProjects()
    skills = Skills()
    contact_info = ContactInfo()

    vanesia_gosh.display_info()
    data_projects.display_projects()
    skills.display_skills()
    contact_info.display_contact_info()
