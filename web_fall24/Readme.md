### Phân tích HTML:

1. Phân tích layout tổng quát, chia thành từng block.
2. Phân tích từng block một.
3. Bắt đầu code cho từng block. Làm HTML trước, xong thêm style vào sau.

### Bộ quy tắc thần thánh:

1. Từ trên xuống dưới. (layout tổng quát, chia block)
2. Từ ngoài vào trong:
   1. Dùng `container` hay `container-fluid`
   2. Nếu có container thì dùng thêm row.
3. Từ trái sang phải. (xác định các columns, nếu có row).

```
body
│
├── header
│   ├── section.top-bar
│   │     ├── img src
│   │     ├── h1 Pet thu cung
│   │     ├── h2 Cham soc thu cung cua ban
│   ├── nav.top-nav
│   │     ├── ul > 5 li > a href #
├── main
│   ├── section.hero
│   ├── section.services
│   └── section.form
└── footer
    └── section.app-footer
```

body
header
section.top-bar
nav.top-nav
main  
 section.hero
section.about
section.facts
footer
section.app-footer



Readme.md
body
    header
        section.top-bar
            container 
             row
                col:ul > li > a
                col: button
        nav.top-nav
            container
                row
                    col: img logo
                    col: menu ul > li > a
                    col: icon search

    main
        section.hero
        section.about
        section.facts
    footer
        section.app-footer