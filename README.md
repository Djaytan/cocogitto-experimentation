# cocogitto-experimentation

Automated releasing process experimentation with Cocogitto.

## Why this repository?

This repository has been created only for archives purposes and to ease retrieval whenever it is
needed to share the experimentation done regarding this big topic.

The integration was made on
the [mc-jobs-reborn-patch-place-break](https://github.com/Djaytan/mc-jobs-reborn-patch-place-break/tree/c67b16ad54a3566b3385429c9e5affe1c01daee1).

An example of generated PR thanks to this
setup: https://github.com/Djaytan/mc-jobs-reborn-patch-place-break/pull/474

An example of generated GitHub
release: https://github.com/Djaytan/mc-jobs-reborn-patch-place-break/releases/tag/v3.0.2

## Project status

Some limitations have been observed with Cocogitto:

* https://github.com/cocogitto/cocogitto/issues/355
* https://github.com/cocogitto/cocogitto-bot/issues/22

Furthermore, it requires lots of manual setup to have a releasing process working
completely.

Finally, it seems like the project doesn't have a big traction and is not enough actively maintained
according to the evaluations needed, probably because of the existence of more mature solutions
like [semantic-release](https://semantic-release.gitbook.io/). Another reason is the fact that it
seems there is only one owner, which is not a good thing regarding open source projects.

I personally decided to go with semantic-release finally which seems to meet all my needs.
