**USE: CTRL +SHIFT + P**


# AT TOP IN # normal dependencies:
* remember not to use <br>
// Start
```yaml
flutter:
  generate: true   # this line

```
// End

# Start Journey 

```YAML

flutter_localizations:
    sdk: flutter

```
# normal dependencies:
```bash

intl,dio,auto_route,freezed_annotation,get_it,injectable,equatable,json_annotation,bloc,flutter_bloc

```




# dev dependencies:
```bash
auto_route_generator,build_runner,freezed,injectable_generator,json_serializable,mockito

```




dart pub run build_runner build

or

# 👨‍💻 terminal
```bash
flutter pub run build_runner watch --delete-conflicting-outputs

```


# at last 
```yaml
flutter_intl:
  enabled: true
  class_name: AppLocalizations

```
