### React là gì ?
 - React là một thư viện (library) javascript để xây dựng giao diện
 người dùng (UI-User Interface)
 - Ra Đời vào tháng 5/2013 . Version hiện tại: 18.2.0(14/06/2022)
 - Fecabook (Meta) phát triển
 - Học một lần viết mọi nơi (Learn Once,Write Anywhere)
 - React JS(Web) vs React Native(Mobile)
### React có thể làm được gì ?
 - Xây dựng website đơn giản như Fecabook hay Instagram
### Tại sao dùng React ?
 - So sánh React/Vue/Angular:
  + React nhiều người dùng nhất bỏ xa các đối thủ Vue và Angular
  + React(Fecabook) vs Angular(Google) vs Vue - (Evan You/China)
  + Nhiều công ty sử dụng React để phát triển sản phẩm
### Lưu Ý Khi Học React
 - Cần biết HTML,CSS và JavaScrip cơ bản
 - Sử dụng JavaScrip hay TypeScrip
 - Sử dụng kết thúc file .js/.ts hay là .jsx/.tsx
### 15 How React Works ?
1. SPA-Single Page Application
- Ứng dụng React là SPA
- Browser chỉ chạy 1 file duy nhất: index.html
- React kiểm soát thứ người dùng muốn nhìn, từ điều hướng trang cho tới
hiển thị dữ liệu
Mô Hình SSR - Server-side rendering (Muti page apps)


### 16 React Components là gì ?
 - Các thành phần là các bit mã độc lập và có thể tái sử dụng. Chúng phục vụ cùng mục đích như
   các hàm JavaScript, nhưng hoạt động độc lập và trả về HTML thông qua hàm render()
 - Các thành phần có hai loại, Thành phần lớp và Thành phần chức năng .
 - Nếu có hàm constructor() trong thành phần của bạn, thì hàm này sẽ được gọi khi thành phần
   được bắt đầu.
   
### 17 State là gì?
1. Component State
- Là JavaScript Object
- Miêu tả trạng thái (state) hiện tại của Component:data/UI-state
- State của Component có thể được cập nhật , VD như :đóng/Mở Modal..

2. Sử dụng State
 - Khai Báo: State={} <= state là JavaScipt Object
 - Sử Dụng { this.state.property }

### 18 React Events là gì ?
 - React Events là sự kiện phản ứng
 - Adding Event (Thêm sự kiện )
 - Các sự kiện phản ứng được viết bằng cú pháp camelCase:
   onClick thay vì onclick.
 - Trình xử lý sự kiện phản ứng được viết bên trong dấu ngoặc nhọn:
 VD: onClick={shoot}  thay vì onClick="shoot()".
     <button onClick={shoot}>Take the Shot!</button>
     
### 23 Props Props là gì?
 - React Props là các tham số truyền vào React Component. React Props được truyền 
   vào Component thông qua các HTML attributes.
 - React Props giống như các tham số của 1 function JavaScript hay các thuộc tính 
   trong HTML
 - Các giá trị của props không bị thay đổi, khi muốn thay đổi trạng thái của
   component thì người ta chỉ thay đổi state của component chứ props thì không
   thay đổi được.
 -  Sử Dụng : {this.props.value}
### Tác Giả
### 2022 - Bản Quyền Thuộc về Công ty của ông Nguyễn Đức Duy
