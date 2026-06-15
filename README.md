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

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColor=0:00fff7,100:ff00ff&height=180&section=header&text=justusemecnc&fontSize=42&fontColor=fff&animation=twinkling"/>
