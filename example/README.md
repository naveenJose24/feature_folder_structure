# Folder Structure Example

The folder structure generated by the CLI is as follows:

1. Normal Type
```md
feature/
┣ domain/
┃ ┣ feature_model.dart
┃ ┣ feature_repository.dart
┃ ┣ feature_service.dart
┃ ┗ feature_domain.dart
┣ screens/
┃ ┣ feature_screen.dart
┃ ┗ screens.dart
┣ widgets/
┃ ┣ feature_widget.dart
┃ ┗ widgets.dart
┣ providers/
┃ ┣ feature_provider.dart
┃ ┗ providers.dart
┗ index.dart
```

2. GetX Type
The folder structure generated by the cli is as follows:

```md
feature/
┣ domain/
┃ ┣ models/
┃ ┣ repository/
┃ ┣ services/
┃ ┗ index.dart
┣ screens/
┃ ┣ feature_screen.dart
┃ ┗ index.dart
┣ widgets/
┃ ┣ feature_component.dart
┃ ┗ index.dart
┣ providers/
┃ ┣ feature_provider.dart
┃ ┗ index.dart
┗ index.dart
```