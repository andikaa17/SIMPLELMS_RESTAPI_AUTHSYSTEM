# Simple LMS API

```bash

# Jalankan
docker-compose up -d
```

API tersedia di: `http://localhost:8000/api/docs`

---

## Dokumentasi API

### 1. POST `/api/auth/register` - Buat Akun
![Register](/Dokumentasi/image10.png)

### 2. POST `/api/auth/login` - Login
![Login](/Dokumentasi/image11.png)

### 3. POST `/api/auth/refresh` - Refresh token
![Refresh Token](/Dokumentasi/image12.png)

### 4. GET `/api/auth/me` - Lihat Profil
![Get Me](image.png)

### 5. PUT `/api/auth/me` - Update Profil
![Update Me](image-1.png)

### 6. GET `/api/courses` - List Course
![List Courses](image-2.png)

### 7. POST `/api/courses` - Buat Course untuk Instructor
![Create Course](image-3.png)

### 8. GET `/api/courses/{id}` - Detail 
![Detail Course](image-4.png)

### 9. PATCH `/api/courses/{id}` - Update
![Update Course](image-5.png)

### 10. DELETE `/api/courses/{id}` - Admin
![Delete Course](image-6.png)

### 11. POST `/api/enrollments` - Student
![Enroll](image-7.png)

### 12. GET `/api/enrollments/my-courses` - Enroll Course
![My Courses](image-8.png)

### 13. POST `/api/enrollments/{id}/progress` — Progres 
![Progress](image-9.png)
