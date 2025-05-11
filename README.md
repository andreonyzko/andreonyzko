```java
public class AboutMe {
    private String name, location, profession;
    private int age;

    private String[] favoriteSkills, otherSkills, hobbies, education, programParticipation;

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

        this.programParticipation = "Participant in the UOL Compass scholarship and professional training program";
    }
}
```
