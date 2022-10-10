### Using OpenAi to convert XML to JSON

Try tweaking the prompt, adding `Replace "body" with "content".` to see if the corresponding JSON's field name will be changed.

```
Convert XML to JSON:

<posts>
  <post date="2022-01-01">
    <title>Post 1 title</title>
    <summary>Post 1 summary</summary>
    <body>Post 1 body</body>
    <author>Joe Bloggs</author>
  </post>
  <post date="2022-01-02">
    <title>Post 2 title</title>
    <summary>Post 2 summary</summary>
    <body>Post 2 body</body>
    <author>Joe Bloggs</author>
  </post>
  <post date="2022-01-03">
    <title>Post 3 title</title>
    <summary>Post 3 summary</summary>
    <body>Post 3 body</body>
    <author>Jane Doe</author>
  </post>
</posts>

```
