```cpp
int main() {
    SoftwareEngineer mihaibc;
    mihaibc.setAbout("Mihai Baluta-Cujba", "Expleo", "Head of AI Solutions DET RO | Team Leader | DevOps Process & Practice Lead")
          .addTechnologies({
              "Kotlin", "C++", "Python", "Azure", "CI/CD",
              "Java", "C#", "Objective-C", "Swift", "Flutter",
              "Docker", "Azure DevOps", "Machine Learning",
              "AI Solution Architecture",
              "Clean Architecture", "Microservices", "MVVM",
              "Systems Development",
              "Algorithms", "Data Structures"
          })
          .setLinks("https://www.linkedin.com/in/mihaibc/", 
                    "https://stackoverflow.com/users/8208808/mihaibc", 
                    "https://github.com/mihaibc",
                    "https://bacumi.dev/");

    mihaibc.display();
    return 0;
}
```