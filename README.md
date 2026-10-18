<table>
<tr>
<td width="55%" valign="top">

```go
package main

type SoftwareEngineer struct {
    Name       string
    Role       string
    Studying   string
    Language   string
  
}

func (s *SoftwareEngineer) BuildSomethingCool() {
	for {
		s.Learn()
		s.Build()
		s.Ship()
		// Stay curious. Keep creating.
	}
}

func main() {
    me := SoftwareEngineer{
        Name:     "Enguunbayar",
        Role:     "Software Engineer",
        Studying: "SE @ National University of Mongolia",
        Language: "Go , ... ",
    }
    me.BuildSomethingCool()
}
```

</td>
<td width="45%" valign="top">

```
        ┌──────────────────────┐
        │  ~/enguunbayar $ _   │
        └──────────────────────┘
              ╱│                
             ╱ │  ┌──────────┐  
            ╱  │  │ 01001000 │  
           ╱   │  │ 01001001 │  
          ╱    │  └──────────┘  
         ╱     │                
    ┌────────────────┐          
    │  ▓▓▓▓▓▓▓▓▓▓▓▓  │          
    │  ▓  >_    ▓▓  │          
    │  ▓▓▓▓▓▓▓▓▓▓▓▓  │          
    └────────────────┘          
     ░░░░░░░░░░░░░░░░           
    ░░░░░░░░░░░░░░░░░░          
```

</td>
</tr>
</table>
