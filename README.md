
# Spider Test Page

## Spider Graph:

```mermaid
graph
A(spider_test_page) --> B(spider_test_page/node1.html)
A(spider_test_page) --> C(spider_test_page/node2.html)
B --> D(spider_test_page/node1_1.html)
D --> C
D --> A
B --> C
```

```json
[
  {
    "url": "https://niortizva.github.io/spider_test_page",
    "points_to": [
      "https://niortizva.github.io/spider_test_page/node1.html",
      "https://niortizva.github.io/spider_test_page/node2.html"
    ]
  },
  {
    "url": "https://niortizva.github.io/spider_test_page/node1.html",
    "points_to": [
      "https://niortizva.github.io/spider_test_page/node1_1.html",
      "https://niortizva.github.io/spider_test_page/node2.html"
    ]
  },
  {
    "url": "https://niortizva.github.io/spider_test_page/node1_1.html",
    "points_to": [
      "https://niortizva.github.io/spider_test_page",
      "https://niortizva.github.io/spider_test_page/node2.html"
    ]
  },
  {
    "url": "https://niortizva.github.io/spider_test_page/node2.html",
    "points_to": [
      "https://niortizva.github.io/spider_test_page/node1_1.html"
    ]
  }
]
```
