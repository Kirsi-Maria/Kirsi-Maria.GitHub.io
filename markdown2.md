## Exercise 1
Italic & Bold

Writing in Markdown is _not_ that hard!

I **will** complete these lessons!

"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"

If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

## Exercise 2
**_GenCode_**
The **first** well-known public presentation of markup languages in computer text processing was made by **William W. Tunnicliffe** at a conference in 1967, although he preferred to call it generic coding. It can be seen as a response to the emergence of programs such as **RUNOFF** that each used their own control notations, often specific to the target typesetting device. In the 1970s, Tunnicliffe led the development of a standard called GenCode for the publishing industry and later was the first chairman of the International Organization for Standardization committee that created SGML, the first standard descriptive markup language. Book designer Stanley Rice published speculation along similar lines in 1970.

**_Troff and nroff_**
Some early examples of computer markup languages available outside the publishing industry can be found in typesetting tools on Unix systems such as troff and nroff. In these systems, formatting commands were inserted into the document text so that typesetting software could format the text according to the editor's specifications. It was a trial and error iterative process to get a document printed correctly. Availability of **WYSIWYG** ("_what you see is what you get_") publishing software supplanted much use of these languages among casual users, though serious publishing work still uses markup to specify the non-visual structure of texts, and WYSIWYG editors now usually save documents in a markup-language-based format.

## Exercise 3
[![Karkeakarvainen mäyräkoira](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Wirehaired_Dachshund.jpg/1280px-Wirehaired_Dachshund.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ "You got Rickroll`d!")

## Exercise 4
```C#
public class Person{
  private string name;
  private int age;

  public Person(string initialName)
  {
    this.age = 0;
    this.name = initialName;
  }
  public void PrintPerson()
  {
    Console.WriteLine(this.name + ", age " + this.age + " years");
  }
  public void GrowOlder()
  {
    this.age = this.age + 1;
  }
}




