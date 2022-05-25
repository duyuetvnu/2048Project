Nguyễn Hoàng Duy
21020755

Giới thiệu chung:

​	Đây là [video](https://www.youtube.com/watch?v=3iDLFbshtWM) giới thiệu

​	Đây là trò chơi 2048 cổ điển được viết bằng ngôn ngữ C++, sử dụng thư viện đồ hoạ SDL2

Hướng dẫn cài đặt:

​	Tải game tại đây: [Download](https://github.com/duyuetvnu/2048Project/releases/download/v1.0.0/2048Portable.zip)

​	Giải nén vào một tệp và chạy file 2048_Last_Version.exe để chơi game
​	Nếu máy báo lỗi VCRUNTIME140.dll is missing thì vào [link](https://www.dll-files.com/vcruntime140.dll.html) để tải phiên bản phù hợp

​	Chọn phiên bản phù hợp để tải![Tải file vcruntime140.dll](https://cdn.tgdd.vn/hoi-dap/1346793/cach-sua-loi-vcruntime140dll-is-missing-tren-may-tinh-100-1-1-800x305.jpg)

​	Giải nén file đã tải

![Giải nén file vcruntime140.dll](https://cdn.tgdd.vn/hoi-dap/1346793/cach-sua-loi-vcruntime140dll-is-missing-tren-may-tinh-100-2-1-800x305.jpg)

​	Nhấn tổ hợp Windows + R để mở hộp thoại Run, sao chép đường dẫn **C:\Windows\System32** rồi dán vào

![Mở hộp thoại Run](https://cdn.tgdd.vn/hoi-dap/1346793/cach-sua-loi-vcruntime140dll-is-missing-tren-may-tinh-100-3-1-800x450.jpg)

​	Chọn và kéo thư mục vcruntime140.dll vào trong System32 rồi tắt hết các chương trình đang mở và khởi động lại máy tính

Luật chơi:

​	Sử dụng các phím mũi tên để di chuyển các khối ô vuông có các số là luỹ thừa của 2 từ 2 đến 2048. Mỗi lần di chuyển sẽ có một giá trị 2 hoặc 4 sinh ra ngẫu nhiên ở một ô trống ngẫu nhiên. Trò chơi sẽ kết thúc nếu không thể di chuyển hoặc đạt được giá trị 2048 ở một ô vuông bất kỳ

Các chức năng:

    Menu game
    Hiển thị bảng xếp hạng
    Nhạc nền
    Các hiệu ứng âm thanh
    Chơi lại khi thắng/thua
Các kỹ thuật được sử dụng

    Con trỏ
    Truyền tham chiếu
    Mảng
    Class
    Load ảnh, âm thanh từ thư viện SDL2
    Bắt sự kiện từ bàn phím và chuột
    Sinh số ngẫu nhiên
    Đọc, ghi file
Kết luận, hướng phát triển:

    Qua thời gian em làm game này, em đã biết thêm được rất nhiều kỹ năng lập trình, giải quyết các vấn đề phát sinh, cải thiện khả năng tìm kiếm thông tin, đọc hiều tài liệu tiếng Anh. Em đã biết được làm một game "đơn giản" là không hề đơn giản, cần phải áp dụng các kiến thức, thuật toán một cách khéo léo để có thể đạt được mục tiêu mình muốn.
    Hướng phát triển: Thêm các hiệu ứng cho game, thêm vào cốt truyện, cải thiện âm thanh, hình ảnh sinh động hơn, thêm chế độ chơi cho 2 - nhiều người.
CREDIT:

    Em xin cảm ơn:
        Thầy Trần Quốc Long
        Thầy Nguyễn Thành Sơn
    đã giúp em làm và hoàn thiện game này
    
    Đồng thời em xin cảm ơn
    
        Lazy Foo' Prodution: https://lazyfoo.net/tutorials/SDL/
        Đã hướng dẫn em cài đặt, sử dụng và các tính năng của thư viện SDL2.
    
        Chotom, link GitHub: https://github.com/Chotom
        Đây là nguồn tham khảo về các thuật toán của game.
    
    Âm thanh được sử dụng:
        move.wav: https://www.zapsplat.com/music/board-game-plastic-token-move-on-board-x1/
        error.wav: https://www.zapsplat.com/music/game-error-tone-6/
        backgroundMusic.wav: Forest Walk - Alexander Nakarada: https://www.chosic.com/download-audio/28063/
        win.wav: https://www.zapsplat.com/music/game-sound-congratulations-win-game-harp-glissando-leads-into-a-fanfare-and-fireworks/
        lose.wav: https://www.zapsplat.com/music/game-sound-fun-arcade-organ-tone-short-negative-fail-or-lose-tone-1/
