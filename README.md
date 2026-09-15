# Lesson 1 - ASP.NET Core Razor Pages

Project giao diện trang tin tĩnh được làm lại từ bản gốc. Tất cả ảnh đều nằm
trong `wwwroot/images`; project không tham chiếu tới Desktop và không chứa
`bin`, `obj`, `.git` hoặc `.idea`.

## Yêu cầu

- .NET SDK 10.0

Kiểm tra bằng lệnh:

```powershell
dotnet --version
```

## Chạy project trên Windows

1. Giải nén file ZIP.
2. Mở PowerShell tại thư mục `lesson1-fixed` (nơi có file `lesson1.csproj`).
3. Chạy:

```powershell
dotnet restore
dotnet run
```

4. Mở `http://localhost:5030` nếu trình duyệt không tự mở.

Nếu port 5030 đang được sử dụng, chạy bằng port khác:

```powershell
dotnet run --urls "http://localhost:5040"
```

## Chạy project trên macOS

```bash
cd lesson1-fixed
dotnet restore
dotnet run
```

Sau đó mở `http://localhost:5030`.
