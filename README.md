````markdown
# 🚀 Simple Blazor App

Project ini dibangun menggunakan **.NET 9** dengan framework **Blazor**.  
Repositori ini berisi source code lengkap untuk aplikasi web interaktif berbasis C#.

---

## 📦 Persyaratan

Pastikan sudah terpasang di komputer kamu:

- [.NET SDK 9.0+](https://dotnet.microsoft.com/download)

---

## ⚙️ Cara Menjalankan Project

1. **Clone repository:**
   ```bash
   git clone https://github.com/<username>/<repo-name>.git
   cd <repo-name>
   ```
````

2. **Restore dependencies:**

   ```bash
   dotnet restore
   ```

3. **Build project:**

   ```bash
   dotnet build
   ```

4. **Jalankan aplikasi:**

   ```bash
   dotnet run
   ```

---

## 🌐 Deployment

### 🔸 Blazor WebAssembly

Untuk menghasilkan file static yang bisa dideploy ke layanan seperti **Vercel**, **Netlify**, atau **GitHub Pages**:

```bash
dotnet publish -c Release
```

Hasilnya ada di:

```
bin/Release/net9.0/publish/wwwroot/
```

---

## 📁 Struktur Folder (Umum)

```
MyBlazorApp/
 ├── Pages/           # Komponen halaman
 ├── Shared/          # Komponen bersama
 ├── wwwroot/         # File statis (CSS, JS, dll)
 ├── Program.cs       # Entry point aplikasi
 ├── App.razor        # Root komponen Blazor
 └── MyBlazorApp.csproj
```

---

## 🧩 Build Ulang

Jika kamu baru clone repo atau update dependency:

```bash
dotnet restore
dotnet build
```
