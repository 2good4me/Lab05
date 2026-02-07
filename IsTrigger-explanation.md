# Sự khác biệt giữa IsTrigger = true và IsTrigger = false trong Unity

## IsTrigger = true
- Collider sẽ không gây ra va chạm vật lý.
- Chỉ kích hoạt các sự kiện như `OnTriggerEnter`, `OnTriggerStay`, `OnTriggerExit`.
- Dùng khi bạn muốn collider hoạt động như một khu vực kiểm tra hoặc xử lý logic mà không ảnh hưởng đến vật lý.
- Ví dụ: Khi nhân vật đi vào một vùng "trigger" để kích hoạt hiệu ứng hoặc sự kiện.

## IsTrigger = false
- Collider sẽ tương tác vật lý với các đối tượng khác.
- Gây ra va chạm và phản ứng vật lý (ví dụ: dừng lại khi chạm vào tường).
- Dùng khi bạn muốn collider ảnh hưởng đến chuyển động vật lý của các đối tượng trong game.
- Ví dụ: Tường, sàn nhà, vật thể cản đường.
