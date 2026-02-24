<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00ADD8&center=true&vCenter=true&width=600&lines=%3E+_whoami;;%3E+_Chavs+-+Full+Stack+Engineer;;%3E+_Building+systems+with+Go+%26+React;;%3E+_Based+in+Almaty,+KZ" alt="Typing SVG" />
</div>

<br/>

### 👨‍💻 `profile.go`
Я создаю надежные системы и современные интерфейсы. Вместо долгих описаний — структуры данных.

```go
package main

type Developer struct {
	Name       string
	Role       string
	Location   string
	Focus      []string
	Status     string
}

func initProfile() Developer {
	return Developer{
		Name:     "Chavs",
		Role:     "Full Stack Engineer",
		Location: "Almaty, Kazakhstan 🇰🇿",
		Focus:    []string{"High-Load Backend", "Modern Frontend", "DevOps"},
		Status:   "Open to interesting challenges & networking",
	}
}
