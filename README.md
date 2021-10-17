# Day5Homework.js
/* Bài 1: 
let people = prompt("Số lượng người tham gia là: ");
let pizza = prompt("Số lượng pizza là: ");
let pizzaPiece = pizza * 8 / people;

for(people > 0; people--;) {
   let name = prompt("Tên của người tham gia là: ");
   let age = prompt("Tuổi của người tham gia là: "); 
}
alert("Số miếng pizza mỗi người được ăn là: " + pizzaPiece); 
*/

 /* Bài 2:
let temperature = Number(prompt("Nhiệt độ hôm nay là: "));
if (temperature < 40) {
    alert("Nóng");
} else if (temperature < 25) {
    alert("Mát");
} else if (temperature < 15) {
    alert("Lạnh");
} else if (temperature < 0) {
    alert("Siêu lạnh");
} else if (temperature < -12) {
    alert("Không sống được");
} else {
    alert("Không sống được")
}
*/

/* Bài 3:
let user = 10;
for(user > 0; user --;) {
    let userName = prompt("Tên người dùng là: ");
}
*/

/* Bài 4:
let book = Number(prompt("Số lượng sách muốn nhập là: "))
while(book > 0) {
    let bookName = prompt("Tên sách muốn nhập là: ");
    alert("Số lượng sách hiện giờ là: " + book--);
}
*/

/* Bài 5:
let bookShelf = ['Vàng', 'Xanh', 'Đỏ', 'Tím'];
let book = Number(prompt("Số lượng sách muốn nhập là: "))
while(book > 0) {
    let bookName = prompt("Tên sách muốn nhập là: ");
    book--;
    alert("Số lượng sách hiện giờ là: " + book);
    bookShelf.push(bookName);
}
console.log(...bookShelf);
alert(bookShelf);
*/

/* Nâng cao:
let shop = ["Quần bò", "Áo sơ mi", "Mũ len"];
let statement = String(prompt("Bạn muốn làm gì: Create, Read, Update, Delete?"));
if(statement == "Create") {
    let items = Number(prompt("Số lượng items muốn thêm là: "))
    while(items > 0) {
    let itemsName = prompt("Tên sách muốn nhập là: ");
    items--;
    alert("Số lượng sách hiện giờ là: " + items);
    let items = String(prompt("Thêm đồ muốn thêm: "))
    console.log(shop.push(itemsName));
    }
} else if (statement == "Read") {
    console.log(...shop);
} else if (statement == "Update") {
    let positionName = String(prompt("Tên đồ bạn muốn thêm vào là: "));
    shop.push(positionName);
    alert(shop);
} else if (statement == "Delete") {
    let itemsDeletle = Number(prompt("Vị trí sản phẩm muốn xóa: "));
    shop.slice(itemsDeletle, itemsDeletle);
} else {
    alert("Nhập lại")
}
*/
