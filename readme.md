1. Tự động mời bạn bè like Fanpage
```
javascript:var inputs = document.getElementsByClassName('uiButtonText');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
Với Giao diện Facebook mới thì không cần code cho tính năng này.

2. Tự động like bài viết trên Tường bạn bè, trên dòng thời gian của chính mình, like bài viết trên Fanpage, like bài viết trong Group
```
javascript:var inputs = document.getElementsByClassName('sp_LUg8uzjLm4u sx_d18851');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
3. Tự động like Ảnh trong album bạn bè
```
javascript:var inputs = document.getElementsByClassName('_5glz _53o _53b');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
4. Tự động like Comment trong bài viết
```
javascript:var inputs = document.getElementsByClassName('UFILikeLink UFIReactionLink UFIEnlargeLikeLinkHotspot');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
5. Tự động “thêm bạn bè” theo gợi ý của Facebook
```
javascript:var inputs = document.getElementsByClassName('_42ft _4jy0 FriendRequestAdd addButton _4jy3 _4jy1 selected _51sy');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
6. Tự động “kết bạn” với bạn bè của người khác
```
javascript:var inputs = document.getElementsByClassName('_42ft _4jy0 FriendRequestAdd addButton _4jy3 _4jy1 selected _51sy');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
7. Tự động like theo biểu tượng cảm xúc (yêu thích, haha, wow, buồn, phẫn nộ)
Chú ý: Chuyển từ trang www.facebook.com thành m.facebook.com trước khi auto.

a. Yêu thích
```
javascript:var inputs = document.getElementsByClassName('_1ekf');
var input2=document.getElementsByClassName('img _mpx img _4s0y');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
for(var j=0; j<inputs.length;j+=1) {
if(j==1){input2[j].click();}}
}
```
b. Haha
```
javascript:var inputs = document.getElementsByClassName('_1ekf');
var input2=document.getElementsByClassName('img _mpx img _4s0y');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
for(var j=0; j<inputs.length;j+=1) {
if(j==3){input2[j].click();}}
}
```
c. Wow
```
javascript:var inputs = document.getElementsByClassName('_1ekf');
var input2=document.getElementsByClassName('img _mpx img _4s0y');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
for(var j=0; j<inputs.length;j+=1) {
if(j==4){input2[j].click();}}
}
```
d. Buồn
```
javascript:var inputs = document.getElementsByClassName('_1ekf');
var input2=document.getElementsByClassName('img _mpx img _4s0y');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
for(var j=0; j<inputs.length;j+=1) {
if(j==5){input2[j].click();}}
}
```
e. Phẫn nộ
```
javascript:var inputs = document.getElementsByClassName('_1ekf');
var input2=document.getElementsByClassName('img _mpx img _4s0y');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
for(var j=0; j<inputs.length;j+=1) {
if(j==6){input2[j].click();}}
}
```
8. Tự động “tham gia” Group
Gõ tên bạn muốn tìm kiếm vào ô “tìm kiếm trên Facebook“, sau đó ở tab bên trái chọn “Nhóm” rồi paste code vào ô Console như bình thường. 

Lưu ý: Các nhóm có yêu cầu câu hỏi sẽ hiển ra, trả lời từng nhóm, xong nhóm này thì khung hỏi của nhóm khác sẽ hiện lên.
```
javascript:var inputs = document.getElementsByClassName('hu5pjgll lzf7d6o1 sp_ItUvUz1k1uu sx_a4ad63');
for(var i=0; i<inputs.length;i+=1) {
inputs[i].click();
}
```
9. Tự động hủy lời mời kết bạn mà bạn đã gửi
Các bạn vào đường dẫn sau: https://www.facebook.com/profile.php?id=Mã_ID_NickFacebook_của_bạn&sk=following

Ví dụ: https://www.facebook.com/congvietit/following

Sau đó làm F12 như thường.
```
javascript:var inputs = document.getElementsByClassName('rq0escxv l9j0dhe7 du4w35lb d2edcug0 hpfvmrgz j83agx80 j5wkysh0 hytbnt81');
for(var i=0; i<inputs.length;i++) {
inputs[i].click();
}
```
10. Tự động Like bài viết trên dòng thời gian
Các bạn gõ trên trình duyệt m.facebook.com để chuyển về giao diện mobile trên máy tính sau đó dán đoạn code này vào Console như bình thường:
```
javascript:var inputs = document.getElementsByClassName('_15ko _77li touchable'); 
for(var i=0; i<4;i+=1) { 
inputs[i].click(); 
}
```
11. Tự động Like Fanpage trong phần tìm kiếm Facebook
Các bạn gõ trên trình duyệt m.facebook.com để chuyển về giao diện mobile trên máy tính.Gõ tên bạn muốn tìm kiếm vào ô “tìm kiếm trên Facebook“, sau đó ở tab bên trái chọn “Fanpage” rồi paste code vào ô Console như bình thường. 
```
javascript:var inputs = document.getElementsByClassName(' _k7v _2rgt _1j-f _2rgt img '); 
for(var i=0; i<4;i+=1) { 
inputs[i].click(); 
}
```
