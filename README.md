### Hi there 👋

```go
package Life

import "Parents"

type Me struct {
    Name     string
    Age      int
    Location string
    Hobbies  []string
    AboutMe  string
    Experience string
}

func main() {
    me := Me{
        Name:     "Верещака Артем",
        Age:      33,
        Location: "Россия, Самара --> Санкт-Петербург",
        Hobbies:  []string{"Освоение Golang", "Warhammer40k", "Пытаюсь в написание статей"},
        AboutMe:  "Я здесь, чтобы стать хорошим разработчиком.",
        Experience: "Support инженер в МТС, ползу в сторону го-разработки",
    }
}
