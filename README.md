<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=260&color=0:020617,40:0f766e,100:7c3aed&text=KIM%20CHHORNG&fontColor=ffffff&fontSize=58&animation=twinkling&desc=Backend%20Engineer%20%C2%B7%20Golang%20%C2%B7%20Fintech%20Systems&descSize=18&descAlignY=64" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2600&pause=800&color=22D3EE&center=true&vCenter=true&width=760&lines=Backend+Engineer+from+Cambodia+%F0%9F%87%B0%F0%9F%87%AD;Building+payment%2C+card%2C+and+webhook+systems;Golang+%7C+PostgreSQL+%7C+Redis+%7C+Microservices;I+like+boring+systems+that+work+in+production" />

<br />

<img src="https://komarev.com/ghpvc/?username=kimchhorng99&style=for-the-badge&color=0ea5e9" />
<img src="https://img.shields.io/badge/Open%20to-Backend%20Roles-22c55e?style=for-the-badge" />
<img src="https://img.shields.io/badge/Focus-Fintech%20Backend-7c3aed?style=for-the-badge" />

</div>

---

```go
package main

import "fmt"

type Engineer struct {
	Name      string
	Location  string
	Role      string
	Focus     []string
	Stack     []string
	Belief    string
}

func main() {
	me := Engineer{
		Name:     "Kim Chhorng",
		Location: "Cambodia 🇰🇭",
		Role:     "Backend Engineer",
		Focus: []string{
			"payment systems",
			"card platform",
			"webhooks",
			"database migrations",
			"clean backend architecture",
		},
		Stack: []string{
			"Go",
			"PostgreSQL",
			"Redis",
			"Docker",
			"REST APIs",
			"GORM",
		},
		Belief: "Simple code. Clear schema. Reliable production.",
	}

	fmt.Printf("%+v\n", me)
}
