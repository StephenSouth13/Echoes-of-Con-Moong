🌿 CÚC PHƯƠNG: TIẾNG VỌNG CON MOONG
(CUC PHUONG: THE ANCIENT ECHOES)
"Thiên nhiên không nợ chúng ta điều gì. Mọi hơi thở đều có cái giá của nó."

Cúc Phương: Tiếng Vọng Con Moong là một tựa game sinh tồn thế giới mở (Open World Survival) kết hợp yếu tố tâm linh và giả tưởng, lấy bối cảnh tại Rừng Quốc gia Cúc Phương, Việt Nam. Trong vai một người cha tuyệt vọng đi tìm phương thuốc cứu con gái, bạn phải đối mặt với những thực thể cổ đại và những bí mật nằm sâu trong hang Con Moong 15.000 năm tuổi.

🎬 Câu Chuyện (The Narrative)
Khi chứng bệnh "Hóa Gỗ" kỳ lạ đang dần tước đi mạng sống của con gái nhỏ, Lâm - một thợ rừng dày dạn - phải dấn thân vào vùng cấm của rừng già Cúc Phương. Đồng hành cùng anh là linh hồn của người vợ quá cố trong hình hài một Linh Điệp (con bướm phát sáng). Lâm phải học cách sinh tồn giữa rừng rậm nhiệt đới và giải mã những ký ức tiền sử tại hang Con Moong để tìm ra "Nhựa Sống Nguyên Thủy".

🔥 Tính Năng Đỉnh Cao (Key Features)
🌲 Sinh Tồn Đậm Chất Việt (Survival)
Hệ thống xây dựng "Ký Sinh": Dựng chòi tre, nhà sàn trên những cây Chò ngàn năm tuổi. Tận dụng địa thế cao để tránh né dã thú và oán linh.

Chế tác nguyên thủy: Sử dụng tre, đá cuội, dây mây và thảo mộc đặc trưng của rừng nhiệt đới Việt Nam.

🦋 Cơ Chế "Linh Điệp" (AI Soul Guide)
Người vợ quá cố sẽ dẫn đường qua màn sương, cảnh báo nguy hiểm và giúp người chơi giữ vững chỉ số Tinh Thần (Sanity).

🌀 Nhãn Quan Tiền Sử (Echoes of the Past)
Sử dụng cổ vật để kích hoạt hiệu ứng chuyển đổi thực tại (Time-shift), biến rừng Cúc Phương hiện đại thành một thế giới tiền sử rực rỡ nhưng đầy hiểm nguy.

🎮 Multiplayer Co-op (Coming Soon)
Hỗ trợ 2 người chơi song hành (Cha và Anh traihttps://www.google.com/search?q=/Bạn đồng hành), chia sẻ tài nguyên và cùng thực hiện các nghi lễ thanh tẩy rừng già.

🛠 Kỹ Thuật & Công Nghệ (Tech Stack)
Engine: Unity 2022.3 LTS (HDRP).

Physics: Hệ thống chặt cây và xây dựng dựa trên vật lý thực (Sons of the Forest style).

Lighting: Real-time Global Illumination với Physical Sky và Volumetric Fog.

Networking: Photon Fusion cho trải nghiệm Co-op mượt mà.

📂 Cấu Trúc Thư Mục (Project Structure)
Bash

Assets/
 ├── _Project/
 │    ├── Scripts/        # Hệ thống C# Core (Player, AI, Build System)
 │    ├── Shaders/        # Custom Shader Graph (Water, Foliage, Time-Shift)
 │    ├── Prefabs/        # Các module xây dựng bằng tre, vật dụng
 │    └── Environments/   # Map Rừng Cúc Phương & Hang Con Moong
 ├── Survival_3D/         # 3D Assets (Models, Textures)
 └── Settings/            # HDRP & Input System Settings
🚀 Cài Đặt Cho Developer (Installation)
Clone Project:

Bash

git clone https://github.com/YourUsername/CucPhuong-TheAncientEchoes.git
Mở bằng Unity Hub: Chọn phiên bản 2022.3.x LTS.

Import Assets: Đảm bảo tất cả các package trong Manifest.json đã được tải về.

Bake Lighting: Vào Window > Rendering > Lighting, nhấn Generate Lighting để khởi tạo ánh sáng môi trường.

⚠️ Lưu ý về các lỗi Mesh (Troubleshooting)
Nếu bạn gặp lỗi Identifier uniqueness violation hoặc Self-intersecting polygon:

Hãy mở model trong Blender và đảm bảo các vật thể con có tên duy nhất.

Tích chọn Generate Lightmap UVs trong tab Model khi Import vào Unity.

🤝 Đóng Góp (Contribution)
Vì đây là dự án tâm huyết mang tầm cỡ "siêu cấp", mình rất hoan nghênh các đóng góp về:

VFX: Hiệu ứng sương mù và hào quang cổ đại.

3D Art: Model nhà sàn, dụng cụ truyền thống Việt Nam.

Optimization: Tối ưu hóa hiệu năng cho các khu rừng dày đặc.