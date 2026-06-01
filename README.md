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
![Get Me](/Dokumentasi/image.png)

### 5. PUT `/api/auth/me` - Update Profil
![Update Me](/Dokumentasi/image-1.png)

### 6. GET `/api/courses` - List Course
![List Courses](/Dokumentasi/image-2.png)

### 7. POST `/api/courses` - Buat Course dengan role Instructor
![Create Course](/Dokumentasi/image-3.png)

### 8. GET `/api/courses/{id}` - Detail 
![Detail Course](/Dokumentasi/image-4.png)

### 9. PATCH `/api/courses/{id}` - Update
![Update Course](/Dokumentasi/image-5.png)

### 10. DELETE `/api/courses/{id}` - Admin
![Delete Course](/Dokumentasi/image-6.png)

### 11. POST `/api/enrollments` - Student
![Enroll](/Dokumentasi/image-7.png)

### 12. GET `/api/enrollments/my-courses` - Enroll Course
![My Courses](/Dokumentasi/image-8.png)

### 13. POST `/api/enrollments/{id}/progress` — Progres 
![Progress](/Dokumentasi/image-9.png)
