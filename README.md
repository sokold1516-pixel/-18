пр13_14/
├── App.xaml / App.xaml.cs          # Точка входа, ресурсы приложения
├── MainWindow.xaml                 # Главное окно с Frame-навигацией
├── UserSession.cs                  # Статический класс сессии пользователя
├── DatabaseHelper.cs               # Работа с БД (все CRUD-операции)
├── Converters/
│   ├── NullToVisibilityConverter.cs # Конвертер для привязок UI
│   └── BoolToBlockTextConverter.cs  # Конвертер для текста кнопок
├── Pages/
│   ├── LoginPage.xaml              # Страница авторизации
│   ├── RegistrationPage.xaml       # Страница регистрации
│   ├── CatalogPage.xaml            # Каталог экспонатов (основная)
│   ├── AddEditPage.xaml            # Добавление/редактирование экспоната
│   ├── AdminPanelPage.xaml         # Админ-панель (2 вкладки)
│   ├── RoleSelectionDialog.xaml    # Диалог выбора роли
│   ├── User.xaml / Manager.xaml    # Заглушки панелей (опционально)
└── Models/
    ├── ExhibitCardItem.cs          # Модель для карточки экспоната
    └── (другие модели при необходимости)
