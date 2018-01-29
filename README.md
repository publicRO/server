publicRO
=======

Table of Contents
---------
1. publicRO là gì?
2. Mục đích ra đời
3. Cài đặt

publicRO là gì?
---------

`publicRO = rAthena + rAsql + RO client + ♥`

> rAthena is a collaborative software development project revolving around the creation of a robust massively multiplayer online role playing game (MMORPG) server package. Written in C, the program is very versatile and provides NPCs, warps and modifications. The project is jointly managed by a group of volunteers located around the world as well as a tremendous community providing QA and support. rAthena is a continuation of the eAthena project.

- [rAthena](https://github.com/rathena/rathena/) là một bộ mã nguồn mở (open sourse), được phát triển để xây dựng server game Ragnarok Online.

- Mặc định [rAthena](https://github.com/rathena/rathena/) hoạt động với MySQL, đồng nghĩa với việc nến muốn khởi chạy một server RO thì thì phải khởi chạy service MySQL hay phải có một server khác chạy MySQL. Điều này sẽ dẫn việc nếu bạn chỉ muốn chơi `offline` hay test sơ qua vài script của rAthena thì sẽ tốn thêm chút thời gian. Vậy nên [rAsql](https://github.com/rathena/rAsql) ra đời.
- `publicRO` nói ngắn gọn là một server RO có thể khởi tọa nhanh mà cách bạn không cần phải làm gì hết, kể cả việc `compile`. Chỉ cần `start` là đủ.

Mục đích ra đời
---------
- Trước hết, bản thần mình muốn có một server RO có thể khởi tạo nhanh chống để chơi `offline` hoặc lâu lâu sẽ test script mới hay là item mới.
- Tiếp đó mình muốn nhiều anh em chơi RO biết rõ hơn về cách xây dựng server, để Ragnarok Việt mình có thể ngày càng phát triển hơn (hơi sến nhưng đúng là thế thật).
- Chia sẻ. Bản thân mình cũng chỉ biết những vấn đề cơ bản của RO server, hay [rAthena](https://github.com/rathena/rathena/). Mình sẽ cố gắng để sưu tầm những script, item hay map để đống góp vào `publicRO`. Và hy vọng sẽ có những người khác có cùng suy nghĩ với mình.

Cài đặt
---------
1. Download


- publicRO server: ngay chính repo này hoặc download bằng link: https://github.com/publicRO/server/archive/master.zip
- [rAsql](https://github.com/publicRO/rAsql): Link tải trực tiếp: https://github.com/publicRO/rAsql/archive/master.zip 
- publicRO client: [Full client](https://drive.google.com/open?id=1kkbmBTka_4x-s3iX4HL-W8ocgs5sciCO). Hoặc [Lite client](https://github.com/publicRO/lite-client). Các bạn nên tải bản full nhé

Sau khi tải xong về giải nén bất kỳ đâu bạn muốn.

2. Khởi động rAsql

Mở `rAsql\mysql_start.bat` Nếu thấy thông báo thành công như:

```
The MySQL server is working on disk Z:\ [port 3306]

Press any key to continue . . .
```

Lúc này bạn có thể thấy cửa sổ connect MySQL, bạn có thể ấn OK để connect và theo dõi database.

3. Khởi động server

Mở `server/runserver.bat`. 3 cửa sổ CMD sẽ được mở lên, chờ 1-3 phút nếu không có dòng thông báo đỏ nào thì bạn đã start thành công.

4. Khởi động game

Sau khi `rAsql` và `server` đã start thành công. Bạn có thể mở `publicRO/publicRO.exe` để khơi động game.

Để đang ký account thì ở lần đăng nhập đầu tiền bạn hãy nhập.

```
ID: idcuaban_M
Password: password
```

Trong đó có `_M` là xác định gới tính nam `_F` là nữ. Những lần đăng nhập sau bạn không cần những hậu tố này nữa.



Nếu có vấn đề?
---------

Nếu gặp vấn đề hãy để lại câu hỏi ở:

Facebook Group: https://www.facebook.com/groups/ragnarokviet/

Discord Chat: https://discord.gg/TNDA2S2







