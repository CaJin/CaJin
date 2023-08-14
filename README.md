

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

这是一个简单的C++程序，创建了一个`Article`类来表示博客文章，其中包含标题、内容和作者属性。`display`函数用于显示文章的信息。

你可以根据需要扩展这个模板，添加更多的功能和布局样式。如果你有其他具体的要求或需要进一步的帮助，请随时告诉我。
