```java
@Slf4j
@Data
@AllArgsConstructor
@NoArgsConstructor
public class InformationTech {
    private String name;
    private String role;
    private List<String> spokenLanguages;

    public void writeToFile(String filename) {
        String text = "Name: " + this.name + "\n"
                    + "Role: " + this.role + "\n"
                    + "Spoken Languages: " + this.getSpokenLanguagesString() + "\n"
                    + "Thanks for dropping by, hope you find some of my work interesting.\n";
        try {
            Files.write(Paths.get(filename), text.getBytes());
        } catch (IOException e) {
            log.error("Error generating the file", e.getMessage());
        }
    }

    public static void main(String[] args) {
        InformationTech informationTech = new informationTech(
            "Guilherme Maciel",
            "Information Technology",
            Arrays.asList("Portuguese", "English")
        );
        informationTech.writeToFile("guilherme-maciel-info.txt");
    }
}
```

 <div> 
  <a href = "mailto:guilhermesouzamaciel1@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/guilherme-souza-8b527a258/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>

## These are the technologies I usually work with
<div>
 <img align="center" alt="postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
 <img align="center" alt="intelliJ" src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white"/>
 <img align="center" alt="html5" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
 <img align="center" alt="html5" src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
 <img align="center" alt="html5" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
</div>

<br>

<div align="center">
  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dyastrophism&layout=compact&bg_color=1e1e2e&text_color=cdd6f4&icon_color=cba6f7&title_color=94e2d5)
</div>

<div align="center">

[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=lzh692e0t4aryx95bxpbvzhom&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false)](https://github.com/kittinan/spotify-github-profile)
</div>

