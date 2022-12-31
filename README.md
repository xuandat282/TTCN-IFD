# TTCN-IFD
- Nhóm thực tập 
1. Ngô Hoàng Phát
2. Nguyễn Trọng Thành
3. Huỳnh Xuân Đạt
4. Trần Hải Phước
6. Trần Khải Hoàn
7. Phù Quốc Khánh

Customer account
```bash
hoantran1107@gmail.com
123456
```

Admin account
```bash
admin@gmail.com
123456
```

Reload model
```bash
Scaffold-DbContext 'Server=DESKTOP-DDQN6I1\HOANTRAN;Initial Catalog=dbshop;Trusted_Connection=True;' Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force
```
appsetting.json
```bash
{
  "ConnectionStrings": { "dbShopBanDo": "Server=XUANDAT\\DATXUAN;Database=dbshop;Integrated Security=true;" },
  "Serilog": {
    "MinimumLevel": {
      "Default": "Information",
      "Override": {
        "Microsoft": "Information",
        "System": "Information"
      }
    }
  },
  "EPPlus": {
    "ExcelPackage": {
      "LicenseContext": "Commercial" //The license context used
    }
  },
  "Smtp": {
    "Host": "smtp.gmail.com",
    "Port": 465,
    "FromEmail": "quockhanhphu11@gmail.com",
    "UserName": "quockhanhphu11@gmail.com",
    "PassWord": "bwzlrkejdcolvoub"
  },
  "ElasticSearch": { "Url": "http://localhost:9200" },
  "AllowedHosts": "*"
}
```