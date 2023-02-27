CÁC THẺ HTML CƠ BẢN
Thẻ div: bọc 1 khối nào đó bạn muốn
thẻ p: Hiển thị dưới dạng văn bản dài
thẻ h1-h6:Thẻ Tiêu đề từ lớn 1 đến nhỏ 6
thẻ a(link): thẻ đường dẫn (href: tạo đường link) (target="_blank"       rel="noopener noreferrer" tạo 1 trang mới và đường dẫn ở đây)
thẻ img: Hình ảnh (src: Đường dẫn Hình ảnh   alt: địa chỉ hình ảnh)
thẻ ol[li]:Tạo danh sách có thứ tự
thẻ ul[li]L:Tạo Mục Lục 
thẻ header: dùng ở phía trên
thẻ footer: dùng ở phía dưới
thẻ aside: 
thẻ nav: Tạo menu 
thẻ main: chứa nhiều thứ bên trong là phần chính ở trang web
thẻ article: tượng trưng cho 1 bài viết
thẻ iframe: thẻ nhúng (nhúng video hay gì đó cho trang web của mình)
thẻ span: đoạn văn bản ngắn
thẻ b: tô đậm chữ (bold)
thẻ i: chữ nghiêng (italic)

sự khác biệt thẻ inline và thẻ block
-thẻ inline: sẽ có độ rộng bằng nội dung mà nó chứa,nếu có nhiều thẻ inline thì nó sẽ nằm chung 1 hàng(văn bản ngắn thì xài inline)
-thẻ block: sẽ có độ rộng full phần tử của nó, nếu có nhiều thẻ block thì nó sẽ rớt xuống hàng(văn bản dài thì xài block)

sự khác biệt giữa class và id trong CSS
class: có thể trùng nhau, sử dụng nhiều phần tử giống nhau
id: không ai giống ai

--Học về BEM cơ bản
-BEM là viết tắt của cụm Block__Element–Modifier, là tiêu chuẩn quy ước đặt tên cho các tên lớp CSS. BEM giúp việc lập trình Frontend dễ hiểu, dễ đọc hơn, dễ làm việc và dễ mở rộng cũng như bảo trì khi làm việc với CSS.
-Laptop: Block
-keyboard, mouse, screen: Element
-keyboard--big, keyboard--small: modifier

-Block__Element--modifier
-Block__Element
-Block--Modifier

VD:
Laptop: Block
Laptop__Keyboard, Laptop__screen, Laptop__mouse
Laptop--big, Laptop--small, laptop--expensive
Laptop__Keyboard--big, laptop__screen--expensive

<!-- --Cách tạo nhanh và nhiều class khác nhau 1 
    .title
    .tile1.title2.title3
--cách tạo nhanh 1 id
    #tên id
--cách duy chuyển dòng 
    bấm ALT + Mũi tên
--cách copy nguyên dòng
    bấm Shit + ALT + mũi tên
--cách sửa cách chữ hoặc class id giống nhau
    nhấp chuột 2 lần vào cùm từ đó + CRTL + D
--cách tạo nhanh ul trong đó có li
    ul>li*10    
--cách tạo cách thẻ cùng cấp và các thẻ con của thẻ cha
     
     ex1:
        h1.title+p.desc+div.demo>p.text
        <h1 class="title"></h1>
        <p class="desc"></p>
        <div class="demo">
            <p class="text"></p>
        </div>

    ex2:
        h1.title+p.desc+.demo>p.text1+p.text2^.div2
        <h1 class="title p desc"></h1>
        <div class="demo">
            <p class="text1"></p>
            <p class="text2"></p>
        </div>
        <div class="div2"></div>
 -->

 --Cấu trúc của 1 đoạn code CSS
    selector {
        property: value;
    }
    selecttors:
    tags: p, div, h1, main, a, span
    class: .demo, .header, .boy

    ID: #container, #footer

    property:color ,background-color
    value: red, orange, yellow

