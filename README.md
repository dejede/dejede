<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,30,45&height=180&section=header&text=Hi%20There,%20I'm%20Dejede!&fontSize=32&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%" />
</div>

<div align="center">
  <p>🌐 <b>Network Engineer & Developer from Indonesia 🇮🇩</b></p>
  
  <!-- Badge Visitor & Followers Custom / Fake -->
  <p>
    <img src="https://img.shields.io/badge/Profile%20Views-13.37k-blueviolet?style=flat-square" alt="Profile Views" />
    <img src="https://img.shields.io/badge/Followers-1.33k-2CA5E0?style=flat-square&logo=github" alt="GitHub Followers" />
  </p>
</div>

---

### 💻 About Me

```go
package main

import "fmt"

type Dejede struct {
	Name      string
	Location  string
	Role      string
	Focus     []string
	Editor    string
	FunFact   string
}

func main() {
	me := Dejede{
		Name:      "Dejede",
		Location:  "Indonesia",
		Role:      "Network Engineer & Developer",
		Focus:     []string{"OpenWrt", "Web Development", "Scripting"},
		Editor:    "VS Code",
		FunFact:   "Turning coffee and config files into production-ready networks!",
	}

	fmt.Printf("Welcome to %s's profile! Let's build something awesome.\n", me.Name)
}
