

```cpp
#include <iostream>

using namespace std;

class Article {
private:
    string title;
    string content;
    string author;
public:
    Article(string t, string c, string a) {
        title = t;
        content = c;
        author = a;
    }

    void display() {
        cout << "Title: " << title << endl;
        cout << "Content: " << content << endl;
        cout << "Author: " << author << endl;
        cout << "-----------------------" << endl;
    }
};

int main() {
    // 创建博客文章
    Article article1("Hello World", "This is my first article.", "John Doe");
    Article article2("Introduction to C++", "C++ is a powerful programming language.", "Jane Smith");

    // 显示博客文章
    article1.display();
    article2.display();

    return 0;
}
```

