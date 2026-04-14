# 🚀 Sql Dropper

sql dropper is a modular project for managing SQL operations.  
It provides a flexible architecture for handling database models and authentication servers using modern Java technologies.

## 📦 Project Structure
```plaintext
sql-dropper
│
├── parent
│   ├── spring-boot-starter            ![v4.0.0]
│   └── lombok                         ![auto-picked supported version]
│
├── data-model
│   ├── parent                         ![latest version]
│   ├── spring-boot-starter-web        ![auto-picked supported version]
│   ├── spring-boot-starter-data-jpa   ![auto-picked supported version]
│   └── spring-boot-starter-validation ![auto-picked supported version]
│   └── spring-boot-testcontainers     ![auto-picked supported version]
│   └── postgresql                     ![auto-picked supported version]
│   └── hibernate-envers               ![auto-picked supported version]
│   └── jackson-databind               ![auto-picked supported version]
│   └── org.testcontainers-postgresql  ![1.21.3]
│   └── org.testcontainers-jupiter     ![1.21.3]
│   └── spring-boot-starter-flyway     ![auto-picked supported version]
│   └── flyway-database-postgresql     ![auto-picked supported version]
│   └── jarchivelib                    ![1.2.0]
│
├── auth-server
│   ├── spring-boot-starter-web        ![v3.2.2]
│   ├── spring-boot-starter-security   ![v3.2.2]
│   ├── spring-boot-starter-data-jpa   ![v3.2.2]
│   ├── postgresql                     ![v42.6.0]
│   └── data-model
│
└── pom.xml
    ├── 
    ├── 
```

## 📦 Projects

- **DevToolbox** – Browser-based toolkit for debugging and testing APIs  
- **UIForge** – Lightweight, accessible React UI components  
- **DeployMate** – Zero-config CI/CD pipelines for frontend projects  

## 🤝 Contribute

We welcome community contributions!  
Check out our [Contributing Guide](https://github.com/opendev/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/opendev/.github/blob/main/CODE_OF_CONDUCT.md)

## 🌐 Links

- Website: [opendevlabs.org](https://opendevlabs.org)  
- Twitter: [@opendevlabs](https://twitter.com/opendevlabs)  
- Discord: [Join our community](https://discord.gg/example)
- 📚📊 Database Tables Docs: [Docs](https://sqldropper.github.io/data-model-ui/)
---

© 2025 OpenDev Labs.
