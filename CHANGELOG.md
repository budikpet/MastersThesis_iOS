# Changelog

- please enter new entries in format 

```
- <description> (#<PR_number>, kudos to @<author>)
```

- Update to use Xcode 12.4 ([#70](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/70) kudos to @olejnjak)
- Add `superfluous_disable_command` to white list ([#69](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/69) kudos to @fortmarek)
- Remove .tuist-bin folder, move Config.swift to Tuist folder, add .disableSynthesizedResourceAccessors generation option ([#68](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/68) kudos to @svastven)
- Update ACKLocalization ([#66](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/66) kudos to @olejnjak)
- Remove pluggable app delegates ([#65](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/65) kudos to @olejnjak)
- Fix release configuration bug and make `SWIFT_ACTIVE_COMPILATION_CONDITIONS` empty ([#62](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/62) kudos to @svastven)
- Make init of `AppDependency` fileprivate ([#61](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/61), kudos to @olejnjak)
- Remove `xcfilelists` ([#60](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/60), kudos to @fortmarek)
- Fix missing LaunchScreen storyboard after generation ([#59](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/59), kudos to @LukasHromadnik)
- Added LicensePlist ([#58](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/58), kudos to @LukasHromadnik)
- Removed `todo` from whitelist rules, update tuist ([#57](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/57), kudos to @fortmarek)
- Add tests to swiftlint's included paths ([#53](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/53), kudos to @fortmarek)
- Rename global `dependencies` to `appDependencies` ([#52](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/52), kudos to @fortmarek)
- Update Tuist, set shared organization name, disable autogenerated schemes (#51, kudos to @olejnjak)
- Make `RequestAddress` conform to `ExpressibleByStringLiteral` and `ExpressibleByStringInterpolation` (#50, kudos to @olejnjak)
- Add clear of launch screen cache on app launch for debug and beta configurations ([#47](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/47), kudos to @IgorRosocha)
- Add custom Swiftlint rule to enforce link to the Redmine ticket in TODO ([#46](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/46), kudos to @LukasHromadnik))
- Add swiftlint to rename ([#45](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/45))
- Remove useless return statements (#43, kudos to @babacros)
- Update dependencies to fix vulnerability warning ([#42](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/42))
- Add tuist integration ([#41](https://github.com/AckeeCZ/iOS-MVVM-ProjectTemplate/pull/41), kudos to @fortmarek)
- Change default project version to `0.1.0` 
- Conform `User` to `Identifiable` (#39, kudos to @fortmare)
- add new configurations which reflect currently built environment (#37, kudos to @olejnjak)