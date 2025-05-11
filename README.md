```java
public class AboutMe {
    String name, location, profession;
    int age;

    String[] favoriteSkills, otherSkills, hobbies, education, programs;

    public AboutMe() {
        this.name = "André Luís Onyszko";
        this.age = 20;
        this.location = "Dois Vizinhos, Brazil";
        this.profession = "Software Engineering Student";

        this.favoriteSkills = new String[] {
            "HTML", "CSS", "JavaScript", "React", "Java", "SQL"
        };

        this.otherSkills = new String[] {
            "C", "Python", "Bootstrap", "Git"
        };

        this.hobbies = new String[] {
            "Building personal projects",
            "Watching hardware-related videos",
            "Playing video games",
            "Watching movies and TV series"
        };

        this.education = new String[] {
            "Technical High School in Informatics - IFPR",
            "Bachelor’s Degree in Software Engineering - UTFPR",
            "English Course - Wizard (5 years)"
        };

        this.programs = new String[]{
            "UOL Compass scholarship and professional training program"
        };
    }
}
```
