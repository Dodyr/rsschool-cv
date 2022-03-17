## Mikhail Arapov

### Contacts
- __Email__: misha.arapov@gmail.com
- __Tel__: +79601204660
- __GitHub__: @Dodyr

### About Myself
I was interested in programming for a long time, my father is a programmer, so he always told me about it, making me curious. Later I entered the univercity, where I studied C++ among other things, it was interesting and fun. Today I want to work as a developer and, I guess, I will.

### Skills
C++, Python, GitHub, HTML5, CSS3, VS Code, Visual Studio 2019, JS Basics

### Code samples
```C++
void sort_(Sorter& sorter, Hash_table& table)
{
    auto cmp = [&table](std::string a, std::string b)->bool {
        bool founda, foundb;
        Publication* pa = table.Find(a, founda);
        Publication* pb = table.Find(b, foundb);
        return pa->GetNPages() < pb->GetNPages(); 
    };
    sorter.sort(cmp);
}
  ```
### Experience
- CS50 by Garvard
- Python course
- HTML and CSS course
- ...

### Education
- Voronezh State Univercuty (mechanics and mathmetics)

### English 
Level is C1
