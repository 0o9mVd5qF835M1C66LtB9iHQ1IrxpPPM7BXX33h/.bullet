# .bullet
A plaintext digital adaption designed for bullet journaling.

All credit for the original bullet journaling template goes to Ryder, creater of the Bullet Journal.

If you don't know how bullet journaling works, check this link: [Youtube: How to Bullet Journal](https://www.youtube.com/watch?v=fm15cmYU0IM&feature=youtu.be)

---

This is currently not implemented and is not a standard anywhere, but here are the specs for how to implement plaintext bullet journaling on your own, specs that can be eventually turned into a .md-like format.

## File Structure

* An index isn't needed, because everything is easy to find because you're on a computer. Grabbing a particular date's or month's notes is just a matter of searching for them.
* All date formats are in ISO-8601, the superior date format. This allows alphabetical sort to sort them chronologically.
* Months are formatted like `2020-07.md`.
* Dates are formatted like `2020-07-10.md`.
* Make a folder titled `0-collections`. This is where your collections will live.

## Syntax

```
- [ ] Todo
- [x] Finished todo
- [>] Migrated from daily log to new monthly log
- [<] Migrated to appropriate month in future log
- [~] Not worth doing
- note
* event
- [[ ]] Important todo
```
