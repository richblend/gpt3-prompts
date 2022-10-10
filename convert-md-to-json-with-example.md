### Using OpenAi to convert XML to JSON

By providing OpenAi with an example input and output (a form of simple training), it can convert the rest of the provided markdown in the exact specified format.



```
Convert markdown to JSON:

Input:
# Article heading
![alt-text](https://example.com/image.png)
Article summary.

Output:
[
    {
        "heading": "Article heading",
        "image": "https://example.com/image.png",
        "alt": "alt-text"
        "summary": "Article summary."
    }
]

Input:
# Lorem ipsum dolor sit amet.
![Picture of a bird](https://i.imgur.com/BZFHk5l.jpeg)
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In sollicitudin diam felis, congue blandit eros varius et. Curabitur aliquam non justo non posuere.

# Pellentesque habitant morbi tristique senectus.
![Picture of a small elephant](https://i.imgur.com/Up9TgbS.jpeg)
In auctor, orci sit amet iaculis feugiat, massa lectus auctor arcu, sit amet dapibus est metus sit amet orci. Nunc egestas risus mauris, eget tempus purus molestie in.

Output:

```


