```cpp
#include <string>
#include <vector>
#include <map>

namespace justusemecnc {
class Profile {
public:
    auto getStatus() const -> std::string {
        return "Student — software & game developer, building a portfolio.";
    }

    auto getToolbox() const -> std::vector<std::string> {
        return {"C", "C++", "Rust", "Java", "Python"};
    }

    auto getFocusAreas() const -> std::vector<std::string> {
        return {
            "Software & game development",
            "System tools & workflow automation",
            "Server-side resources, mods & addons"
        };
    }

    auto getModding() const -> std::vector<std::string> {
        return {"Minecraft", "Roblox", "CitizenFX"};
    }

    auto getGameEngines() const -> std::vector<std::string> {
        return {"Unity (primary)", "Unreal Engine (learning)", "Godot (learning)"};
    }

    auto getContact() const -> std::map<std::string, std::string> {
        return {
            {"Email", "justusemecnc@gmail.com"},
            {"Telegram", "telegram.me/justusemecnc"}
        };
    }
};
}
```

<hr>

![GitHub Activity](https://github-readme-activity-graph.vercel.app/graph?username=justusemecnc&theme=react&hide_border=true&area=true&color=00fff7&line=ff00ff&point=ffffff&bg_color=0a0a0f)
