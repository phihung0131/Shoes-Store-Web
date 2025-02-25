# 🏬 **Đóm Store - Footwear E-commerce Website**  

## 📖 **Overview**  
Đóm Store là một website thương mại điện tử giày dép hoàn chỉnh, bao gồm hai giao diện riêng biệt: **khách hàng** và **quản trị viên**. Dự án được xây dựng với hai thành phần chính: **Frontend** và **Backend**.

---
## 🙉 **Preview**  

### 📸 **Hình ảnh**  
Xem hình ảnh tại thư mục **`preview`** trong repository.  

### 🎥 **Video demo**  
[🌟 Xem video giới thiệu trên YouTube tại đây!](https://www.youtube.com/watch?v=n3HCS5K23eE)  

### 🌐 **Truy cập trực tuyến**  
- **Backend:** [https://domstorefe.azurewebsites.net/](https://domstorefe.azurewebsites.net/)
- **Frontend:** [https://domstore.azurewebsites.net](https://domstore.azurewebsites.net/) 

---

## 🚀 **Technologies Used**  

### 🖥️ **Frontend**  
- ⚛️ React.js  
- 🛠️ Redux (quản lý trạng thái)  
- 🎨 Tailwind CSS (thiết kế giao diện)  
- 🌐 Axios (gọi API)  

### 💾 **Backend**  
- 🟢 Node.js  
- 📡 Express.js  
- 🍃 MongoDB (cơ sở dữ liệu)  
- 🔒 JWT (xác thực)  
- ☁️ Cloudinary (lưu trữ ảnh)  
- 📜 Swagger (tài liệu API)  

---

## 🌟 **Key Features**  

### 👥 **Dành cho khách hàng**  
- 🔐 Đăng ký, đăng nhập và xác thực người dùng  
- 🛍️ Xem sản phẩm và chi tiết sản phẩm  
- 🛒 Quản lý giỏ hàng  
- 💳 Đặt hàng và thanh toán  
- 🚚 Theo dõi đơn hàng  
- 📝 Quản lý hồ sơ cá nhân  
- 🎟️ Áp dụng mã giảm giá  

### 🛠️ **Dành cho quản trị viên**  
- 📝 Quản lý sản phẩm (CRUD)  
- 📦 Quản lý đơn hàng  
- 👥 Quản lý người dùng  
- 🎯 Quản lý khuyến mãi  
- 📊 Phân tích doanh thu  
- 🛡️ Quản lý vai trò (OWNER, ADMIN, CUSTOMER)  

---

## ⚙️ **Installation**  

### 📋 **Yêu cầu**  
- 🟢 Node.js (v14 hoặc cao hơn)  
- 🍃 MongoDB  
- 🔗 Git  

### 🛠️ **Các bước cài đặt**  

1. **Clone repository:**  
   ```sh  
   git clone https://github.com/phihung0131/Shoes-Store-Web
   cd Shoes-Store-Web
   ```

2. **Cài đặt Backend:**  
   ```sh  
   cd Backend  
   npm install  
   ```  
   **Cấu hình file `.env`:**  
   ```env  
   PORT=5000  
   MONGODB_URI=your_mongodb_uri  
   JWT_SECRET=your_jwt_secret  
   CLOUDINARY_CLOUD_NAME=your_cloud_name  
   CLOUDINARY_API_KEY=your_api_key  
   CLOUDINARY_API_SECRET=your_api_secret  
   ```  

3. **Cài đặt Frontend:**  
   ```sh  
   cd ../Frontend  
   npm install  
   ```  
   **Cấu hình file `.env`:**  
   ```env  
   REACT_APP_API_URL=http://localhost:5000/api  
   ```  

4. **Chạy ứng dụng:**  
   - Khởi động Backend:  
     ```sh  
     cd Backend  
     npm start  
     ```  
   - Khởi động Frontend:  
     ```sh  
     cd Frontend  
     npm start  
     ```  

---

## 📜 **API Documentation**  
Truy cập `/` sau khi khởi động Backend để xem tài liệu API bằng **Swagger**.  

---

## 🗂️ **Project Structure**  

### **Backend**  
```
Backend/  
├── src/  
│   ├── config/       # Cấu hình cơ sở dữ liệu và Cloudinary  
│   ├── controllers/  # Xử lý logic  
│   ├── middlewares/  # Middleware xác thực  
│   ├── models/       # Mô hình cơ sở dữ liệu  
│   ├── routes/       # Định tuyến API  
│   ├── services/     # Dịch vụ logic  
│   └── helpers/      # Hàm tiện ích  
├── app.js            # Điểm khởi động  
└── package.json  
```  

### **Frontend**  
```
Frontend/  
├── src/  
│   ├── components/   # Thành phần React  
│   ├── pages/        # Thành phần trang  
│   ├── redux/        # Quản lý trạng thái  
│   ├── services/     # Gọi API  
│   ├── assets/       # Hình ảnh, font chữ  
│   └── helpers/      # Hàm tiện ích  
├── public/           # File tĩnh  
└── package.json  
```  

---

## 🔐 **Security Features**  
- 🛡️ Xác thực JWT  
- 🔑 Mã hóa mật khẩu  
- 👮‍♂️ Quản lý vai trò  
- ✅ Kiểm tra đầu vào  
- ❌ Xử lý lỗi  



