```go
package main

// samuel teixeira · head of technology @ buildbox
// 11 years in · leads 46 by serving them · ships for ~7M

type Human struct{ since int }

func (h Human) learn() Human {
	return h // a slightly better version of itself
}

func main() {
	me := Human{since: 2014}

	for {
		me = me.learn() // when this loop exits, so do i
	}
}
```

<sub><i>// you're only seeing what renders</i></sub>

<sub>[linkedin](https://www.linkedin.com/in/samuelteixeira1337/)</sub>

<!-- eW91IHJlYWQgdGhlIHNvdXJjZS4gdGhhdCdzIHRoZSBjdXJpb3NpdHkgaSBsb29rIGZvci4gLT4gc2FtdWVsQGJ1aWxkYm94LmNvbS5icg== -->
