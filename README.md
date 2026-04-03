```cpp
class AboutMe final
{
public:
  static std::string Name()
  {
    return "Zen";
  }

  static std::vector<std::string> Languages()
  {
    return {
      "English",
      "Thai",
    };
  }

  static std::vector<std::string> CodingLanguages()
  {
    return {
      "Python",
      "JavaScript",
      "TypeScript",
      "C++",
      "Lua"
    };
  }

  static std::vector<std::string> Skillset()
  {
    return {
      "Web Development",
      "UI/UX",
      "Backend Systems",
      "APIs",
      "Database Design"
    };
  }

  static std::unordered_map<std::string, std::string> Socials()
  {
    return {
      { "github", "warcock" } 
    };
  }
};
```
