# Tom-vs-Dan

Fair voting procedure on who releases [PIMS](https://github.com/soft-matter/pims) (with logs and history).

## Rules:

- Players commit & push an empty commit (`git commit -m "I will definitely win" --allow-empty`).
- GHA will run a simple job to return a random integer in range [1, 10], including both end points.
- The player with a lower score has to do the release.
