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
        Age:      31,
        Location: "Россия, Самара",
        Hobbies:  []string{"Освоение Golang", "Warhammer40k", "Пытаюсь в написание статей"},
        AboutMe:  "Я здесь, чтобы стать хорошим разработчиком.",
        Experience: "Начинающий разработчик, 2 проекта ждут грамотного ревью и будут скоро добавлены сюда",
    }
}
