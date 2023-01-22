# Fitzypop's Profile
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
![vs code](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code)
![python](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python)
![rust](https://img.shields.io/badge/Code-Rust-informational?style=flat&logo=rust)
![js](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript)
![ts](https://img.shields.io/badge/Code-TypeScript-informational?style=flat&logo=typescript)
![react](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react)
![kitty](https://img.shields.io/badge/TTY-Kitty-informational?style=flat&logo=gnu-bash)
![fish](https://img.shields.io/badge/Shell-Fish-informational?style=flat&logo=gnu-bash)
![starship](https://img.shields.io/badge/Prompt-Starship-informational?style=flat&logo=gnu-bash)
![postgresql](https://img.shields.io/badge/Tools-PostgreSQL-informational?style=flat&logo=postgresql)
![docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker)
![deno](https://img.shields.io/badge/Tools-Deno-informational?style=flat&logo=deno)

<!-- [![Made with Fresh](https://fresh.deno.dev/fresh-badge-dark.svg)](https://fresh.deno.dev) -->

<!-- ![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=6aa6f8) -->

```rust
#[derive(Debug)]
struct SomeDude<'a> {
    name: &'a str,
    current_role: &'a str,
    hobbies: Vec<&'a str>,
}

impl Default for SoftwareEngineer<'_> {
    fn default() -> Self {
        Self {
            name: "Fitzypop",
            current_role: "Software Engineer",
            hobbies: vec![
                "coding",
                "music and gear",
                "craft beer and microbrews",
                "weightlifting",
            ],
        }
    }
}

fn main() {
    println!("Hello there nerds 🤙. Welcome to my profile!");
    
    let me = SomeDude::default();
    println!("{:?}", me);
}
```

```python
from dataclasses import dataclass, field

@dataclass
class SomeDude:
    name: str = "Fitzypop"
    role: str = "Software Engineer"
    hobbies: list[str] = field(
        default_factory=lambda: [
            "coding",
            "music and gear",
            "craft beer and microbrews",
            "weightlifting",
        ]
    )

    def say_hi(self):
        print(
            "Thanks for visiting my page! I hope you find some of my work interesting."
        )

if __name__ == "__main__":
    me = SomeDude()
    print(me)
    me.say_hi()
```
