# <img width="34" alt="image" src="https://github.com/drago467/Game-SDL-2023/assets/125422941/feeca238-0a16-4dd8-a829-d037c67bf3a3"> CONTRA GUN
 Đây là dự án game cá nhân của mình được tạo bới ngôn ngữ C++ và SDL2. Dự án này là một bài tập lớn của môn học Lập Trình Nâng Cao tại trường Đại học Công Nghệ, VNU Hà Nội.
* Trần Đình Tuấn: 22026550
* K67-CN16-UET
* Bài tập: INT2215 1 - Lập Trình Nâng Cao
* Email: tdt.trandinhtuan467@gmail.com
### GIỚI THIỆU CHUNG:
1. Các nguồn tham khảo: 
- LAZYFOOL:https://lazyfoo.net/tutorials/SDL/index.php
- Phát triển phần mềm 123az: https://www.youtube.com/watch?v=q1WzniyeGTU&list=PLR7NDiX0QsfTIEQUeYCfc2MyCquX0ig9V
2. Luật chơi
- Người chơi di chuyển nhân vật game di chuyển lên, xuống, trái, phải để tiêu diệt lính gác <img width="32" alt="image" src="https://github.com/drago467/Game-SDL-2023/assets/125422941/7689cfd9-7b8c-4fe0-8b8f-03a81909ee41"> và quái vật <img width="33" alt="image" src="https://github.com/drago467/Game-SDL-2023/assets/125422941/d64abc7a-3e37-451d-a518-dceaf8b78586"> đồng thời cố gắng lụm nhiều đồng tiền vàng ![4](https://github.com/drago467/Game-SDL-2023/assets/125422941/4a0364d4-e385-4ee6-8fad-ed75c2f1528a) nhiều nhất có thể.
- Bạn thắng khi tiêu diệt được hết quái vật và lính gác.
- Bạn thua khi hết dùng hết chỉ số sinh mệnh hoặc hết thời gian cho phép.
3. Hướng dẫn cài đặt
- Cài đặt [Visual Studio Code 2015] (https://tinhte.vn/thread/downloadvisual-studio-2015-full-cai-dat-chi-tiet.3440818/)
- Tải các thư viện hỗ trợ SDL:
-  https://github.com/libsdl-org/SDL_image
-  https://github.com/libsdl-org/SDL_mixer
-  https://github.com/libsdl-org/SDL_ttf
4. Cấu trúc của game gồm 14 module gồm:
- Base Object: lớp nền tảng, làm nhiệm vụ load ảnh lên màn hình.
- Common Funch: gọi các thư viện cơ bản và các biến static, global, thông số cơ bản cho môi trường của game.
- BulletObject: quản lý đạn dược của nhân vật và lính trinh sát.
- ExplosionObject: quản lý hàm check va chạm giữ quái và nhân vật, đạn vs nhân vật và quái.
- Game_map: khởi tạo, quản lý hình ảnh bản đồ trong game.
- Geometric: quản lý hiện thị text lên màn hình.
- Imptimer: xử lý Timmer và FPS.
- MainObject: quản lý chức năng, hình ảnh của nhân vật.
- ThreatsObject: quản lý chức năng, hình ảnh cho quái vât, mối hiểm họa.
5. Mô tả.
- MENU
<img width="960" alt="image" src="https://github.com/drago467/Game-SDL-2023/assets/125422941/2eb297f2-e9a6-40c7-9384-a022cf3d062d">

- Màn hình chơi
<img width="960" alt="image" src="https://github.com/drago467/Game-SDL-2023/assets/125422941/a0a835bd-9844-4510-b365-5a820955353a">

6. Cải tiến game.
- Tạo thêm các quái vật vs các chức năng khác nhau.
- Thêm các lựa chọn súng và trang phục cho nhân vật.
7. Lời cảm ơn
- Em xin chân thành cảm ơn các thầy đã hô trợ em hoàn thành game ạ. <3 <3



