## BEM

- Là tiêu chuẩn đặt tên class khi viết CSS

## Ý nghĩa:

- Viết tắt của:Block Element Modifier

- Block: Khối 

- Element: Thành phần trong khối

- Modifier: Bổ sung ý nghĩa cho `Block` và `Element`

## Tại sao dùng BEM

- Mối người đặt 1 kiểu
  
- Members đặt tên class trùng nhau, CSS đè lên nhau

## Cú pháp

- .block

- .block__element
  
- .block--modifier

- .block__element--modifier
  
## Ứng dụng

- Xây dựng layout website

- Xây dựng thành phần website

## Ưu Điểm

- Tính rõ ràng  
  
- Tái sử dụng dễ dàng 

- Giúp cả team làm việc với nhau dễ dàng 

- Tính module, không lo CSS của class này ảnh hướng tới CSS của class khác(đóng gói gọn gàng)

## Nhược điểm

- Tên class dài 

- Nhiều người cho là xấu 
  
## Khi nào dùng BEM là phù hợp

- Dự án nhiều members

- Dự án lớn, số lượng pages nhiều hoặc số lượng các thành phần trên giao diện nhiều 
  
## Thực hành

- Làm button
  - Enabled: Pointer, hover effect
  - Disabled: Arrow, no effect
- Làm message
- Làm 1 thành phần trên website

## Trường hợp block lồng block

- Block con là thành phần dùng chung
- Block con chứa nhiều element
