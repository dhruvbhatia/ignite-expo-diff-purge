# Ignite with Expo diff PURGE

[ignite](https://github.com/infinitered/ignite) based customized version of [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge/), all credit should go to the authors of that great tool!

## What?

This repository exposes an untouched Ignite Expo based app generated with the ignite-cli
`nnpx ignite-cli new IgniteDiffApp --expo`. Each new Ignite release causes a new project to be created, removing the old one, and getting a diff between them. This way, the diff is always clean, always in sync with the changes of the init template.

## Diff table

| From->To | R   | N   |     | C   | O   | R   | E   |     | T   | E   | A   | M   |
| -------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5.4.1    | X   |     |     |     |     |     |     |     |     |     |     |     |

## To see the full table containing all releases click [HERE](https://nirre7.github.io/ignite-diff-expo-purge/)

## Notes

- The diffs start with the latest version of ignite-bowser, 5.4.1 all versions after this version is based on the updated ignite-cli which has an integrated boilerplate

### How did you do this?

I used the great [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge/) tool with some minor tweaks.
All credit to the creator(s) and maintainers of [rn-diff-purge](https://github.com/react-native-community/rn-diff-purge/)

