# flutter project

a new flutter project.

## general setup project

- to setup flutter project
- flutter create project name
- init this file & folders structure
- run *flutter pub add flutter_dotenv http permission_handler riverpod hive hive_flutter auto_route responsive_framework responsive_sizer cached_network_image*
- run *flutter pub add build_runner freezed hive_generator flutter_gen flutter_gen_runner fast_i18n flutter_native_splash flutter_launcher_icons rename --dev*

## generating files

- standard for generating files after create some or modify some
- run *flutter packages pub run build_runner build --delete-conflicting-outputs*

## making secret

- head to *lib/constants/*
- create *constant_secret.dart*
- write *const baseApiKey = 'yourBaseApiKey';*
- write the rest secret

## screenshots from previous run on android

head to */screenshots*

## running app

- choose your device
- head to */lib*
- choose *main_production.dart*
- run project

## renaming app

- pub global activate rename
- pub global run rename --bundleId com.onatcipli.networkUpp
- pub global run rename --appname "Network Upp"
