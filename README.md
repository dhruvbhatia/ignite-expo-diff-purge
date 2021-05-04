# Ignite with Expo diff PURGE

[ignite](https://github.com/infinitered/ignite) based customized version of [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge/), all credit should go to the authors of that great tool!

For Ignite without Expo please click [HERE](https://github.com/nirre7/ignite-diff-purge)

## What?

This repository exposes an untouched Ignite Expo based app generated with the ignite-cli
`nnpx ignite-cli new IgniteDiffApp --expo`. Each new Ignite release causes a new project to be created, removing the old one, and getting a diff between them. This way, the diff is always clean, always in sync with the changes of the init template.

## Diff table

| From->To | P                                                                                                  | U                                                                                                | R                                                                                                | G                                                                                                | E                                                                                                |                                                                                                  | T                                                                                                | I                                                                                                | M                                                                                                | E                                                                                                | !                                                                                                | !                                                                                                |                                                                                                  |                                                                                                  |                                                                                                  |                                                                                                  |     |
| -------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | --- |
| 6.10.0   | X                                                                                                  | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.9.2    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.9.2..release/6.10.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.9.1    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.9.1..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.9.1..release/6.9.2) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.9.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.9.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.9.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.9.0..release/6.9.1) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.8.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.8.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.8.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.8.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.8.0..release/6.9.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.7.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.7.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.7.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.7.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.7.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.7.0..release/6.8.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.6.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.6.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.6.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.6.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.6.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.6.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.6.0..release/6.7.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.5.2    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.2..release/6.6.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.5.1    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.1..release/6.5.2) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.5.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.5.0..release/6.5.1) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.4.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.4.0..release/6.5.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.3.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.5.0) | [->6.4.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.3.0..release/6.4.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.2.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.5.0) | [->6.4.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.4.0) | [->6.3.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.2.0..release/6.3.0) | X                                                                                                | -                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.1.1    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.5.0) | [->6.4.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.4.0) | [->6.3.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.3.0) | [->6.2.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.1..release/6.2.0) | X                                                                                                | -                                                                                                | -                                                                                                | -   |
| 6.1.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.5.0) | [->6.4.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.4.0) | [->6.3.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.3.0) | [->6.2.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.2.0) | [->6.1.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.1.0..release/6.1.1) | X                                                                                                | -                                                                                                | -   |
| 6.0.0    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.5.0) | [->6.4.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.4.0) | [->6.3.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.3.0) | [->6.2.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.2.0) | [->6.1.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.1.1) | [->6.1.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/6.0.0..release/6.1.0) | X                                                                                                | -   |
| 5.4.1    | [->6.10.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.10.0) | [->6.9.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.9.2) | [->6.9.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.9.1) | [->6.9.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.9.0) | [->6.8.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.8.0) | [->6.7.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.7.0) | [->6.6.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.6.0) | [->6.5.2](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.5.2) | [->6.5.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.5.1) | [->6.5.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.5.0) | [->6.4.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.4.0) | [->6.3.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.3.0) | [->6.2.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.2.0) | [->6.1.1](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.1.1) | [->6.1.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.1.0) | [->6.0.0](https://github.com/nirre7/ignite-expo-diff-purge/compare/release/5.4.1..release/6.0.0) | X   |

## To see the full table containing all releases click [HERE](https://nirre7.github.io/ignite-expo-diff-purge/)

## Notes

- The diffs start with the latest version of ignite-bowser, 5.4.1 all versions after this version is based on the updated ignite-cli which has an integrated boilerplate
- For Ignite Bowser diffs please click [HERE](https://github.com/nirre7/ignite-bowser-diff-purge)

### How did you do this?

I used the great [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge/) tool with some minor tweaks.
All credit to the creator(s) and maintainers of [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge/)

